# jest-30-aliases-update

1. Install `comby` https://comby.dev/
2. Run `comby -config ../refactor-depricated-matchers/jest30.toml -f .ts,.tsx -exclude-dir node_modules` to match and print the diff to the console
3. Run `comby -config ../refactor-depricated-matchers/jest30.toml -f .ts,.tsx -exclude-dir node_modules -in-place` to replace depricated jest matchers in-place
