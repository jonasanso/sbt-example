An example SBT project which uses macros (Scala 2.10, SBT 0.13)

To verify that everything works fine, do `sbt run`.

Note that currently SBT doesn't support recompilation of macro clients if the dependencies of the macro implementation have changed - macro clients are only recompiled when the macro definition itself is:  https://github.com/sbt/sbt/issues/399.

Forked from https://github.com/scalamacros/sbt-example

- Added Intellij IDEA integration use sbt gen-idea to create a project