# generator-cl

To install:

```shell
yarn add generator-cl --dev
```

## `cl:comp` (angularjs component)

Lets say we want to make a component called `task-list`, and
attach it to the `clPlatform.app` module.
After changing to your desired directory, run the following...

```shell
yo cl:comp task-list app
```

This will generate the following folder:

```
task-list
├── task-list.component.ts
├── task-list.styles.scss
└── task-list.view.html
```

Now, just add an `import ./task-list/task-list.component.ts';` to `clPlatform.app`.