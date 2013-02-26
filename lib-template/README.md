NAME: lib-template

VERSION: .01  

AUTHOR: Your Name Here

AUTHOR_EMAIL: 

PKG_URL: https://github.com/mmaul/lib-template

DESCRIPTION: Generic Application Template

CATEGORY: Template

LIBDIR: LIB-TEMPLATE

-----
Quickstart SetupTool application template for a generic library.

## Quickstart Installation ##
* 'install' must be able to write to Felix INSTALL_ROOT

    scoop get lib-template myapp --degitify

You can leave off the ''myapp --degitify'' if you want, that just tell scoop 
to strip the .git repo information and to drop app-template in the myapp directory. It is will be your app after all...

Now start writing your binding for the phyics or 3D game engine for Felix.


BTW: if you feel like sharing, put you app up in github and send this README.md (updated with your app's info of course) to felix-language[At]googlegroups[DOT]com and we will stick it in the litterbox so all can enjoy.

P.S if your new to the PkgTool (of which SetupTool is the builder) check out some docs at http://github.com/mmaul/pkgtool
