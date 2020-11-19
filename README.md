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

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
