# Backlog (ideas parked so they don't hijack a session)

## A Design foundation (sample data, no Supabase)
- [ ] Decide how Inter gets into the app: bundled font files or the `google_fonts` package
- [ ] Scaffold the Flutter app for Android, iOS, macOS, Windows and web, with the packages from the spec
- [ ] Design tokens: emerald palette, type scale with tabular numerals, 4 px spacing, radii, animation timings
- [ ] Decide what to do about `textMuted` (4.41:1 on surfacePrimary, 3.74:1 on surfaceElevated) and `accentMuted`, both below 4.5:1 for small text
- [ ] Decide the icon source for Lucide-style outline icons (a Lucide package or Flutter's built-in outlined icons)
- [ ] Breakpoints: the widths where mobile becomes tablet and tablet becomes desktop
- [ ] Reusable components (AshuCard, AshuButton, AshuProgressBar and the rest of the list) on the tokens

## B Application shell
- [ ] GoRouter, desktop sidebar (240 px), optional right panel (280 px), tablet drawer, mobile bottom bar with a More screen
- [ ] Decide which destinations go on the mobile bottom bar and which go under More
- [ ] Page transitions; settings from the sidebar or profile menu

## C Core experience
- [ ] Decide how the vision-to-action chain fits together (its own ADR), and the sample data for it
- [ ] Mock repositories and Riverpod providers; decide where the business logic lives
- [ ] Dashboard, Vision Board and vision detail, Life Systems, goals and milestones
- [ ] Decide where the Vision Board's sample photography comes from (source and licence)

## D Hobbies
- [ ] Hobby overview, the five hobby cards and a page for each hobby with sample data

## E Supporting modules
- [ ] Fitness, academics, career, finance, personal growth, calendar, experience library, insights, weekly review

## Later
- [ ] Backend: Supabase auth, schema, migrations, row-level security, real repositories
- [ ] Integration: real data everywhere, analytics, performance, polish
- [ ] Image upload for vision cards
- [ ] Checks on every pull request (`flutter analyze`, `flutter test`) once there's a GitHub remote
- [ ] Customisable dashboard (a future version)
- [ ] AI-based planning, after the deterministic planner works
