<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="aster-flower-illustrated-dark.svg">
    <img src="aster-flower-illustrated.svg" width="96" height="96" alt="">
  </picture>
</p>

<h1 align="center">Aster Docs</h1>

<p align="center">Beautiful, accessible documentation, straight from your source code.</p>

We build open-source tools that turn the comments in your code into documentation people enjoy
reading. Your documentation keeps living where it belongs, in your source comments, and comes out
as a fast, accessible static site.

## Projects

### [Aster](https://github.com/AsterDocs/Aster)

The site generator. Aster turns your project's documentation into a static site: declarations and
comments come through exactly as written, every overload and enum value gets its own link, search
runs locally, and every page reads well without JavaScript, in eight light and dark themes.

**Aster Garden** comes with it: a local workspace for choosing a theme, checking contrast, adding
your logo, writing guide chapters, seeing documentation coverage, and building, previewing and
publishing your site, all on your own computer.

### [Calyx](https://github.com/AsterDocs/Calyx)

The documentation engine. Calyx reads your sources directly, with no Doxygen to install, and turns
code and comments into one documentation standard: a versioned JSON format with stable IDs that
Aster, or any other tool, can build on. Doxygen-style and Markdown comments work as written, and an
existing Doxyfile's settings can be imported. C++ is supported today, with more languages on the
way. Languages and comment styles are added as small plugins written in Luau, so anyone can
contribute one.

## How they fit together

```
your code and comments  →  Calyx  →  documentation JSON  →  Aster  →  your docs site
```

Calyx extracts; Aster publishes. Because the JSON in between is an open, versioned standard, other
tools can read it too.

## Status

Both projects are in early development, and the first release is on its way.

- Website: [aster.florist](https://aster.florist) (launching soon)
- npm: [`aster-docs`](https://www.npmjs.com/package/aster-docs) (coming soon)
- License: Apache-2.0, for both projects
