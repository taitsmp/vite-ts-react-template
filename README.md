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

1. Follow steps here - https://redux-toolkit.js.org/tutorials/typescript
2. Hook up the `Provider` in `index.js`

```
const root = ReactDOM.createRoot(document.getElementById('root'))
root.render(
  <Provider store={store}>
    <App />
  </Provider>
)
```



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



