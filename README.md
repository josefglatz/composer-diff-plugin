# josefglatz/composer-diff-plugin

> A composer plugin...
> * to show library version diff at "composer update" (e.g. for putting
>   into your GIT commit message),
> * to create and update a `composer.list` file next to the
>   `composer.json`.


![composer-diff-plugin](https://cloud.githubusercontent.com/assets/835251/11893915/46c9bb40-a5b7-11e5-8340-db3917d04221.png)

## Features

* print upgrade/downgrade/add/remove of libraries.
* output `composer.list` file which can be added to project's GIT
  repository.


## Install/Uninstall

Depending on your use case it makes sense to add this plugin globally in
your development environment.

### Global

```bash
$ composer global require josefglatz/composer-diff-plugin
```

```bash
$ composer global remove josefglatz/composer-diff-plugin
```

### Locally

When installing the plugin locally for a specific project it's
recommended to add it as dev-dependency only.

```bash
$ composer --dev require josefglatz/composer-diff-plugin
```

```bash
$ composer --dev remove josefglatz/composer-diff-plugin
```

## License

Copyright 2016 Mercari, Inc.  
Copyright 2020 Josef Glatz

Licensed under the [MIT License](LICENSE)

## Support

Many thanks to my employer [supseven.at](https://www.supseven.at/) for
sponsoring work time.
