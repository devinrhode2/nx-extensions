---
sidebarDepth: 3
---

## @nxext/vitest:vitest

vitest executor

Options can be configured in the 'project.json' when defining the executor, or when invoking it. Read more about how to configure targets and executors here: https://nx.dev/configuration/projectjson#targets.

### Options

#### command (_**required**_)

Type: `string`

Sveltekit command to run

#### passWithNoTests

Default: `false`

Type: `boolean`

Pass the build if no tests are found

#### testNamePattern

Type: `string`

Pattern to match test names