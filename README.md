# Pokekon Go Dev Documentation

### Getting Started

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

- proto2yml : Create a yml file out of a .proto file

```sh
./bin/proto2yml proto/v0.33.0.proto > _data/api_latest.yml
```

- ymlapi2md : Create default .md files for enums and messages (templates used are in `./templates`)

```sh
./bin/ymlapi2md _data/api_latest.yml
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
