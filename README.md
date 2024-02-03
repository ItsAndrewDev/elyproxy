# FortressProxy
![Bastion GLP License](https://img.shields.io/badge/Bastion-GLP%20v1.05-blue) ![Stand With UKRAINE](https://img.shields.io/badge/Stand%20With-UKRAINE-yellow) ![Free PALESTINE](https://img.shields.io/badge/Free-PALESTINE-darkgreen)  
FortressProxy is a simple PHP system to send requests to the Ely.by Authserver through your own web server.  

## How it Works
It's simple! You can send POST requests to your server and it will be passed to Ely.by's Authserver.  
You can expect a standard JSON response from the server [as per the documentation](https://docs.ely.by).  
This is useful especially if your organisations \(eg. Schools\) block requests to https://authserver.ely.by.  

## Deployment
_Download_ the Package ZIP from the [_Latest Release_](https://github.com/ItsAndrewDev/elyproxy/releases/latest).  
_Extract_ the ZIP into your Web Server (regardless of where).  

You can now make requests to https://_yourwebserver_._tld_/_\(whatever-url-for-elyby\)_  
Instead of https://_authserver_._ely_._by_/_\(whatever-url-for-elyby\)_.  
  
## Credits
Much of the PHP code for the _OAuth2 Authorisation_ procedure is adapted from the [_Ely.by Documentation_](https://docs.ely.by/en/oauth.html).  
The _Ely.by Documentaion_ is written by the _Ely.by_ team.
