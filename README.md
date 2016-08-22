# Pokekon Go Dev Documentation

### Getting Started

#### Dependencies to run locally

- Linux / OSX
- Ruby (> 2.0)

#### Let's Get It On

Set up your project in your code directory
```
git clone https://github.com/pogodevorg/pogodevorg.github.io.git
cd pogodevorg.github.io.git
```

Install dependencies
```
./bin/setup
```

Run the server and watch for changes in your files
```
./bin/server
```

### Helper scripts

#### Main script

- `gen-all` : Generate everything from the `.proto` files in the `proto` folder. This should be the only script you have to call manually.

```sh
./bin/gen-all
```

#### Sub-scripts (If the `gen-all` script fails, PANIC!)

- proto2yml : Create a `.yml` file out of a `.proto` file

```sh
./bin/proto2yml proto/v0.33.0.proto > _data/api_latest.yml
```

- ymlapi2md : Create default `.md` files for `enums` and `messages` (templates used are in `./templates`)

```sh
./bin/ymlapi2md _data/api_latest.yml
```

- ymlapi2changelog : Create default changelog `.md` files between 2 versions of the API (templates used are in `./templates`)

```sh
./bin/ymlapi2changelog _data/api_0_31_0.yml _data/api_0_33_0.yml
```

### Issues

If you have problems, please create a
[GitHub Issue](https://github.com/pogodevorg/pogodevorg.github.io/issues).

### Contributing

Have a fix or want to add a feature?
[Pull Requests](https://github.com/pogodevorg/pogodevorg.github.io/pulls) are welcome!

### Credits

Thank you to all of [the contributors](https://github.com/pogodevorg/pogodevorg.github.io/contributors)!

### License

[GPL](LICENSE.md)
