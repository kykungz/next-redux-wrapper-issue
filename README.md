Reproduction of the issue https://github.com/kirill-konshin/next-redux-wrapper/issues/129

1. Create new project
```bash
# Create new project using creat-next-app
create-next-app next-redux-wrapper-issue

# Use next version 7
yarn add next@7

# Add dependencies
yarn add redux react-redux next-redux-wrapper
```

2. Copy `_app.js` from the `next-redux-wrapper` installation guide
3. Add `export default connect(state => state)(Home)` to `pages/index.js`
4. `yarn dev`
