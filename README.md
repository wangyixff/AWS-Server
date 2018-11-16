# Linux Server Configuration
This project is to set up a Linux server with good security settings, a running web server, and deployment of the Item Catalog project.

The web service provider used is AWS Lightsail.

## Essentials for the Reviewer

### Passphrase for "grader" login
catalog
### IP address
34.211.35.166
### Website URL
http://34.211.35.166.xip.io
### Software installed
- Apache2
- Pip
- Python3
- Flask
- Oauth2lib
- Sqlachemy
- sqlite
- mysql
- finger
- python-setuptools
### Configurations made
- Remote login of the root user is disabled
- Grader user is given sudo access
- Firewall is configured to only allow for SSH(2200), HTTP(80), and NTP(123)
- Key-based SSH authentication is enforced
- Web server has been configured to serve the Item Catalog application as a WSGI app
## References

- Udacity FSWD course materials
- Item description texts are from https://www.sportchek.ca
