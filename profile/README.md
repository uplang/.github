# uplang

> **UP — Unified Properties. A data language that stays out of your way.**

Every configuration format makes a bargain. YAML trades clarity for convenience and hides sharp edges in its whitespace. JSON is unambiguous but unkind to human hands. TOML is comfortable until it nests. UP is an attempt at a better bargain: a line-oriented data language simple enough to read at a glance, structured enough never to surprise a parser, and layered so that the easy things stay easy.

The design is a ladder. At the bottom is a minimal, complete core — keys and values, blocks, lists — small enough to specify exactly and implement anywhere. Each rung above it adds one self-contained capability: quoting, types, multiline text, tables, documents, and optional layers for templating and schema. A lower rung never depends on a higher one, so a parser can stop wherever it likes and still be correct. Nothing is bolted on; everything is built up.

What makes it an ecosystem rather than a single tool is that the language is specified first and proven everywhere. The specification is the source of truth, and the same document parses identically across every supported language — so UP is a portable contract, not a dialect that drifts from one runtime to the next. Tooling, editor support, and libraries follow the spec, never the other way around.

A format you can read, and a grammar a machine can't misread.

## Explore

- **[uplang.org](https://uplang.org)** — the language home
- **[Specification](https://github.com/uplang/spec)** — the single normative definition
- **[Tools](https://github.com/uplang/tools)** — the `up` command-line toolkit
- **[All implementations](https://github.com/orgs/uplang/repositories)** — parsers and editor support across many languages

---

<p align="center"><em>Simpler than YAML. More structured than JSON. More layered than TOML.</em></p>
