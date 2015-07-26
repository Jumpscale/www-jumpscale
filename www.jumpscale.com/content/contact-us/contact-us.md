+++
#Don't remove title!
title = "Contact Us"

+++

<form id="contact-form" action="//formspree.io/info@jumpscale.com" method="POST" class="form-horizontal">
  <input type="hidden" name="_next" value="/thanks" />
  <input type="hidden" name="_subject" value="Message from JumpScale wesbite" />
  <input type="text" name="_gotcha" style="display:none" />
  <div class="control-group">
    <input type="text" name="name" placeholder="Your Name" class="form-control">
  </div>
  <div class="control-group">
    <input type="email" name="_replyto" placeholder="Your E-mail" class="form-control">
  </div>
  <div class="control-group">
    <textarea rows="4" cols="50" name="message" placeholder="Your Message" class="form-control"></textarea>
  </div>
  <div class="">
    <button  type="submit" value="Send" class="btn btn-primary">Submit</button>
  </div>
</form>
