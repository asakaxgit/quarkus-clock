# TODO

Project backlog for **quarkus-clock** ([Quarkiverse checklist](https://github.com/quarkiverse/quarkiverse/wiki/checklistfornewprojects)).

## Documentation (Antora)

- [x] Replace placeholder Antora docs (`index`, `usage`, `testing`, `configuration`)
- [x] Examples under `docs/modules/ROOT/examples/`
- [x] Fill `quarkus-extension.yaml` (`description`, keywords, categories, `preview`)
- [x] Project README
- [ ] Register in [quarkiverse-docs `antora-playbook.yml`](https://github.com/quarkiverse/quarkiverse-docs/blob/main/antora-playbook.yml)
- [ ] Uncomment `guide` in `quarkus-extension.yaml` after docs.quarkiverse.io is live

Local preview: `mvn -pl docs package` → `docs/target/generated-docs/index.html`

## Release and catalog

- [ ] First Maven Central release (PR updating `.github/project.yml` `current-version` to `0.1.0` **from an origin branch**, not a fork)
- [ ] Extension catalog ([quarkus-extension-catalog](https://github.com/quarkusio/quarkus-extension-catalog)) — usually auto after first release; else:

```yaml
---
group-id: "io.quarkiverse.clock"
artifact-id: "quarkus-clock"
versions:
- "0.1.0"
exclude-versions: []
```

- [ ] Optional: [Quarkus Ecosystem CI](https://github.com/quarkusio/quarkus-ecosystem-ci)

## References

- [Documenting your extension](https://github.com/quarkiverse/quarkiverse/wiki/DocumentingYourExtension)
- [Release](https://github.com/quarkiverse/quarkiverse/wiki/Release)
- [Checklist for new projects](https://github.com/quarkiverse/quarkiverse/wiki/checklistfornewprojects)
