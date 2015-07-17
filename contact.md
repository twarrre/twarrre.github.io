---
layout: page
title: Contact
tag: Contact
---
<div class="contact">

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Name">
    <input type="email" name="_replyto" placeholder="Email">
    <input type="hidden" name="_subject" value="Portfolio Contact" />
    <textarea name="message" placeholder="Message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="_next" value="//twarrre.github.io/thanks.html" />
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 't' + 'wa' + 're' + '41' + '94' + '@' + 'gmail' + '.' + 'com');
</script>

</div>
