---
layout: page
title: Contact
tag: Contact
---
<div class="contact">
Have any questions, feedback, or suggestions? Feel free to send me an email using the form bellow.

<form id="contactform" name='contactform' onsubmit="return validateForm()" method="POST">
    <input type="text" name="name" class="feedback-input" placeholder="Name">
    <input type="email" name="_replyto" class="feedback-input" placeholder="Email">
    <input type="hidden" name="_subject" value="Portfolio Contact" />
    <textarea name="message" class="feedback-input" placeholder="Message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="_next" value="//twarrre.github.io/thanks.html" />
    <input type="checkbox" name="cbox"> Receive copy of email.
    <input type="hidden" name="_cc" />
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 't' + 'wa' + 're' + '41' + '94' + '@' + 'gmail' + '.' + 'com');
</script>

</div>