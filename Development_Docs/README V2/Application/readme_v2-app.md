# DocuVerse Official Tablet App — Introduction Draft

[한국어](readme_v2-app-ko.md) | [English](readme_v2-app.md)

The project is in planning and design. These are intended capabilities, not released or verified features. The [app roadmap](../../Application/05b_roadmap_and_future.md) defines the initial scope.

## Product direction

DocuVerse aims to combine structured text and blocks with handwriting and spatial notes. iPadOS and Android tablets are the primary app targets. Windows and macOS apps are undecided. Native or WebView implementation choices will follow input and performance validation.

## Initial experience to validate

- Create, save and reopen local documents without an account or cloud service.
- Combine text, images and attachments with basic handwriting, color blocks, sticky notes and shapes.
- Use basic search, tags, backlinks, settings and themes with tablet input and layouts.
- Import and export with explicit preservation and conversion limits; retain unsupported block data.

Offline support covers locally available functionality. Cloud storage, sharing, collaboration, external APIs and multiple AI providers are optional later features. Advanced developer tools and additional platforms require separate evaluation.

## Editor and framework relationship

The app uses the independent editor library and shared document model. The [self-hosted framework](../../Framework/README.md) is a separate tool for document and wiki sites. Using the app does not require hosting a site. Turning off site dynamic features does not disable local app editing.

Some plugin data and logic can be reused across app and web hosts. Platform, version, feature and execution-mode tags require actual testing, recorded evidence and review before marketplace publication. See the [shared policy](../../Framework/1.%20framework-runtime-and-plugin-policy.md).

## Installation and support status

This repository currently contains design documentation. App installers and runnable npm startup commands are not yet provided. Installation instructions, translations and supported versions will reflect implemented and verified releases.

## Pricing and license

The [subscription draft](../../Application/04_business_model.md) describes possible official cloud and operated services; prices are unconfirmed. Self-hosted licensing and commercial policies will be decided separately.

The repository's current [LICENSE](../../../LICENSE) is GPL-3.0. See the [documentation guide](../../README.md) for product-specific status.

## Documentation and participation

- [App documentation](../../Application/README.md)
- [Project documentation guide](../../README.md)
- [Project introduction and contact](../../../README.md)
