# Structurizr-DSL-Testing

## Notes

```bash
brew install structurizr-cli
structurizr-cli export -f plantuml -w getting-started.dsl
cat structurizr-SystemContext.puml | docker run --rm -i think/plantuml -tpng > test.png
```

```bash
npm i -g c4builder

```