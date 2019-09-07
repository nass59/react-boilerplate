# React Boilerplate

## 1 - Initialize an npm Project and git Reposotory

```bash
$ npm init
$ git init
```

After creating the repo, you can update info of **package.json** by running the following command:

```bash
$ npm init -y
```

## 2 - Install webpack and create a default bundle

```bash
$ npm install --save-dev webpack webpack-cli
```

```bash
$ npm run build                        // Run without mode
$ npm run build -- --mode development  // Run with development mode
```
