freistilbox-base-wordpress
==========================

The is the base repository for WordPress websites hosted on [freistilbox](http://www.freistilbox.com).

To use it, first clone your website repository:

    $ git clone ssh://sNUMBER@repo1.freistilbox.net/~/site mysite
    $ cd mysite

Then pull in the base repository:

    $ git remote add base git://github.com/freistil/freistilbox-base-wordpress.git
    $ git pull base master

Repeat the `git pull` to update your website from our base repository.
