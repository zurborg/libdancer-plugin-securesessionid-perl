# NAME

Dancer::Plugin::SecureSessionID - A secure replacement of Dancer's built-in session id generator

# VERSION

Version 0.01

# DESCRIPTION

This plugin overrides the `build_id()` method in [Dancer::Session::Abstract](https://metacpan.org/pod/Dancer::Session::Abstract) and make use of [Crypt::Random](https://metacpan.org/pod/Crypt::Random) to get really secure random session ids.

# AUTHOR

David Zurborg, `<zurborg@cpan.org>`

# SUPPORT

You can find documentation for this module with the perldoc command.

    perldoc Dancer::Plugin::SecureSessionID

You can also look for information at:

- Redmine: Homepage of this module

    [http://development.david-zurb.org/projects/libdancer-plugin-securesessionid](http://development.david-zurb.org/projects/libdancer-plugin-securesessionid)

- RT: CPAN's request tracker

    [http://rt.cpan.org/NoAuth/Bugs.html?Dist=Dancer-Plugin-SecureSessionID](http://rt.cpan.org/NoAuth/Bugs.html?Dist=Dancer-Plugin-SecureSessionID)

- AnnoCPAN: Annotated CPAN documentation

    [http://annocpan.org/dist/Dancer-Plugin-SecureSessionID](http://annocpan.org/dist/Dancer-Plugin-SecureSessionID)

- CPAN Ratings

    [http://cpanratings.perl.org/d/Dancer-Plugin-SecureSessionID](http://cpanratings.perl.org/d/Dancer-Plugin-SecureSessionID)

- Search CPAN

    [http://search.cpan.org/dist/Dancer-Plugin-SecureSessionID/](http://search.cpan.org/dist/Dancer-Plugin-SecureSessionID/)

# COPYRIGHT & LICENSE

Copyright 2014 David Zurborg, all rights reserved.

This program is released under the following license: open-source
