---
title: Contact Us
nav_order: 5
---

<script src="https://code.jquery.com/jquery-2.1.4.min.js"></script>

<div id="feedback-form">form will be placed in here</div>

<script id="zammad_form_script" src="https://mail.bedlamtheatre.co.uk/assets/form/form.js"></script>

<script>
$(function() {
  $('#feedback-form').ZammadForm({
    messageTitle: 'Contact Us - Constitution',
    messageSubmit: 'Submit',
    messageThankYou: 'Thank you for your inquiry (#%s)! We\'ll contact you as soon as possible.',
    noCSS: true
  });
});
</script>