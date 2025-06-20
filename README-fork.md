cd to base of repo
ppnpm install
pnpm run build

cd addons\dexie-export-import
pnpm run build
npm publish --access=public
