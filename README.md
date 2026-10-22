# TUMBAO

**A reusable WordPress theme foundation by Abel Hechavarria**

TUMBAO is a maintainable starting point for client websites and independent projects. It provides a neutral, responsive WordPress theme that can be adapted through a child theme, without locking a site into a page builder or a client-specific visual identity.

## Project goals

- Keep WordPress core behavior and native templates available as a dependable fallback.
- Support the block editor by default, with Elementor Free and Elementor Pro available when a project calls for them.
- Keep client branding and custom layouts in child themes, so parent updates can be adopted without replacing project-specific work.
- Make optional interface effects configurable and progressively enhanced, with keyboard support, reduced-motion handling and usable fallbacks.
- Use a reproducible build and ship compiled assets with each approved release.

## Engineering highlights

- Classic WordPress parent theme with a separate, installable child-theme example.
- Child-overridable templates, design tokens and documented AHJ-prefixed extension hooks.
- Native theme settings scoped to the active theme; no ACF dependency.
- Optional modules for a floating call to action, preloader, pointer cursor, locally bundled Lenis smooth scrolling, bottom blur, back-to-top and a child-configurable logo marquee.
- Responsive design presets shared by the front end and block editor.
- Local JavaScript dependencies, license notices and a deterministic distribution packager.
- Native WordPress update integration designed to deliver approved parent-theme releases while leaving child themes intact.

## Status

TUMBAO is under active development. There is no stable production release available yet. Plugin and browser compatibility is being verified against specific versions; no blanket compatibility claim is made. Release packages and version-specific compatibility notes will be published here after the acceptance checks are complete.

## About

TUMBAO is an ongoing engineering project by **Abel Hechavarria**, a WordPress architect and full-stack developer based in Spain. It reflects a focus on maintainable theme architecture, practical extensibility and careful release engineering.

[View Abel's GitHub profile](https://github.com/abel-hechavarria)

## Distribution

This public repository is reserved for TUMBAO release information and approved distribution assets. Development tooling, internal project documentation and client data are kept out of this repository.

When a stable release is available, its GitHub Release will include the installable parent theme, a separate child-theme example, release notes and metadata for the WordPress updater. Published release assets will be versioned and immutable.
