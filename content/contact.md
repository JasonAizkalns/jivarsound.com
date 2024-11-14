---
title: Contact | j.ivar
description: Contact j.ivar -- musician, producer, songwriter, and studio owner. Fill out this form for business inquiries, questions, comments, or just to say 'hey'.
---
<main class="mw7-ns center avenir near-white bg-near-black o-90 w-90 pa4 mt4">
  <h1 class="ttu tracked mt0 f2-ns f3 mb3">Get in Touch</h1>
  <div class="bt b--white-80"></div>
  <form id="contactform" class="avenir measure center" method="POST">
    <fieldset id="sign_up" class="b--transparent ph0 mh0">
      <!-- <legend class="f4 fw6 ph0 mh0 ttu tracked">Get in touch</legend> -->
      Temporary fields for verification:<br><br>
      My Name: Jason Aizkalns (a.k.a. j.ivar)<br>
      Primary Email: Jason.Aizkalns@gmail.com<br>
      Secondary Email: j.ivar.sound@gmail.com
      <div class="mt3">
        <label class="db fw6 lh-copy f6" for="_replyto">Email</label>
        <input class="bn pa2 input-reset bg-near-white hover-bg-lightest-blue hover-near-black w-100" type="email" name="_replyto" placeholder="Your email">
      </div>
      <div class="mv3">
        <label class="db fw6 lh-copy f6" for="message">Message</label>
        <textarea class="bn pa2 input-reset bg-near-white hover-bg-lightest-blue hover-near-black w-100" rows="6" name="message" placeholder="Your message"></textarea>
      </div>
      <input type="hidden" name="_subject" value="website contact"/>
      <input type="text" name="_gotcha" style="display: none;"/>
    </fieldset>
    <button class="b bn near-black ph3 ml1 pv2 input-reset bg-near-white grow hover-bg-lightest-blue pointer f6 dib" type="submit">Send</button>
  </form>
</main>

<script>

  var contactform =  document.getElementById('contactform');
  contactform.setAttribute('action', '//formspree.io/' + 'j.ivar.sound' + '@' + 'gmail' + '.' + 'com');

</script>
