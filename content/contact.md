---
title: "Contact"
date: 2021-02-08T19:44:33-05:00
draft: false
page: true
---

{{< rawhtml >}}
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mqkwwoog" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="" required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
</form>
{{< /rawhtml >}}