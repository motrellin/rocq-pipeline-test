<!---
This file was generated from `meta.yml`, please do not edit manually.
Follow the instructions on https://github.com/coq-community/templates to regenerate.
--->
# Pipeline Testing

[![Docker CI][docker-action-shield]][docker-action-link]
[![coqdoc][coqdoc-shield]][coqdoc-link]

[docker-action-shield]: https://github.com/motrellin/piptest/actions/workflows/docker-action.yml/badge.svg?branch=main
[docker-action-link]: https://github.com/motrellin/piptest/actions/workflows/docker-action.yml


[coqdoc-shield]: https://img.shields.io/badge/docs-coqdoc-blue.svg
[coqdoc-link]: https://motrellin.github.io/piptest


Playing


## Meta

- Author(s):
  - Max Ole Elliger (initial)
- Compatible Rocq/Coq versions: Developed for 9.0.0
- Compatible OCaml versions: 5.0.0
- Additional dependencies: none
- Rocq/Coq namespace: `PipTest`
- Related publication(s): none

## Building and installation instructions

The easiest way to install the latest released version of Pipeline Testing
is via [OPAM](https://opam.ocaml.org/doc/Install.html):

```shell
opam repo add coq-released https://coq.inria.fr/opam/released
opam install coq-piptest
```

To instead build and install manually, do:

``` shell
git clone --recurse-submodules https://github.com/motrellin/piptest.git
cd piptest
make all  # or make -j <number-of-cores-on-your-machine> all
make install
```


foobar
