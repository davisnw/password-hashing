password-hashing
================

Fork of https://github.com/defuse/password-hashing.

The intent of this fork is to:

 * enable configurability of pbkdf2 iteration count and salt size without requiring recompilation
 * Address and document issue that gives an attacker an additional advantage over defender (in addition to typical hardware advantages the attacker already has), as described at http://security.stackexchange.com/a/51430/28362 and demonstrated at https://gist.github.com/davisnw/991912f1a6fe2b63a73b
