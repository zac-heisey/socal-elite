---
title: Careers at SoCal Elite Physical Therapy
layout: page
---

<section id="contact careers">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading">{{ page.title }}</h2>
        <h3 class="section-subheading text-muted">Interested in joining the team at SoCal Elite Physical Therapy? Complete the form below and we will be in touch ASAP. Thanks!</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <form name="Careers Form" method="POST" netlify-honepot="bot-field" id="careers-form" action="/thank-you/" netlify>
          <!-- Honeypot Field -->
          <p class="hidden">
            <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
          </p>
          <div class="row">
            <div class="col-md-6">
              <div class="control-group form-group">
                <input type="text" name="name" class="form-control" placeholder="Your Name *" id="name" required>
              </div>
              <div class="control-group form-group">
                <input type="email" name="email" class="form-control" placeholder="Your Email *" id="email" required>
              </div>
              <div class="control-group form-group">
                <input type="tel" name="phone" class="form-control" placeholder="Your Phone *" id="phone" required>
              </div>
            </div>
            <div class="col-md-6">
              <div class="control-group form-group">
                <select name="position" class="form-control" required>
                  <option value="" disabled selected>Position Interested In:</option>
                  <option value="Physical Therapist">Physical Therapist</option>
                  <option value="Front Office/Receptionist">Front Office/Receptionist</option>
                </select>
              </div>
              <div class="control-group form-group">
                <label for="resume">Please Upload Your Resume (PDF format)</label>
                <input type="file" name="resume" id="resume" class="form-control" accept=".pdf" required>
              </div>
              <div class="control-group form-group">
                <textarea class="form-control" name="message" placeholder="Anything else you'd like to share?" id="message"></textarea>
              </div>
            </div>
            <div class="clearfix"></div>
            <div class="col-lg-12 text-center">
              <input type="submit" value="Send" class="btn btn-xl">
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</section>
