# jest-30-aliases-update

# How to
1. Install `comby` https://comby.dev/
2. Run `comby -config ../jest-30-aliases-update/jest30.toml -f .test.ts,test.tsx,.test.js,.test.jsx,.spec.ts,spec.tsx,.spec.js,.spec.jsx -exclude-dir node_modules` to match and print the diff to the console
3. Run `comby -config ../jest-30-aliases-update/jest30.toml -f .test.ts,test.tsx,.test.js,.test.jsx,.spec.ts,spec.tsx,.spec.js,.spec.jsx -exclude-dir node_modules -in-place` to replace depricated jest matchers in-place
