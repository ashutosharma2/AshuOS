# Next session: one task

**Phase A: scaffold the Flutter app and build the Emerald design foundation**

Everything else is drawn with these tokens and components, so they come first.

1. Decide how Inter gets into the app (bundled font files or the `google_fonts` package).
2. Scaffold the app for Android, iOS, macOS, Windows and web, and add the packages from the spec.
3. Design tokens: the emerald palette, the type scale with tabular numerals for numbers, 4 px spacing, radii, animation timings and breakpoints. Decide what to do about `textMuted` and `accentMuted`, which fall below 4.5:1 contrast on cards.
4. The reusable components and a dark theme built from the tokens.

Done when: the app runs on macOS and the web with the emerald theme, a screen shows the tokens and components, and `flutter analyze` and `flutter test` are clean.

## End of every phase
- Update README.md (status table, key decisions) and docs/architecture.md (all diagrams; solid = built, dashed = planned).
- Update docs/project-story.md: new actions, results and every real error hit (problem, cause, fix, lesson).
- Run `flutter analyze` and `flutter test`; both must be clean. Run the app and look at it on desktop and mobile sizes.
- Commit, add one line to LOG.md, set the next single task here.
