*Check Submission User Password Expiration Date*
=============


Script will return the expiration date for any given domain user name.
http://github.com/Automic-Community/Check-Submission-User-Password-Expiration-Date

<!-- List of attached files -->
Contents of Solution Package:

						
								*Check_User_Expiry_Date.zip
								
						


Documenation and Instructions
---

<p>This script will return the expiration date for any given domain user name (passed as a Parameter).<br /><br /><br /><span class="bbc_underline"><strong class="bbc">Expected Behavior:</strong></span><br /><br /><strong class="bbc">If password expiration date is more than 10 days in the future:</strong><br /><br /></p>
<p>Script will end successfully and return the number of days before expiration</p>
<p><br /><strong class="bbc">If password expiration date is less than 10 days, but more than 3 days in the future:</strong><br />The script will end successfully but return a warning prompting to change the password</p>
<p><br /><strong class="bbc">If password expiration date is less than 3 days in the future:</strong><br /> The script will abort and return a warning prompting to change the password immediatly</p>
<p>&nbsp;</p>
<p><strong class="title">Target environments:</strong> Windows</p>
<p><strong class="title">Prerequisites:</strong> Powershell</p>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (http://automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (http://automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).