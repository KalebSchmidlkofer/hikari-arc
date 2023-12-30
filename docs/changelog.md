---
title: Changelogs
description: All changelogs for hikari-arc
hide:
  - navigation
---

# Changelogs

Here you can find all the changelogs for `hikari-arc`.

## v0.2.0

- **Breaking:** Rename `Context.edit_response()` to `Context.edit_initial_response()`. This is to make the purpose of the function clearer.
- **Breaking:** Remove `arc.Injected[T]` typehint alias. Use `arc.inject()` instead. This is to avoid confusion between the two.
- Add support for passing mappings to `choices=` when specifying option params.
- Improve handling missing responses via REST by adding `NoResponseIssuedError`.
- Fix `@plugin.inject_dependencies` failing when located outside of the main module.

## v0.1.3

- Fix `Context.respond_with_builder` issuing the response twice in REST.
- Do not export `abc`s to top-level.

## v0.1.2

- Add `Context.respond_with_modal`
- Add `BoolOption` and `BoolParams`
- Improve `Context.respond_with_builder` typing.

## v0.1.1

- Initial release