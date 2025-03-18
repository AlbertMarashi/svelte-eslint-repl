
```
bun i
bun run lint
```
```
(base) albert@Alberts-MacBook-Pro svelte-eslint-repl % bun run lint
$ eslint .

/Users/albert/repos/svelte-eslint-repl/src/routes/Baz.svelte
  3:5  error  'x' in 'position' is an unused property        svelte/no-unused-props
  3:5  error  'y' in 'position' is an unused property        svelte/no-unused-props
  4:5  error  'position' is assigned a value but never used  @typescript-eslint/no-unused-vars

/Users/albert/repos/svelte-eslint-repl/src/routes/Foo.svelte
  4:5  error  'x' in 'position' is an unused property  svelte/no-unused-props
  4:5  error  'y' in 'position' is an unused property  svelte/no-unused-props

✖ 5 problems (5 errors, 0 warnings)

error: script "lint" exited with code 1
(base) albert@Alberts-MacBook-Pro svelte-eslint-repl % 
```