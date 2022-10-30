# ocaml_template

template repository for ocaml

**after importing**

- [ ] rename `ocaml_template` in files
- [ ] rename `lib/ocaml_template.ml` and `test/ocaml_template.ml`
- [ ] remove `ocaml_template.opam`
- [ ] build

## how to set up

```bash
opam switch create .
eval $(opam env)
opam install . --deps-only
eval $(opam env)
```

## how to run

```bash
dune exec ocaml_template
```

## how to build

```bash
dune build
```

watch mode

```bash
dune build -w
```

## how to test

```bash
dune test
```

watch mode

```bash
dune test -w
```

## how to format

```bash
dune fmt --auto-promote
```

## how to build documentation

```bash
dune build @doc
```

open it

```bash
open _build/default/_doc/_html/index.html
```
