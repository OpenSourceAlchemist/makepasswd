# makepasswd

## Create and/or encrypt true-random-seeded password strings.

This work did not start with me.  I pulled it from the Debian package archive
during my efforts to package it for [VoidLinux](http://www.voidlinux.eu/).  I
decided to create this git repo in order to help this code live on in a
hopefully distribution-agnostic form.  I've used makepasswd for most of this
century so far when I've needed a password quickly to meet specific criteria.
I hope it is useful to you too.

Many thanks to the various Debian contributors who kept this tool relevant
over the years:

- Johnie Ingram (Initial packager, fixed --string)
- Javier Fernandez-Sanguino Pen~a (Added MD5 password generation, break
  --clear, UTF-8 cleanup)
- Colin Watson (Debian maintainer since 2003, documented --crypt-md5, many
  fixes and modernizations)

Finally, thanks to lilo (Rob Levin) who brought this tool to us before his
passing.  His original README is produced below.

###  ORIGINAL README from lilo:
> As has been my custom of late, this program is released under the terms of
> GNU COPYING-2.  Don't apply any other version of the GNU license to it. If
> some legal precedent ends up biting us in the nose, write me and I'll tweak
> the license accordingly.
> 
> In that case, or in case you want to laud or castigate me for some imagined
> slight, feel free to email me at lilo@linpeople.org.
> 
> 
> lilo
