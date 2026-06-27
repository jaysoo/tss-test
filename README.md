# tss-test

## Nx + TanStack Start bootstrap

Run:

```bash
npx create-nx-workspace@latest my-workspace --template nrwl/tanstack-start-template
```

Then connect this repository in Netlify. The included `netlify.toml` is preconfigured to build from the generated `my-workspace` folder.

If you choose a different app name, update the `netlify.toml` `build.command` and `build.publish` paths to match that app.
