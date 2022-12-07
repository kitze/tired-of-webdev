Some reasons why I'm tired of webdev. If you think something is fixable, please open a PR and tell me how. Thank you.

## WebStorm
### Imports
Fuck auto imports in WebStorm, seriously. I want my editor to import things on the fly. I have the option "import on the fly" checked but it doesn't work.
- Sometimes it imports things twice (super frustrating)
- Auto-import {Box} from "ink" even though in 13948138413 files I import it from @mantine-ui/core
- Not suggesting auto-imports for components like <Text/>
- If I'm using <Vertical> from the same library in 19384813 files, just import it from the same frickin library and don't ask me

## Prisma
- After running a db:migrate
  - I have to restart the dev server and studio
  - I have to go to the generated types so my editor (WebStorm) can pick up the type changes

## Blitz
In retrospect, going with blitz was not a smart idea. trpc + next-auth is the way to go
  - Scaffolds are useful, but not that clever 
    - my model has id string, but blitz scaffolds 10 files that use number as id, painful to refactor)
    - the scaffold is bad
  - 
  - I haaaaaaate creating files for every mutation, query, etc. while keeping a structure that makes blitz happy
  - I hate that blitz forces certain file structure, trpc doesn't
  
## react-hook-form
  So annoying. Everything about it is annoying I honestly don't even know why I'm using it.
  - Banging my head against the wall because of "caching" issues. I'm navigating from one page to another page in Next.js, why does a form keep old values ??? It doesn't make any sense.
