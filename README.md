# Quarkus Clock

[![Version](https://img.shields.io/maven-central/v/io.quarkiverse.quarkus-clock/quarkus-clock?logo=apache-maven&style=flat-square)](https://central.sonatype.com/artifact/io.quarkiverse.quarkus-clock/quarkus-clock-parent)
[![Build](https://github.com/quarkiverse/quarkus-clock/actions/workflows/build.yml/badge.svg)](https://github.com/quarkiverse/quarkus-clock/actions/workflows/build.yml)

Injectable `java.time.Clock` for Quarkus applications: system clock by default, fixed instant for deterministic tests, or an adjustable clock you can advance in tests and development.

## Installation

Maven:

```xml
<dependency>
    <groupId>io.quarkiverse.quarkus-clock</groupId>
    <artifactId>quarkus-clock</artifactId>
    <version>${quarkus-clock.version}</version>
</dependency>
```

Gradle:

```groovy
implementation("io.quarkiverse.quarkus-clock:quarkus-clock:${quarkusClockVersion}")
```

## Documentation

User guide (Antora): see the `docs/` directory.
Once registered in [quarkiverse-docs](https://github.com/quarkiverse/quarkiverse-docs), the guide will be published at <https://docs.quarkiverse.io/quarkus-clock/dev/>.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) (when present) and the [Quarkiverse wiki](https://github.com/quarkiverse/quarkiverse/wiki).

## License

Licensed under the [Apache License 2.0](LICENSE).
