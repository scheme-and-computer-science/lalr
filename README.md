# lalr
LALR(1) parser generator by Mark Johnson

I completed an LALR(1) parser generator a couple of weeks ago,
and I thought it might be useful to some of you.  (My CommonLisp
version seems to be well-used).   Anyway, here it is; it has
been tested on a couple of small grammars and on a larger one
(the purpose for which it was written) and seems to work fine.
Still, there may be errors in it.

It's offered more or less on an as-is basis; it's a tool that
I have found useful, and I thought that others might as well.

This message contains three files; lalr.ss, lalr-test.ss, and
a utility called assoc.ss (this is only needed for parse table
construction).  It needs the sort utility distributed in SLIB.

repackage by theschemer / Raven support team from https://github.com/ovenpasta/thunderchez
