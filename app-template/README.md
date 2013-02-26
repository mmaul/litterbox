NAME: app-template

VERSION: .01  

AUTHOR: Your Name Here

AUTHOR_EMAIL: 

PKG_URL: https://github.com/mmaul/app-template

DESCRIPTION: Generic Application Template

CATEGORY: Template

LIBDIR: app

-----
Quickstart SetupTool application template for a generic application.

## Quickstart Installation ##
* 'install' must be able to write to Felix INSTALL_ROOT

    scoop get app-template myapp --degitify

You can leave off the ''myapp --degitify'' if you want, that just tell scoop 
to strip the .git repo information and to drop app-template in the myapp directory. It is will be your app after all...

Now start writing your new killer app for Felix.
By default executate app code is in the bin directory so just start hacking
bin/app.flx 


BTW: if you feel like sharing, put you app up in github and send this README.md (updated with your app's info of course) to felix-language[At]googlegroups[DOT]com and we will stick it in the litterbox so all can enjoy.

P.S if your new to the PkgTool (of which SetupTool is the builder) check out some docs at http://github.com/mmaul/pkgtool
