## v0.2.3 (2017-11-22)

* Update dtoa.c to fix #18 (`string_of_float` incorrectly returns `-nan`)
  (@mato, #28).
* Support OCaml 4.06.0 (@mato, #27)
* Add additional stubs needed by newer gmp (@hannesm, #26)
* aarch64 support (@mato, #25)

## v0.2.2 (2017-07-14)

* Support OCaml 4.05.0 (@mato, #23)
* Fixes for OCaml 4.04.1+ (@mato, #22)
* Silence STUB: warnings by default (@mato, #19)
* Add support for solo5-kernel-muen, not exposed in Solo5 or MirageOS yet
  (@Kensan, #18)

## v0.2.1 (2017-01-18)

* Declare `OCAML_OS_TYPE` as `freestanding` (@hannesm, #14)

## v0.2.0 (2017-01-18)

* FreeBSD support (@mato, @hannesm)
* OpenLibm supplied as a git subtree (@mato, #11)
* Support OCaml 4.04.0 (@mato, #8)

## v0.1.1 (2016-07-21)

* Initial release for publishing to opam.ocaml.org.
