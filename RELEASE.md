# Release Instructions

1. Update the version number in [package.json](./package.json) and commit it
2. `rm -rf node_modules bun.lockb`
3. `bun install`
4. `bun run build`
5. `npm publish`
6. Create a new GitHub release for this version with the release notes
