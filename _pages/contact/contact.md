---
layout: page
permalink: /contact/
title: CONTACT
comments: false
---

<hr />

If you have any comments related with the blog, feel free to send me a message:

<form name="AgileDataScientist.com" id="contact-form" method="post" action="//formspree.io/javier.estraviz+agiledatascientist@gmail.com">
  
  <div id="wrapping">

    <section id="aligned">
    <h4>
      <i class="fa fa-user"></i>&nbsp;&nbsp;Name <span class="redcolor">*</span>
      <input type="text" name="name" id="name" autocomplete="off" tabindex="1" class="highlight" required="" placeholder="Your name" onfocus="getFocus(this);" onblur="loseFocus(this);">
      
      <i class="fa fa-envelope"></i>&nbsp;&nbsp;E-mail <span class="redcolor">*</span>
      <input type="email" name="email" id="email" autocomplete="off" tabindex="2" class="highlight" required="" placeholder="E-mail address (will not be public)" onfocus="getFocus(this);" onblur="loseFocus(this);">
      
      <i class="fa fa-globe"></i>&nbsp;&nbsp;Website
      <input type="url" name="website" id="website" autocomplete="off" tabindex="3" class="highlight" placeholder="Website (optional)" onfocus="getFocus(this);" onblur="loseFocus(this);">
      
      <i class="fa fa-pencil"></i>&nbsp;&nbsp;Message <span class="redcolor">*</span> 
      <textarea name="message" id="message" tabindex="4" class="highlight" required="" placeholder="Enter your comments here" onfocus="getFocus(this);" onblur="loseFocus(this);"></textarea>
      <small class="normalweight"><i>Fields marked with an <span class="redcolor">*</span> are required</i></small>
    </h4>    
    </section>

    <section id="buttons">
      <span class="pull-right">
        <button type="reset" name="reset" id="resetbtn" class="btn btn-reset" tabindex="6"><i class="fa fa-times"></i>&nbsp;&nbsp;Reset</button>
        <button type="submit" name="submit" id="submitbtn" class="btn btn-send" tabindex="7"><i class="fa fa-paper-plane"></i>&nbsp;&nbsp;Send</button>
      </span>
      <br style="clear:both;">
    </section>

  </div>

  <input type="hidden" name="_next" value="//agiledatascientist.com/contact/thank-you.html" />

</form>
