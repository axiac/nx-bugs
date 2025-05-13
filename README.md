# Nx bugs #30997 & #30999

This repository contains a stub project that uses Nx and can be used to reproduce Nx bugs
[#30997](https://github.com/nrwl/nx/issues/30997) and [#30999](https://github.com/nrwl/nx/issues/30999).

## How to reproduce

The Nx bug [#30997](https://github.com/nrwl/nx/issues/30997) is demonstrated on branch [`bug-30997`](https://github.com/axiac/nx-bugs/tree/bug-30997).<br>
The Nx bug [#30999](https://github.com/nrwl/nx/issues/30999) is displayed on branch [`bug-30999`](https://github.com/axiac/nx-bugs/tree/bug-30999).

Checkout the corresponding branch and run `NX_DAEMON=false node_modules/.bin/nx show projects` inside the `sample-project` sub-directory.

Checkout the branch `master` and run the same command to get the expected results.

