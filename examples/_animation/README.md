The samples in this folder used to be under `src/_includes/code`. Despite that,
the sources were not being included anywhere. It is likely that the sources
appear in some pages none-the-less. What needs to be done is the following:

- Each app/sample needs to be fully reviewed (and potentially simplified).
- If the sources are in fact being used in site pages, then they need to be
  integrated as proper code excerpts. See [Code excerpts][] for details.
- Each app/sample should be tested, at least with a smoke test.

As these changes are completed for a given app/sample folder, then move the
folder into `examples/animation`. One `examples/_animation` is empty, it can be
deleted.

[Code excerpts]: https://github.com/dart-lang/site-shared/blob/main/doc/code-excerpts.md
