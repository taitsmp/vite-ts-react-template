Template project with

- pnpm
- vite
- react
- typescript
- VS Code

### Adding Redux

```
pnpm add  react-redux @reduxjs/toolkit
pnpm add -D @types/react-redux
pnpm add -D @redux-devtools/extension #maybe not needed?
```
Follow steps here - https://redux-toolkit.js.org/tutorials/typescript

#### Redux - preferred locations

##### Redux specific stuff
* store -`src/store/index.ts`
* slices - `src/store/<entity>/slice.ts`
* selectors - `src/store/<entity>/selectors.ts`

##### General stuff

* hooks - `src/hooks.ts`
* components - `src/components/`
* views (or pages) - `src/views` 
* api - `src/api`



