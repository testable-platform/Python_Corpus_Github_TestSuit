# Python Corpus -- Tool Triggering (Tool Github Test data)

`main` carries only this overview -- it holds no project code. Every other
branch in this repository is one cell of `testable-platform/python-corpus`, split out to carry
only the `Tool Triggering (Tool Github Test data)/` folder (plus that branch's own build scaffolding).

This repository was produced by splitting `testable-platform/python-corpus` by task folder.
`testable-platform/python-corpus` itself was not modified by this split and still holds the
full combined corpus.

## Scope

This repo covers 24 branches, all carrying byte-identical content -- this folder does not vary by version, build tool, package manager or architecture. Branch names are borrowed from one version's combo set purely for naming consistency with the sibling repos.

## Branch naming

Branch names are unchanged from `testable-platform/python-corpus`:

```
PY_V{ver}_{BUNDLER}_{PKGMGR}_{ARCH}
```

## Finding a branch

Each branch's own `README.md` describes its exact cell (version, bundler,
package manager, architecture) and its tool roster, trimmed to the parts
relevant to `Tool Triggering (Tool Github Test data)/`. `dataset.json` on each branch is the
machine-readable answer key for that cell.

## History

Each branch's commit history is carried over unchanged from `testable-platform/python-corpus`,
with one additional commit on top that removes the folders not relevant to
this repo. Nothing was squashed or rewritten.
