flag
=======

[![Build Status](https://drone.io/github.com/gonuts/flag/status.png)](https://drone.io/github.com/gonuts/flag/latest)

A fork of fork of the official "flag" package but with:

 * the flag.Value interface extended to provide a ``Get() interface{}`` method,
 * method ``(FlagSet *) Merge`` to merge two non-conficting flag sets
