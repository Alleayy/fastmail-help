Why am I not getting my Fastmail emails?
=========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:
  
Fastmail is a privacy-centric email service that offers fast, secure, and reliable mail services for individuals and businesses alike. Known for its advanced security protocols, powerful spam filters, and efficient sync with email clients, Fastmail has earned a reputation for performance and ease of use. However, some users may experience a frustrating issue—emails not arriving in the inbox.
  
.. image:: not-working.png
   :alt: My Project Logo
   :width: 400px
   :align: center
   :target: https://getchatsupport.live/

Understanding Fastmail Email Delivery Issues
--------------------------------------------

If you’re wondering, “Why am I not getting my Fastmail emails?”, this guide will walk you through every possible cause, explain detailed solutions, and help you restore uninterrupted email communication. This Sphinx documentation provides a complete breakdown, ideal for users who want clarity, control, and confidence in resolving email reception issues.

Common Causes for Not Receiving Fastmail Emails
-----------------------------------------------

There are multiple factors that can impact email delivery on Fastmail. Understanding each cause helps pinpoint the problem and implement the right solution.

Inbox Filters and Rules
~~~~~~~~~~~~~~~~~~~~~~~~

Fastmail allows users to set up powerful inbox filters and rules that automate message management. However, improperly configured rules may divert emails into folders, archive them, or even delete them automatically without notification.

Spam Filtering
~~~~~~~~~~~~~~~

Fastmail uses robust spam detection algorithms. Sometimes, legitimate emails may be mistakenly flagged and sent to the Spam folder. These messages can be missed if users do not check the Spam folder regularly.

Blocked Email Addresses or Domains
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If a specific sender or domain has been blocked, their emails will not appear in your inbox or any folder. This blocklist feature is useful against spam, but can unintentionally silence important senders.

Incorrect Email Client Configuration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you use a third-party email client like Outlook, Thunderbird, or Apple Mail, incorrect IMAP or SMTP configuration can prevent email sync. Outdated port numbers, encryption settings, or authentication issues may cause undelivered messages.

Full Mailbox Storage
~~~~~~~~~~~~~~~~~~~~~

Fastmail accounts have storage limits. If your mailbox is full, new messages may be rejected or silently dropped. Unread messages from bulk senders or large attachments can fill your quota without warning.

Connectivity or Sync Issues
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A poor internet connection or sync failure in your email app can prevent new messages from showing up. In some cases, emails are received by the server but do not appear locally due to client-side sync delays.

Fastmail Server Outage
~~~~~~~~~~~~~~~~~~~~~~~

Although rare, Fastmail may experience temporary outages or service maintenance that delay message delivery. During this time, incoming emails may be queued or bounce temporarily.

External Forwarding Conflicts
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you are forwarding email from another provider to Fastmail, delivery failures at the original domain, misconfigured SPF records, or disabled forwarding settings can prevent emails from arriving.

Custom Domain DNS Misconfiguration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you are using Fastmail with your own domain name, incorrect DNS settings (such as MX, SPF, or DKIM records) can prevent Fastmail servers from receiving messages sent to that domain.

Email Throttling or Greylisting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Fastmail may throttle or temporarily delay emails from unknown sources as a spam prevention measure. This can result in delayed delivery, especially for new senders or bulk messages.

Step-by-Step Troubleshooting for Missing Fastmail Emails
---------------------------------------------------------

To resolve missing emails in Fastmail, follow the detailed troubleshooting process below. This ensures a complete check of server settings, filters, client configurations, and delivery behavior.

Check the Spam Folder
~~~~~~~~~~~~~~~~~~~~~~

First, log in to Fastmail using the web interface. Navigate to the **Spam** folder and look for legitimate emails. If found, select them and click “Not Spam.” This retrains the filter and restores the message to the inbox.

Review Inbox Filters and Rules
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Visit **Settings > Mail Rules** to inspect all existing filters. Look for any rule that:

- Moves messages to folders
- Marks them as read
- Sends them to Archive or Trash

Temporarily disable all filters and test email delivery again.

Check Blocked Senders List
~~~~~~~~~~~~~~~~~~~~~~~~~~~

In **Settings > Blocked Senders**, review and remove any blocked addresses or domains that might be preventing important emails from arriving.

Inspect Trash, Archive, and Other Folders
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Sometimes, filters move emails into folders where you might not look. Check your Archive, Trash, and custom folders to ensure emails haven't been routed there.

Verify Storage Quota
~~~~~~~~~~~~~~~~~~~~~

Go to your **Account Settings** and check the storage bar. If you're near your quota limit:

- Empty Spam and Trash folders
- Delete old emails with large attachments
- Clear unnecessary messages in the Sent folder

