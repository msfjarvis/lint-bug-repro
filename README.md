Reproducer for a Lint bug in AGP 8.3.0-alpha05 that flags instance variables of types that have a `@RequiresApi` annotation with the `NewApi` Lint but does not allow to silence the it by adding `@RequiresApi` on the field.