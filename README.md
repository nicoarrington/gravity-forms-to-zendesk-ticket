# Gravity Forms to Zendesk Ticket (functions.php version)

Gravity Forms to Zendesk Ticket is a simple Wordpress functions.php filter to pass Gravity Forms fields to a Zendesk ticket, including attachments.  It utilizes the [Zendesk v2 API](https://developer.zendesk.com/rest_api/docs/core/introduction), PHP, and cURL.

This functions.php filter was created for theme developers that want to integrate in this functionality by default.  If you're looking to integrate Zendesk functionality by add-on that is not dependent on a theme, please see the [Gravity Forms Zendesk Add-On](https://github.com/christirichards/gravity-forms-zendesk) (in development).

### Version
1.0.0

### Requirements

You need a working Wordpress installation, Gravity Forms plugin installed and at least one form to reference, Zendesk API key/credentials, and cURL enabled on your server.

### To Use

- Include the filter file from your own Wordpress theme's function.php file or cut/paste the contents of inc/gravity-forms-to-zendesk-ticket.php into your own functions.php file.

- Update the Zendesk API credentials in the script.

- Reference the correct Gravity Form form ID in the filter reference.

- Reference the appropriate Gravity Form form field IDs in the ticket generation portion to send to Zendesk.

- **Please note: this script is for one attachment per ticket, for multi-file uploads the script will need to be modified to split the request [currently on the To Do]**

### To Do

 - Split requests to handle multiple file uploads per ticket.

 - Add in a Wordpress settings panel to easily add in Zendesk API key, e-mail, and subdomain.

License
----

MIT

Contact
----

[Christi Richards](http://www.christirichards.com)

[@christirichards](http://twitter.com/christirichards)