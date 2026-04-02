# Building and running C through the RISC OS build service

This repository shows how you can build and run a C program on the RISC OS build
service, and get the results back.

The supplied program is a very simple command line tool which just
prints a message to the screen. This can easily be extended to any
command line tool you wish to build.

A description of how to handle running programs on the build service
can be found [here](https://build.riscos.online/ci-build.html#).

Other examples can be found in the GitHub topic '[riscos-ci](https://github.com/topics/riscos-ci)'.

Templates for use with GitLab and GitHub can be found in the [riscos-ci-templates](https://github.com/gerph/riscos-ci-templates) repository.


## Using the riscos-build-online tool

The `riscos-build-online` tool is intended to make the process easier and
provide some degree of interactivity from the output.


## Automatic releases

The `.github` configuration is also set up to automatically create releases
when a tag with the name `v*` is pushed. This release will be a draft and
you must update the text to make it public.
