---
layout: page
title: Apple iCal Support
---

After a long, long work, the iCal support has finally been added to Radicale!
Well, this support is only for iCal 4 and is highly experimental, but you can
test it right now with the git master branch. Bug reports are welcome!

Dear MacOS users, you can thank all the gentlemen who sended a lot of debugging
iformation. Special thanks to Andrew from DAViCal, who helped us a lot with his
tips and his tests, and Rémi Hainaud who lent his laptop for the final tests.

The default server address is ``localhost:5232/user/``, where calendars can be
added. Multiple calendars and owner-less calendars are not tested yet, but they
should work quite well. More documentation will be added during the next
days. It will then be time to release the Radicale 0.6 version, and work on the
WSGI support.