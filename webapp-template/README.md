NAME: webapp-template

VERSION: .011  

AUTHOR: Your Name Here

AUTHOR_EMAIL: 

PKG_URL: https://github.com/mmaul/webapp-template

DESCRIPTION: Generic Application Template

CATEGORY: Template, WWW, Web

LIBDIR: app

-----
Quickstart SetupTool application template for a generic web application.

## Quickstart Installation ##
* 'install' must be able to write to Felix INSTALL_ROOT

    scoop get app-template myapp --degitify

You can leave off the ''myapp --degitify'' if you want, that just tell scoop 
to strip the .git repo information and to drop app-template in the myapp directory. It is will be your app after all...

Now start writing your awesome new web app for Felix.
By default web application code is in the app directory so just start hacking
app/webapp-template.flx 

Static html, javascript and css are stored in the html directory. Finally the
server configurationfile is stored in config server-config.cfg

BTW: if you feel like sharing, put you app up in github and send this README.md (updated with your app's info of course) to felix-language[At]googlegroups[DOT]com and we will stick it in the litterbox so all can enjoy.

P.S if your new to the PkgTool (of which SetupTool is the builder) check out some docs at http://github.com/mmaul/pkgtool

P.P.S for more inforation on the web programming framework for Felix see:

* example code in INSTALL_ROOT/lib/web/examples/
* library code in INSTALL_ROOT/lib/web