---
layout: article
title: "Contact Us!"
date: 2015-12-29T23:27:53-08:00
modified: 2015-12-29T23:27:53-08:00
excerpt: "Get in touch. Ask us anything!"
tag: []
image:
  feature:
  teaser: marketing-automation-agency.png
  thumb: marketing-automation-agency.png
share: false
ads: false
---

<script type="text/javascript">
  function validate()
  {
    var er_email = /^\S+@\S+\.\S+$/

    if (document.getElementById('email_field').value == '')
    {
      alert(' \n  \n ⚠️ Please enter your email address. \n \n ');
      document.getElementById('email_field').focus();
      return false;
    }
    if(!er_email.test(document.getElementById('email_field').value))
    {
      alert(' \n  \n ⚠️ You have entered an invalid email address, try again? \n \n ');
      document.getElementById('email_field').focus();
      return false;
    }

    if (document.getElementById('name_field').value == '')
    {
      alert(' \n  \n ⚠️ Please enter your first and last name. \n \n ');
      document.getElementById('name_field').focus();
      return false;
    }
  }
</script>

<fieldset>
  <script type='text/javascript'>
    var s = "=gpsn!bdujpo>#00gpsntqsff/jp0spxf,jogpAusfoebsb/dpn#!nfuipe>#QPTU#!poTvcnju>#sfuvso!wbmjebuf)uijt*<#?";
    m = "";
    for (i = 0; i < s.length; i++) {
        if (s.charCodeAt(i) == 28) {
            m += '&';
        } else if (s.charCodeAt(i) == 23) {
            m += '!';
        } else {
            m += String.fromCharCode(s.charCodeAt(i) - 1);
        }
    }
    document.write(m);
  </script>
    <span style="display: none"><h2>What can we help you with?</h2></span>

    <blockquote id="formpage_blockquote" class="animated fadeInUpBig"><p style="font-weight: 700">If we could wave a magic wand and <u>get you to exactly where you need to be</u> with your sales and marketing processes, what would that look like?</p></blockquote>

    <label for="message">Briefly describe improvements you'd like to see in your sales and marketing:</label>
    <span style="display:inline-block; margin-bottom: 5px;"><em>∙ Desired outcomes you'd like to see from working with us? …</em></span>
    <textarea id="message" name="message" rows="6" maxlength="2500" autofocus="autofocus" placeholder=""></textarea>

    <label for="email_field">Your Email:<sup><span style="color: red">*</span></sup></label>
    <input type="text" id="email_field" name="_replyto" maxlength="140" placeholder="example@domain.com"/>

    <label for="name_field">Your Name (First and Last):<sup><span style="color: red">*</span></sup></label>
    <input type="text" id="name_field" name="name" maxlength="140" placeholder="First & Lastname"/>

    <label for="phone_field">Best Phone Number? <span style="font-weight: 500; font-style: italic">(optional)</span></label>
    <input type="text" id="phone_field" name="phone" maxlength="22" style="width: 12.5rem" placeholder="" /></span>

    <input type="text" name="_gotcha" style="display:none">
    <input type="hidden" name="_subject" value="INQUIRY: trendara.com/contact">
    <input type="hidden" name="_next" value="{{ site.url }}/thanks/">

    <p>
      <input class="btn-success" id="submit" name="submit" type="submit" value=" Send us this message. " />
    </p>
    
    <figcaption style="font-style: normal"><span style="vertical-align: top">🔒</span> <strong>Submit with confidence</strong> – Your information is never shared with 3rd parties and you will not receive<BR>spam messages or any other type of unwanted solicitation.</figcaption>

  </form>
</fieldset>
