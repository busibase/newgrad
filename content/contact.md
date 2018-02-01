+++
title = "Register"
weight = 40
draft = false
+++

レジュメを添付の上、ご登録ください。

<form method="post" action="mailto:busi.base.tk@gmail.com">
	<div class="field half first">
		<label for="name">Name</label>
		<input type="text" name="name" id="name" />
	</div>
	<div class="field half">
		<label for="email">Email</label>
		<input type="text" name="email" id="email" />
	</div>
	<div class="field">
		<label for="message">Message</label>
		<textarea name="message" id="message" rows="4"></textarea>
		<input type="file" name="attachment"> 
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send Message" class="special" /></li>
		<li><input type="reset" value="Reset" /></li>
	</ul>
</form>

{{< socialLinks >}}
