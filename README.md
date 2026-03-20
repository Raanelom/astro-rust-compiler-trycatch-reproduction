# Astro reproduction

Steps to reproduce:

- Run `npm i`
- Run `npm run build`

Notice the error message:

```bash
11:31:44 [ERROR] [vite] ✗ Build failed in 29ms
src/pages/index.astro (27:8): Expression expected (Note that you need plugins to import files that are not JavaScript)
# etc
```

When removing the rust-compiler-lines, the error disappears and is building normally.
