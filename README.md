# https://tea.xyz/what-is-this-file
---
version: 1.0.0
codeOwners:
  - '0x839949CAE78eb6CCA7ed7a75F8f250E264F32Cf3'
quorum: 1
# tea

[![build](https://travis-ci.org/alefnula/tea.png)](https://travis-ci.org/alefnula/tea)
[![codecov](https://codecov.io/gh/alefnula/tea/branch/master/graph/badge.svg)](https://codecov.io/gh/alefnula/tea)
[![docs](https://readthedocs.org/projects/tea-lib/badge/)](https://tea-lib.readthedocs.org)


`tea` is a set of libraries developed for common tasks like executing and
manipulating processes, sending emails, file system manipulation, and a great
number of utility functions that I caught myself writing over and over again.

Also parts of the `tea` library can be viewed as a sand-box where I start
a module, which eventually, if it grows and become large enough to become a
library itself, gets extracted as a separate project.

Modules like `dsa` (data structures and algorithms), `logger`, `msg`,
`process`, `shell`, `utils`... will always remain a part of `tea`.
