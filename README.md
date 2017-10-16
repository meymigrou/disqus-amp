# disqus-amp
Disqus HTML file that works for AMP supported websites

Create a new subdomain (example: comments.example.com) in your server that fully supports SSL/HTTPS.
Download the disqus.html file and upload it on your server.
Download and install the Accelerated Mobile Pages plugin on WordPress.
Go to AMP --> Settings --> Comments --> disable the 'Host Disqus Comments through AMPforWP Servers' option and add your Disqus shortname
(url) and on 'Disqus Host File' field add the url from the subdomain you've created (example: comments.example.com/disqus.html).
