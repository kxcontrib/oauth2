# oauth2

Companion code to the blog post at

https://kx.com/blog/oauth2-authorization-using-kdb/

Note the pre-requisites in the blog.
In this example, the OAuth2 endpoint is to google. This can be configured at your google account,
https://console.developers.google.com/
Here, you can enable your OAuth2 'account', and in return you'll obtain a client ID & secret.
This can then be added to your kx_client.json file

cat kx_client.json
{"web":{"client_id":"REDACTED","project_id":"REDACTED","auth_uri":"https://accounts.google.com/o/oauth2/auth","token_uri":"https://accounts.google.com/o/oauth2/token","auth_provider_x509_cert_url":"https://www.googleapis.com/oauth2/v1/certs","client_secret":"REDACTED"}}
