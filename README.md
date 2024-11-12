# farm-svelte-5-issue

Svelte 5 not working with Farm.

## Steps to reproduce

1. `bun create farm@latest`
1. Select `svelte` template.
1. `cd farm-project`
1. `bun install` - this installs svelte 4
1. `bun run dev` - works
1. `bun install svelte@latest @sveltejs/vite-plugin-svelte@latest svelte-check@latest` - this installs svelte 5
1. `bun run dev` - this fails.
1. `bun run build && bun run preview` - this also fails.
