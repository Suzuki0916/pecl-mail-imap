====
IMAP
====

This is the IMAP extension extracted from the PHP source distribution.
PHP versions after PHP 8.3 no longer bundle this extension.

This extension is no longer actively maintained or supported, and this
repository serves as an archive for it.

The documentation is still available as part of the `PHP Documentation
<https://www.php.net/imap>`_.

Installation Issues
-------------------

In order for this extension to compile, you need to have the ``c-client``
installed.

Debian
~~~~~~

On Debian based systems, you can do that with ``apt-get``. As this
distribution installed library is compiled with Kerberos and SSL support, you
need to make sure to have these development libraries installed too.

You can install all of these with::

	apt-get install libc-client-dev libkrb5-dev libssl-dev

When running PECL, you may not disable either Kerberos or SSL support, as the
system installed c-client requires it.
