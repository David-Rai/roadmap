# Random Things I Learned

## 1. Monorepo
https://youtu.be/6LoqigJpifg?si=EvHe4QQq4Sz0dJC5

Monorepo are the architecture or method to manage a fullstack software or  which contains all the
multiple projects (apps,packages,utils,services) all togther by sharing the same packages  instead of splitting
it into the multiple repos

```bash
apps/
  frontend/     ← React app
  backend/      ← Express app
packages/
  utils/        ← shared logic
  validation/   ← shared schemas
```

## Advantages
- Single codebase
- Reusibilty
- Full acccess or faster accesibility of full codebase
- Avoids the duplication of the packages in isolated sub_folders
- Utils are shared

## Things require to consider a project as a monorepo architecture
- single repo
- Multiple folder and packages
- seperate sub node modules or single root node_modules


[example](https://github.com/david-rai/yapzone)
