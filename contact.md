---
title: Contact
layout: page
---


<script src="assets/openpgp.min.js" type="text/javascript"></script>
<script src="assets/contact-pgp.js" type="text/javascript"></script>


<h3>Contact me</h3>

<p>This is a secure contact form with end-to-end encryption.<br/>
Your message will be encrypted in the browser before being sent, thanks to <a href="https://openpgpjs.org" target="_blank">OpenPGP.js</a>.</p>

<form id="form" method="post" action="https://blog.mayel.space/_/contact-pgp/send_form.php">
	<table width="100%">
		<tr>
	  		<td valign="top">
	   			<label for="email">Your&nbsp;Email</label>
	 		</td>
	  		<td valign="top">
	   			<input type="text" name="email" style="width:100%; font-size:14px" required="true">
	  		</td>
	 	</tr>
		<tr>
			<td valign="top">
				<label for="message">Message</label>
			</td>
			<td valign="top">
				<textarea  id="message" name="message" style="height:180px; width:100%; min-width:450px; font-size:14px" required="true" placeholder="If you have a PGP public key, please include a link (or copy/paste it into the message) if you want a secure reply."></textarea>
		 </td>
		</tr>
		<tr>
		  	<td >
			</td>
			<td >
				<input type="submit" value="Encrypt & Send">
		  	</td>
		</tr>
	</table>
</form>
