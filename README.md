KindlePeriodicUploader
======================

This script tries to load from net new periodics and upload it onto your kindle by email.

USAGE
=====================

You should write your email, password and kindle email into /etc/pk.conf
You should write list of hyperlinks to download periodic into file /etc/pk.lst. Each line should be a ref and a number. Change number in ref to %% and write last number in file.
See example in /etc/pk.lst


BUGS
======================

Now works only with yandex mail.
