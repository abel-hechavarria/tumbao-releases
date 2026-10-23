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

[TUMBAO 0.1.0 is available as a stable release](https://github.com/abel-hechavarria/tumbao-releases/releases/tag/v0.1.0). Its normal WordPress update channel has been verified with the native installer: the parent updates while child files, settings and the administrator's automatic-update preference are preserved.

### Installation

1. Download [the parent theme](https://github.com/abel-hechavarria/tumbao-releases/releases/download/v0.1.0/tumbao-0.1.0.zip) and install it through **Appearance → Themes → Add New → Upload Theme**.
2. For a new project, install [the separate child-theme example](https://github.com/abel-hechavarria/tumbao-releases/releases/download/v0.1.0/tumbao-child-example-0.1.0.zip) and activate the child. Keep project branding, templates and custom code there.
3. Configure optional effects under **Appearance → TUMBAO** and evaluate the result in a test environment before using it on a client site.

The example child is an initial setup package; it must not replace an existing project child theme.

### Compatibility and accessibility scope

The theme baseline is **WordPress 6.8+ and PHP 8.2+**. Optional plugins have their own version requirements. Versioned checks include native WordPress, Elementor Free/Pro, WooCommerce and representative field, SEO and cache integrations.

Browser checks cover Chrome 155/156, Edge 155/156, Firefox 157/158 and Chrome on Android. Chrome 156 uses Google's Chrome for Testing binary; Firefox checks use stock Mozilla releases. Safari on macOS and iOS has not been verified.

Accessibility checks include keyboard navigation, accessible names, reduced motion, forced colors, rendered contrast and browser zoom up to 400%. These are scoped engineering checks, not a conformance certificate or a guarantee for every child-theme design. Some optional plugin versions emit PHP 8.5 deprecation notices independently of TUMBAO; assess plugin compatibility for each project.

## About

TUMBAO is an ongoing engineering project by **Abel Hechavarria**, a WordPress architect and full-stack developer based in Spain. It reflects a focus on maintainable theme architecture, practical extensibility and careful release engineering.

[View Abel's GitHub profile](https://github.com/abel-hechavarria)

## Distribution

This public repository is reserved for TUMBAO release information and approved distribution assets. Development tooling, internal project documentation and client data are kept out of this repository.

Each stable GitHub Release includes the installable parent theme, a separate child-theme example, release notes and metadata for the WordPress updater. Published release assets are versioned and immutable. WordPress checks the public stable channel without requiring a GitHub token; automatic updates remain the administrator's choice.

Version 0.1.0 was promoted from its verified candidate without changing any release asset. The release page reflects current status; the downloadable notes retain their original candidate-publication snapshot. Download the named theme ZIPs, rather than GitHub's generated source archives.
