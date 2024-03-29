# vizo_app_generator

A project with many code templates used at Vizo.dev.

## Installing Mason (first time)
🎯 Activate from https://pub.dev/packages/mason_cli <br />
```dart pub global activate mason_cli```

## Getting Started (using templates)
On this repository terminal: <br />
```mason get``` <br />
(will list all templates added to this repository)

```mason make``` <br />
(will list all templates added to your global list) <br />


(Example: template called 'hello') <br />
```mason make hello```

```mason make hello -o .\generated\hello```

```mason make weather -c .\bricks\weather\config.json -o .generated\weather```

## Create/Add
```mason new NAME``` <br />
(create new template)

```mason add --global --path ./bricks/FOLDER_NAME NAME``` <br />
(after template is setup, add it to your global templates list) <br />
(so you can you this template outside the current folder/repository)

```
Usage:
mason add [arguments]
-h, --help       Print this usage information.
-g, --global     Adds the brick globally.
--git-url        Git URL of the brick
--git-ref        Git branch or commit to be used
--git-path       Path of the brick in the git repository
--path           Local path of the brick
```

## Advanced features (install templates)
```mason install --source git https://github.com/fellangel/mason --path bricks/greeting```

```mason install --source path .\bricks\weather```


For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
