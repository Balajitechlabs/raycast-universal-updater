## Fixed

- Remove duplicate `Preferences` interface definitions from multiple files; use auto-generated Raycast type from `raycast-env.d.ts`
- Wire "Backup Current Versions" action to actually call the backup implementation instead of a no-op stub
- Fix inverted message in major version filter note — now correctly indicates state of the setting
- Remove unused `@raycast/utils` dependency from package.json
- Convert dynamic import of `isEcosystemAvailable` to static import to simplify code and eliminate false circular dependency concern

## Added

- Add Universal Updater Raycast extension (initial release)

## Notes

- Includes backup/export/import and macOS notifications.
