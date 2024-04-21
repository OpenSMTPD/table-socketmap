TABLE\_SOCKETMAP(5) - File Formats Manual

# NAME

**table\_socketmap** - format description for smtpd socketmap tables

# DESCRIPTION

This manual page documents the file format of "socketmap" tables used by the
smtpd(8)
mail daemon.

The format described here applies to tables as defined in
smtpd.conf(5).

# SOCKETMAP TABLE

A "socketmap" table uses a simple protocol.
The client sends a single-line request and the server sends a single-line reply.

The table may be used for any kind of key-based lookup and replies are expected
to follow the formats described in
table(5).

# SEE ALSO

smtpd.conf(5),
table(5),
smtpctl(8),
smtpd(8)

# HISTORY

The first version of
**table\_socketmap**
was written in 2014.
It was converted to the stdio table protocol in 2024.

# AUTHORS

**table\_socketmap**
was initially written by
Gilles Chehade &lt;[gilles@poolp.org](mailto:gilles@poolp.org)&gt;.
The conversion to the stdio protocol was done by
Omar Polo &lt;[op@openbsd.org](mailto:op@openbsd.org)&gt;.

Nixpkgs - April 21, 2024
