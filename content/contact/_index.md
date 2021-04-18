---
title: Contact
description: Drop me a note and say hello!
layout: single
hideMeta: true
disableShare: true
ShowPostNavLinks: false
---

{{<rawhtml>}}
<script type="text/javascript">var submitted=false;</script>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {window.location='/contact/?status=submitted';}"></iframe>
<form action="https://docs.google.com/forms/d/e/1FAIpQLSeHh8Z5G_iZvZxLMhxwhp0p2MzxRea-r4vU1nchYW1yaRZBwg/formResponse" method="post" target="hidden_iframe" onsubmit="submitted=true;"></form>

<div id="contact_message">Your message has been successfully sent!</div>

<form class="form" action="https://docs.google.com/forms/d/e/1FAIpQLSeHh8Z5G_iZvZxLMhxwhp0p2MzxRea-r4vU1nchYW1yaRZBwg/formResponse" method="post" target="hidden_iframe" onsubmit="submitted=true">
    <label>Name</label>
    <input type="text" placeholder="Martha Stewart" class="form-input" name="entry.2005620554" required>

    <label>Email</label>
    <input type="email" placeholder="martha@example.com" class="form-input" name="entry.1045781291" required>

    <label>Message</label>
    <textarea rows="5" placeholder="Your message" class="form-input form-textarea" name="entry.839337160" required></textarea>

    <button type="submit" class="button form-submit-button">Submit</button>
</form>

<script type="text/javascript">
  var urlParams = new URLSearchParams(window.location.search);

  if (urlParams.has('status') && urlParams.get('status') == "submitted") {
    var message = document.getElementById("contact_message");
    message.classList.add("success")
  }
</script>
{{</rawhtml>}}
