---
title: "Contact"
date: 2022-08-09T20:01:06+07:00
draft: false
seo_description: ""
seo_keyword:
  - keyword1
  - keyword2
thumbnail: "posts/example.jpg"
slug: "contact"
formspree: "mpzbpgww"
---

<form action="https://formspree.io/f/{{< param formspree >}}" method="POST">
<p class="mb-4">Please send your message to myLightning.Network. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>
<input class="btn btn-success" type="submit" value="Send">
</form>