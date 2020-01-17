# Simple Todo App

Based on [Svelte v3 - Basics - Todo App](https://www.youtube.com/watch?v=0uTX5GfmhTo), [github repo](https://github.com/drehimself/svelte-todo-example)

_Framework_: [Svelte 3](svelte.dev/)

_CSS Framework_: [Bulma](http://bulma.io)

_Package manager_: [PNPM](https://pnpm.js.org)
(hardcoded in `rollup.config.js`, so dont forget change to you packet manager like npm, otherwise `run dev` will not work properly)

```javascript
require("child_process").spawn("pnpm", ["run", "start", "--", "--dev"], {
  stdio: ["ignore", "inherit", "inherit"],
  shell: true
});
```
