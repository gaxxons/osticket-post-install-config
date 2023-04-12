<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
Once osTicket has been installed you need to further configure it via admin panel before it is fully usable. Only staff with admin’s privileges can access the admin panel. Please use the username and password created during the install process.<br/></p>


<h2>Video:- Gmail Configuration</h2>

<p>In order to use Gmail, your host must support SSL, so osTicket can negotiate the secure connection, and you must enable IMAP or POP in your GMail or GApps account. Configure in osTicket (the easy part)

Under Admin panel -> Emails -> Emails -> Sending email via SMTP For most people, enter either ssl://smtp.gmail.com with port 465 or tls://smtp.gmail.com with port 587.

note: If you have a google apps/G-Suite account, this might change, see below.

Select “Authentication Required”. Leave Header Spoofing unchecked. Make sure your username is your full email and password are set correctly in the Email Login Information

If you test at this point and it doesn’t work, continue reading.

You may need to consult your PHP error log (the location varies by OS and personal preferences so consult your php.ini to determine its location). The PHP error log often contains more information as to why something is not working correctly.</p>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

<b>1</b>- <p>
<img src="https://res.cloudinary.com/lwgatsby/f_auto/www/uploads/2021/07/osticket1-web-based-installation.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h5><b>2</b>- Complete the form below to establish your admin user and database settings. Once finished, click Install Now.</h5>
<p><img src="https://res.cloudinary.com/lwgatsby/f_auto/www/uploads/2021/07/osticket2-basic-installation.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></P>
<h5><b>3-</b> After installing osTicket, you can configure your support ticket system.</h5>
<p><img src="https://res.cloudinary.com/lwgatsby/f_auto/www/uploads/2021/07/osticket1-web-based-installation.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></P>

<h2>Some helpful links you will find on this page are:</h2>
Your osTicket URL: Where your customers can submit support requests created via email.
Your Staff Control Panel: Where users can access the admin panel to control various settings.
osTicket Forums: Where users can ask and answer osTicket questions.
osTicket Community Wiki: Where users can find additional osTicket documentation.

<h1>Conclusion</h1>
osTicket is a very useful tool for your support system and is completely free. Not everyone needs an enterprise product like SalesForce or Zendesk, which is where osTicket comes in. After familiarizing yourself with osTicket, handling customer inquiries created via email will become a breeze.
