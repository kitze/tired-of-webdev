Some reasons why I'm tired of webdev. If you think something is fixable, please open a PR and tell me how. Thank you.

# Apps
## WebStorm
### Imports
Fuck auto imports in WebStorm, seriously. I want my editor to import things on the fly. I have the option "import on the fly" checked but it doesn't work.
- Sometimes it imports things twice (super frustrating)
- Auto-import {Box} from "ink" even though in 13948138413 files I import it from @mantine-ui/core
- Not suggesting auto-imports for components like <Text/>
- If I'm using <Vertical> from the same library in 19384813 files, just import it from the same frickin library and don't ask me

# Libraries/Tools
## Prisma
- After running a db:migrate
  - I have to restart the dev server and studio
  - I have to go to the generated types so my editor (WebStorm) can pick up the type changes

