---
title: FAQ | j.ivar
description: Frequently asked questions (FAQ) page for jivarsound.com.
---

<main class="mw7-ns center avenir near-white bg-near-black o-90 w-90 pa4 mt4" id="faq-content">
  <h1 class="ttu tracked mt0 f2-ns f3 mb3">Frequently Asked Questions</h1>
  <div class="bt b--white-80 pb3"></div>
  <section class="avenir measure center">
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      How do a I purchase a beat?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        Purchasing beats is easy! First, {{< link-no-border "browse our catalogue of beats" "../#beat-store" >}}. If you've got a
        specific style or artist type of beat you're looking for, you can use the top search bar. When you've made your choice, click "add to cart", select your license, and proceed to checkout.
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      Are the beats still tagged when I purchase a beat?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        No, all licenses come with untagged files. For more information on our available licenses, please see our {{< link-no-border "licensing page" "/licensing" >}}.
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      When will I receive my files?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        After checkout from the beat store, all files are sent immediately to the email address that was
        used to make the purchase.
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      What is the file format and sample rate of the beats?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        All files are sent in .wav 24-bit 44.1 kHz (or higher) and/or .mp3 320 kbps.
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      Where can I find information about licensing?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>More information about or licensing options is available {{< link-no-border "on our licensing page" "../licensing" >}}. In addition, you can also read the {{< link-no-border "Everything You Need to Know About Buying beats Online" "/blog/everything-you-need-to-know-about-buying-beats-online" >}} guide for more information.</p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      What is your price for exclusive rights?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        Exclusive rights start at $799, but depend on the artist and the beat. <em>We <span class="underline">do not</span> sell exclusive rights to every artist.</em> If you are interested in purchasing rights for a beat, please {{< link-no-border "contact us" "/contact" >}} and provide the following information:
        <ul>
          <li>Full Name</li>
          <li>Artist Name</li>
          <li>The beat title of interest</li>
          <li>Link(s) to your recent songs and socials</li>
        </ul>
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      Can you create me a custom beat?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        Yes! Custom beats are on a case-by-case basis, but please {{< link-no-border "get in touch" "/contact" >}} to get the conversation going. We will then work with you to craft and create custom product to fit your needs and budget.
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      Where are you located?
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        Sinking Spring, Pennsylvania, USA. Just west of Reading, PA. About 1.5 hours from Philadelphia, 2 hours from Baltimore, 2.5 hours from NYC, and 3 hours from Washington, D.C.
      </p>
    </div>
    <button class="w-100 tl collapsible bg-animate near-white ba b--near-white pv1">
      I have a different question...
    </button>
    <div class="content-collapse mb1 bg-near-black near-white bl br">
      <p>
        We got you. Please {{< link-no-border "reach out to us" "/contact" >}} and we'll get back to you as soon as possible.
      </p>
    </div>
  </section>
</main>

<script>

var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight) {
      content.style.maxHeight = null;
      content.style.borderBottom = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
      content.style.borderBottom = "solid 1px"
    }
  });
}

</script>
