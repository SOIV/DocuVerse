# DocuVerse Editor Library — Introduction Draft

[한국어](readme_v2-ko.md) | [English](readme_v2.md)

The project is in planning and design. Packages, APIs and supported platforms will be confirmed through implementation and validation. This is not documentation for an already published package or runnable installation.

## Purpose

Provide shared document models, editing commands, conversion and extension contracts as an independent library. The official tablet app and self-hosted document framework use this foundation; developers can also embed only the editor.

## Capabilities to develop

- Basic document and block schemas, selection, commands, undo and redo.
- Optional Markdown, permitted HTML and NamuWiki-style parsing and conversion.
- Basic tables with later advanced table, formula and syntax extensions.
- Platform adapters for input, rendering, clipboard, touch and pen handling.
- Read-only rendering and shared document processing without requiring editing UI.
- Versioned documents, extension-data preservation and unsupported-block fallbacks.

Syntax and conversions will be verified within explicit support limits. Handwriting and advanced blocks cannot be assumed to round-trip without loss through every text format.

## Host and server boundaries

Hosts handle storage, accounts, workspace search, document trees, sharing and collaboration servers. Collaboration-data integration is optional. Basic editing must not require a database, authentication service or real-time server. A specific UI framework or external service is not a mandatory core dependency.

ProseMirror-based engines, UI frameworks and build tools remain candidates for validation. Initial checks cover iPadOS and Android tablet editing and web rendering, then guide adapter selection. Support for all platforms or versions is not assumed.

## Plugin compatibility

Shared logic and platform-specific UI and execution are separate. Compatibility claims require actual platform and version testing, recorded feature explanations and usage results, and review before marketplace publication. See the [shared policy](../../Framework/1.%20framework-runtime-and-plugin-policy.md).

## License status

MIT distribution is the editor's existing planning goal. The repository's current [LICENSE](../../../LICENSE) is GPL-3.0; a separate MIT package has not been established by these documents. Package-specific licensing must be confirmed before distribution. See the [documentation guide](../../README.md).

## Documentation and participation

- [Editor documentation](../../Editor_Library/README.md)
- [Editor roadmap](../../Editor_Library/editor-library_roadmap.md)
- [Self-hosted framework](../../Framework/README.md)
- [Project introduction and contact](../../../README.md)
