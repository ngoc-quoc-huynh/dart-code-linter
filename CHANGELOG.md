# Changelog

## [3.0.0](https://github.com/ngoc-quoc-huynh/dart-code-linter/compare/v2.0.0...v3.0.0) (2026-08-26)


### ⚠ BREAKING CHANGES

* Minimum Dart SDK bumped to >=3.5.0.

### Features

* add autofix for newline-before-return with edge-case fixture coverage ([#227](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/227)) ([c196357](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/c1963570179863df5bfdc9ebe70aa3adfadf92f0))
* add new rule prefer-media-query-direct-access ([7d257c5](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/7d257c5181ec5a210df194556f3c990e750d4e2e))
* add new rule prefer-media-query-direct-access ([546f86b](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/546f86be573dff31dc6b5760c5a4a5e2b1da472f))
* Add new rules ([#260](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/260)) ([12642bc](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/12642bccdce342d7fe761e08fa2a4f664a6c5501))
* add rule prefer-named-record-fields ([50b2177](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/50b2177744243db13de3d8534b0d1b405a193920))
* add rule prefer-named-record-fields ([bd24366](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/bd24366647caf8d28ee5f59a0876b5a9a0fdcfed))
* analyzer 13.x support (release 4.1.0) ([#237](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/237)) ([2b9f6d7](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/2b9f6d73413cded2186b6c84bd16b29769ac961a))
* **avoid-duplicate-exports:** add auto-fix to delete the duplicate export directive ([#247](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/247)) ([63dba63](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/63dba638f14a2d71164b09c5239f5b34b12d921d))
* **avoid-unnecessary-type-casts:** add auto-fix to remove redundant cast ([#244](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/244)) ([2d631ac](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/2d631ac48a4f97d7f786b13453c4c09f4f6cad62))
* **new_rules_and_multiple_suggestions:** adapt barrel rule message ([264d52e](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/264d52e21eea007dbcd8e4c6d1ac7e269d68de70))
* **new_rules_and_multiple_suggestions:** add rules to rules factory ([cbed444](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/cbed444c1fe5aeec20c6ea71456b20c9de094a10))
* **new_rules_and_multiple_suggestions:** add some docs ([622d8bd](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/622d8bd08aa32af5990e44a99152825ff67c9d95))
* **new_rules_and_multiple_suggestions:** add use_design_system_item and only_barrel_import rules and adapt codebase to multiple suggestions ([b89a821](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/b89a8213dd0d6fb0e5d7f514e7731fbff4a4b188))
* **new_rules_and_multiple_suggestions:** bump version ([6e89367](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/6e89367ea72fdf7b598cfb45b705e2a0e56fa129))
* **new_rules_and_multiple_suggestions:** fix conflicts ([afacbe3](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/afacbe3dd7914a1998235de8af86af783630f2e5))
* **new_rules_and_multiple_suggestions:** fix conflicts ([90d4cd2](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/90d4cd2401501252594c67b16c93653221f8cde8))
* **new_rules_and_multiple_suggestions:** fix pr issues ([e4f7937](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/e4f79371a7f8718d96392aba83acb40bc422bd80))
* **new_rules_and_multiple_suggestions:** fix priority & bump version ([ce51d1a](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/ce51d1a4005fcd8f38592d270f81baea63b482c4))
* **new_rules_and_multiple_suggestions:** fix tests ([3bf41df](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/3bf41df878a568dae20c2130f0fde47aea5bb3fb))
* **new_rules_and_multiple_suggestions:** remove todo ([54c69c1](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/54c69c158052107b9a1bf387cc89a8398ff6f1b3))
* **no-blank-line-before-single-return:** add auto-fix and fix trailing-brace false positive ([#245](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/245)) ([432bb45](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/432bb4552b19f5fd394dd3898f0cb66c3c7b4936))
* **prefer-enums-by-name:** add guarded auto-fix to convert firstWhere to values.byName (4.1.6) ([#248](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/248)) ([d50c899](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/d50c8995e244bda72ccb7f991de2a2566e4b12b2))
* **prefer-match-file-name:** add config for excluding enums and typedefs ([#242](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/242)) ([ebcab9b](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/ebcab9b2b16bb190403ffacdfb1cab2efa967572))
* **prefer-moving-to-variable:** add ignored-invocations and ignored-targets options ([#218](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/218)) ([17f3cb5](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/17f3cb557eb3d12933f9146f63e73c0616910c81))
* **unused-code:** detect unused private class members behind a flag ([#176](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/176)) ([#259](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/259)) ([be95d7c](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/be95d7c324ae127e8bc37667c07a8f0a7e235e47))
* **unused-code:** detect unused public members behind a flag ([#176](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/176)) ([#268](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/268)) ([ee53c11](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/ee53c1137a824bcdda73258885e74307ef66687e))
* update analyzer dependency ([d66a8e1](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/d66a8e14e2373af6ab9a208888c4c1892c6e847f))
* Update pubspec.yaml ([e82df32](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/e82df32695dcb78086303a2932901fd7bb382f81))


### Bug Fixes

* address PR [#216](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/216) review feedback and resolve merge conflicts ([#221](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/221)) ([089aa87](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/089aa87741ed8795558eb1eef9a0d4cde1502643))
* **analyzer-plugin:** replace deprecated getChildAssumingFile with getFile ([#250](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/250)) ([#254](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/254)) ([814cc27](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/814cc2726040c17a4cd0e79e3c82f2cd04addbb2))
* **avoid-unused-parameters:** replace deprecated MethodDeclaration.isAbstract across analyzer matrix ([#253](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/253)) ([d2c1e9d](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/d2c1e9dfe1167018c4736122e676403b7c2f0ec3))
* change rule category ([c56f5dd](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/c56f5dd901a8e5c8dc50882bee91f7699238ae08))
* change rule category ([04b199b](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/04b199b60c1e576bf9be384966590a0824fdebfc))
* correct packageVersion constant and bump to 4.0.2 ([#230](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/230)) ([b7de35f](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/b7de35fbc691b8325abc9c2bcf1f9726c14baac7))
* delete dev_dependencies ([e21ed2f](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/e21ed2fecc647103c73d579eccdd669223ad713b))
* fix DCL version in analyzer_plugin ([ca37d4a](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/ca37d4a4d30e7e165ebe385b83b61bb31fee17c7))
* **lint-analyzer:** apply fixes back-to-front to avoid RangeError on multiple fixes ([#188](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/188)) ([#246](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/246)) ([db411dd](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/db411dd9d4ee7655d20793b017086cdd34387be5))
* **lint-analyzer:** resolve ExtensionTypeDeclaration.primaryConstructor deprecation via ast_compat helper ([#249](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/249)) ([#252](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/252)) ([1d7eddc](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/1d7eddccb29c21e6be07ccd09127f322ef1505c0))
* **metrics:** respect per-line `// ignore:` comments for metric violations ([#236](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/236)) ([d2fbbc1](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/d2fbbc11152c38658b88f3c78467208f666b46d4))
* migrate lint_analyzer ([87c8785](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/87c8785cfa2a543dffa905934f9b0a6570dfdfa1))
* **no-magic-number:** remove self-reported parameter_assignments analyzer warnings ([#243](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/243)) ([1633fa7](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/1633fa716ccbce38a83a05f848b99a1b9d1532d6))
* **prefer-dot-shorthands:** add support for unnamed constructors ([#266](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/266)) ([f684aec](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/f684aec04a2312f5776927ecda6731a41ab613b5))
* **prefer-moving-to-variable:** 4.0.3: detect duplicates in expression bodies + release process docs ([#219](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/219)) ([3e0f799](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/3e0f7992e7aa8df9f4a5570ba7050dc0ad7039bb))
* Recover example.dart with its empty lines for test to catch these issues ([43b7abc](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/43b7abca76f3a351991a2dff6df98fd681e7f52c))
* relax analyzer constraints for Flutter stable compatibility ([#228](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/228)) ([#229](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/229)) ([9771482](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/9771482d7e46a42f61ab6e32798d475b43096157))
* remove unsafe_html linter rule and update element references ([84a9efa](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/84a9efa26720f415ba593c58415df6751ef751f6))
* support configured plugin rules on Dart 3.13 ([#263](https://github.com/ngoc-quoc-huynh/dart-code-linter/issues/263)) ([6a20197](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/6a201970248f488f7304ffbdc88fc7cdf1676de6))
* update DCL version in analyzer_plugin ([51c759d](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/51c759dd156f3f3bb75a77aa5e582924d00f1e99))
* visitor and replacement ([617900b](https://github.com/ngoc-quoc-huynh/dart-code-linter/commit/617900b380890681a222717d2b8154392b362efe))

## 4.3.0
- Add opt-in detection of unused public members in type declarations to `check-unused-code`, enabled via the `--analyze-public-members` CLI flag or the `unused-code.analyze-public-members` analysis-options key and disabled by default. It is independent of `analyze-private-members`, so a large project can keep the cheaper private members check on while leaving this one off. Members that cannot be seen to be used through a reference are skipped instead of reported: members overriding or implementing an inherited member (found by walking `allSupertypes`, which also covers `toString`/`hashCode`/`noSuchMethod` and overrides written without `@override`), members carrying an annotation that says they are called from elsewhere (`@override`, `@mustBeOverridden`, `@visibleForOverriding`, `@redeclare`, `@protected`, `@visibleForTesting`, `@JS`, `@pragma('vm:entry-point')`), members exported to JavaScript with `@JSExport` (counted from the enclosing class too, but there only for its instance members, since a class level annotation never wraps statics; a class level `@pragma('vm:entry-point')` deliberately does not work this way at all, as it only permits allocation from native code and leaves members needing their own pragma), members whose name is invoked or read on a `dynamic` target anywhere in the program, `toJson` (called by `json.encode` rather than by reference), enum constants of an enum whose `values` is referenced, and unnamed constructors (their invocations carry no identifier to record; named constructors are analyzed).
- Record usages of members reached without an identifier: binary, index, unary and increment operator invocations (`a + b`, `a[b]`, `-a`, `a++`) and implicit `call` invocations previously marked only the enclosing extension as used, so a class's operators looked unused as soon as member analysis was on. The combiner of a compound assignment (`a += b`, which reaches `operator +`) was recorded nowhere at all, so an extension whose operator is used only that way was falsely reported even by the default top-level analysis. Operators and implicit `call` invocations on a `dynamic` target resolve to no element and are now recorded by the member name they reach, the same way dynamic method calls and property reads are.
- Fix the legacy analyzer plugin loader silently loading the wrong DCL version. The analysis server copies `tools/analyzer_plugin/pubspec.yaml` verbatim and resolves it against pub.dev, so its `dart_code_linter` range (frozen at `<4.2.0` since 4.1.7) resolved to 4.1.9 for anyone on 4.2.0 or later: the IDE ran 4.1.9's rules while the CLI ran the installed version, with no error, because a satisfying version always exists. Restored the exact version pin used up to 4.0.1, so each release's loader loads exactly that release.
- Fix a false negative in `check-unused-code` with `analyze-private-members` enabled: a used class member no longer marks a dead top-level declaration of the same name as used (a class calling its own `dispose` used to hide an unused top-level `dispose` function). The name based fallback that works around [dart-lang/sdk#49182](https://github.com/dart-lang/sdk/issues/49182) now requires both sides to agree on whether they are members, which cannot introduce false positives because member dispatch never resolves to a library level declaration.
- Document the `--analyze-private-members` flag and the `unused-code.analyze-private-members` analysis-options key in the README, including their precedence and known limitations.
- Extend the private members test coverage to mixin, enum and extension type members, static members, and member level `// ignore: unused-code` suppressions.
- Fix a false negative in `avoid-non-configurable-callbacks-in-init-state` where a named argument whose label reads `widget` or a known callback method name (e.g. `Options(widget: child)`) was mistaken for a real reference to the state's `widget` getter or to that method, suppressing the warning. Reproducible only on analyzer 10-12, where a named argument's label is a `Label`-wrapped identifier; analyzer 13+ uses a bare token for it instead.
- Fix a false negative in `avoid-non-exhaustive-switch-on-sealed-classes` where a parenthesized wildcard case (`case (_):`) was not recognized as defeating exhaustiveness the same way a bare `_` does.

## 4.2.2
- Fix Analysis Server plugin configuration loading across supported Dart runtimes.

## 4.2.1
- Fix `prefer-dot-shorthands` to also flag unnamed constructor calls (suggesting `.new(...)`) and enum/static member access used as a `switch` statement/expression case pattern matched against the switch's scrutinee type — both were previously left unflagged.

## 4.2.0
- Fix Analysis Server plugin rule configuration on Dart 3.13 by keeping plugin diagnostics scalar and loading full options from `dart_code_linter.rules`.
- Add the `avoid-non-configurable-callbacks-in-init-state` rule, which flags a `State.initState` that configures a widget-supplied object (e.g. `widget.controller.setNavigationDelegate(...)`) with a callback object whose named callbacks never reference the widget's own fields — a sign the behavior is fully hardcoded with no way for callers of the widget to customize it.
- Add the `avoid-non-exhaustive-switch-on-sealed-classes` rule, which flags a `default`/wildcard (`_`) case in a `switch` statement or expression over a sealed type. Relying on a fallback case defeats the compiler's exhaustiveness checking for sealed hierarchies, so newly added subtypes can silently fall through instead of forcing an explicit decision at each call site.
- Add the `prefer-dot-shorthands` rule (with auto-fix), which flags enum/static member access, static method calls, and named constructor calls that repeat a type name already inferable from context (a call argument's declared parameter type, or an explicitly typed variable's initializer) — Dart 3.10's dot-shorthand syntax lets these collapse to `.value` instead of `Type.value`. The rule only fires on files whose language version is 3.10 or later, since the shorthand syntax does not compile below that.

## 4.1.9
- Add opt-in detection of unused private members in type declarations (methods, fields, getters, setters and named constructors) to `check-unused-code`. Private members cannot be referenced from outside the declaring library, which rules out the reflection and cross-library false positives that make public members unreliable to analyze. Mirroring the SDK's `unused_element` semantics, a sole private constructor is never reported: it is the intentional prevent-instantiation/extension pattern (an entirely unused class is still reported by the class-level check). Enabled via the `--analyze-private-members` CLI flag or the `unused-code.analyze-private-members` analysis-options key; disabled by default.

## 4.1.8
- Raise the `analyzer` ceiling to `<15.0.0`, enabling analyzer 14.x support now that `dart_style` 3.1.11 added compatibility with it. Add 14.0.0 and 14.1.0 rows to the `scripts/test_analyzer_compat.py` matrix (`analyzer_plugin` 0.14.13/0.14.14, `analysis_server_plugin` 0.3.19/0.3.20).

## 4.1.7
- Replace the deprecated `Folder.getChildAssumingFile` with `ResourceProvider.getFile` in the analyzer plugin's UUID bootstrap, resolving the pana static-analysis deprecation warning on analyzer 13.x. The call stays compatible across the full `>=10.0.0 <14.0.0` range (`Folder.getFile` only exists in analyzer 13.3.0+).
- Replace the deprecated `MethodDeclaration.isAbstract` with a structural `ast_compat.isAbstractMethod()` helper in `avoid-unused-parameters`, keeping the call non-deprecated across the full `>=10.0.0 <14.0.0` range (`isComplete` only exists in analyzer 13.2+).

## 4.1.6
- Add an auto-fix to the `prefer-enums-by-name` rule that converts `Enum.values.firstWhere((e) => e.name == x)` to `Enum.values.byName(x)`. The fix is offered only when the call is safely convertible: a single-parameter `== name` arrow closure, no `orElse`, and a lookup that does not reference the closure parameter.
- Fix a deprecation warning for `ExtensionTypeDeclaration.primaryConstructor` (deprecated on analyzer 13.1+ in favor of `namePart`, which doesn't exist before 13.1) by reading the extension type's name structurally through a new `ast_compat` helper instead of the version-specific getter.

## 4.1.5
- Add an auto-fix to the `avoid-duplicate-exports` rule that deletes the duplicate export directive (the earlier export already covers the same URI, so the removal is behavior-preserving).
- Fix a `RangeError` crash in the `fix` command when a file had multiple auto-fixable issues; fixes are now applied from the end of the file towards the start so earlier edits no longer invalidate later offsets.

## 4.1.4
- Add an auto-fix to the `no-blank-line-before-single-return` rule that removes the blank line(s) before a single `return` statement in a block, preserving any comments.
- Fix a false positive in `no-blank-line-before-single-return` where a trailing comment on the block's opening brace (e.g. `{ // comment`) was reported even without a blank line before the return.

## 4.1.3
- Add an auto-fix to the `avoid-unnecessary-type-casts` rule that removes the redundant `as` cast (e.g. `value as String` becomes `value`).

## 4.1.2
- Remove two self-reported `parameter_assignments` analyzer warnings in the `no-magic-number` rule implementation by replacing `++count` with `count + 1` in the literal-counting callbacks (no behavioral change).

## 4.1.1
- Add config option `prefer-match-file-name.ignore-enums` and `prefer-match-file-name.ignore-typedefs` to suppress reports for enum and typedef declarations whose name doesn't match the file name.

## 4.1.0
- Add support for `analysis_server_plugin` (analyzer 13.x).
- Add support for `analyzer` 13.x via a cross-version AST shim ([lib/src/utils/ast_compat.dart](lib/src/utils/ast_compat.dart)) that recognises the reshaped named-argument, record-field, default-parameter and label nodes structurally.
- Widen `analyzer` constraint to `>=10.0.0 <14.0.0`.
- Extend `make test-analyzer-compat-full` to cover analyzer 10.x, 11.x, 12.x and 13.x; skip versions whose Dart SDK constraint is incompatible with the host SDK instead of failing.

## 4.0.5
- Add `ignored-invocations` and `ignored-targets` options to `prefer-moving-to-variable` rule to suppress reports for specific method/getter names or target receivers.
- Add autofix for `newline-before-return` with comment-aware, whitespace-preserving behavior and edge-case fixture coverage.

## 4.0.4
- Honor per-line `// ignore: <metric-id>` comments for function- and class-level metric violations (both leading and trailing forms). File-level metrics keep their `// ignore_for_file:` behavior.

## 4.0.3
- Fix `prefer-moving-to-variable` rule not detecting duplicate invocations in expression function bodies (`=> expr`).

## 4.0.2
- Update `packageVersion` constant to match pubspec version (was hardcoded as `3.2.0`).

## 4.0.1
- Relax `analyzer` constraint to >=10.0.0 <13.0.0 to support Flutter stable with `meta` 1.17.0.
- Relax `analyzer_plugin` constraint to >=0.14.0 <0.16.0.
- Add support for `analyzer` 12.x (replace removed `LibraryIdentifier` with version-agnostic approach).
- Remove `dependency_overrides` from main and example pubspecs.

## 4.0.0
- **BREAKING**: Update minimum Dart SDK to >=3.5.0 (compatible with Flutter 3.24+).
- Update `analyzer` to >=11.0.0 <12.0.0.
- Update `analyzer_plugin` to ^0.14.5.
- Fix element comparison for substituted elements in `always-remove-listener` rule.
- Add Packaged AI Assets for MCP integration (`extension/mcp/`).

## 3.2.1
- Update homepage in `pubspec.yaml`.

## 3.2.0
- Update `analyzer` constraint to ^8.2.0. Only works with `dart >= 3.9.0`.
- Add rule `use-design-system-items`.
- Add rule `only-barrel-import`.
- Allow to specify more than one suggestion for each rule.

## 3.2.0-alpha.2
- Update `analyzer` constraint to ^8.2.0

## 3.2.0-alpha.1
- Add rule `use-design-system-items`.
- Add rule `only-barrel-import`.
- Allow to specify more than one suggestion for each rule.
- Bump `analyzer` to ^8.0.0

## 3.1.1
- Changed `prefer-media-query-direct-access` to `FlutterRule`.

## 3.1.0
- Add rule `prefer-media-query-direct-access`.
- Add rule `prefer-named-record-fields`.

## 3.1.0-beta.3
- Add rule `prefer-media-query-direct-access`.

## 3.1.0-beta.2
- Fixed DCL version in analyzer_plugin.

## 3.1.0-beta.1
- Add rule `prefer-named-record-fields`.

## 3.0.0-beta.1
- [Breaking] Update dart sdk constraints to `>=3.4.0 <4.0.0`.
- Update `analyzer` to version ^7.4.4
## 2.0.0
- Update `analyzer` to version ^6.0.0
## 1.3.0
- Added `fatal-warnings-threshold` `fatal-performance-threshold` and `fatal-style-threshold` to set the failure threshold for analyze command
## 1.2.1
- Fixed generating report file when find issues in the report
## 1.2.0
- Added fix command
- Added prefer single quotes rule
- Added prefer first or null rule
- Added no blank line before single return rule
- Fixed rule avoid dynamic to extensions definition
## 1.1.5
- Removed deprecated fields in analysis options and collection method
- Fixed changelog URL for update available warning
## 1.1.4
- Fixed some test
- Reverted `analyzer` ^6.0.0 to ^5.14.0
## 1.1.3
- Fixed some test
## 1.1.2
- Append new presset `analysis_options.1.0.0.yaml`
## 1.1.1
- Rename common rules to dart rules
## 1.1.0
- Added new presets
- Removed Angular framework rules
- Added example

## 1.0.2
- Fix: report in IDE'S is adjusted
## 1.0.1
- Automated publishing of packages to pub.dev

## 1.0.0
- Fork: [Dart code metrics 5.7.3](https://github.com/dart-code-checker/dart-code-metrics)