Recheck email delivery after freeing up space.

Test Email Access via Webmail
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Accessing Fastmail via the web interface bypasses client-specific issues. If your emails appear in the browser but not in your app, the issue lies with the third-party client.

Update or Reconfigure Email Client
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you're using Outlook, Apple Mail, or any email app:

- Remove the existing Fastmail account
- Add it again using IMAP settings
- Ensure encryption (SSL/TLS) and authentication are correctly enabled
- Use the latest version of the email client

Fastmail IMAP and SMTP configuration:

- Incoming (IMAP): `imap.fastmail.com`, Port: 993, SSL: Yes  
- Outgoing (SMTP): `smtp.fastmail.com`, Port: 465 or 587, SSL: Yes

Review Custom Domain DNS Records
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If using Fastmail with your own domain, log into your DNS provider and verify:

- MX record points to `in1-smtp.messagingengine.com`
- SPF record includes `include:spf.messagingengine.com`
- DKIM and DMARC records are present and valid

Fastmail provides tools in **Settings > Domains** to verify these entries.

Send a Test Email
~~~~~~~~~~~~~~~~~~

Send yourself a test email from another account or ask a friend to send one. If the email arrives, the issue may be sender-specific. If not, the problem is more systemic.

Contact the Original Sender
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ask the sender if they received a bounce-back message. If so, it may contain details such as blacklisting, SPF failure, or recipient domain error.

Temporarily Disable Antivirus and Firewall
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In rare cases, firewall settings or antivirus email scanning tools may interfere with your mail client. Temporarily disable them to see if email delivery resumes.

Ensure Good Network Connectivity
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Restart your router and check your internet connection. Switch from Wi-Fi to a wired network if possible. A slow connection can disrupt IMAP sync.

Preventive Tips to Avoid Future Fastmail Email Issues
------------------------------------------------------

Once resolved, you can reduce the chance of missing future emails by implementing good email management practices.

Maintain Your Filters Regularly
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Avoid over-complicating filter rules. Keep only essential filters. Test filters when adding new rules to ensure they don’t misroute messages.

Check Spam Folder Frequently
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Make it a habit to check the Spam folder weekly. Mark false positives correctly so Fastmail learns from your behavior.

Clear Inbox and Trash Monthly
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Regularly delete old or unimportant messages, especially those with large file attachments. Empty the Trash folder to free up space and prevent quota issues.

Whitelist Trusted Senders
~~~~~~~~~~~~~~~~~~~~~~~~~~

Add contacts to your Fastmail address book. Trusted senders are less likely to be marked as spam when they're already known to your contact list.

Keep Email Clients Updated
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Always use the latest version of your mail app or browser. Updates ensure compatibility with Fastmail’s current security protocols.

Monitor DNS for Custom Domains
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you manage your own domain, recheck your DNS settings monthly. Use Fastmail’s domain checker tool to confirm that SPF, DKIM, MX, and DMARC are configured properly.

Avoid Blocking Senders Accidentally
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Only block senders after verification. Avoid blocking entire domains unless absolutely necessary.

Enable Notifications and Sync Alerts
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use mobile or desktop notifications to get real-time updates about new messages. This ensures you notice if new emails are not coming in as expected.

Use Two-Factor Authentication
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Protect your account with 2FA to prevent unauthorized access and potential compromise that could affect incoming mail.

Monitor System Status
~~~~~~~~~~~~~~~~~~~~~

Visit Fastmail’s system status page occasionally to check for global outages. Being aware of system issues can help you avoid unnecessary troubleshooting.

When to Contact Fastmail Support
--------------------------------

If none of the above solutions work, reach out to Fastmail’s support team. Contact support when:

- Emails are missing from both webmail and all devices
- No bounce-back or delivery notification is received
- Storage appears normal but new messages are not delivered
- You suspect account suspension or compromise
- DNS settings are correct but domain mail is not arriving

Fastmail support can provide detailed backend logs and analysis to identify server-side issues or misconfigurations.

Conclusion: Restore Reliable Fastmail Email Reception
------------------------------------------------------

If you're asking, “Why am I not getting my Fastmail emails?”, the issue could be a simple filter setting, a misconfigured email client, or a more technical DNS issue with a custom domain. By following this comprehensive troubleshooting and prevention guide, you can identify, correct, and avoid email delivery issues with confidence.

Fastmail is designed to be secure, fast, and intelligent, but like all technologies, it requires proper configuration and regular maintenance. With this documentation as your reference, you can keep your inbox clean, organized, and consistently receiving the messages you expect.

This guide is a complete Sphinx documentation resource to help you diagnose missing email issues, answer your email-related questions, and maintain reliable email delivery on Fastmail.
