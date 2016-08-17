# pdoc

### Getting Started

Set up your project in your code directory
```
git clone https://github.com/hamue/pdoc.git
cd pdoc
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
./bin/proto2yml proto/0.33.0.proto > _data/apis_0_33_0.yml
```

- ymlapi2md : Create default .md files for enums and messages (templates used are in `./templates`)

```sh
./bin/ymlapi2md _data/apis_0_33_0.yml
```

### Issues

If you have problems, please create a
[GitHub Issue](https://github.com/hamue/pdoc/issues).

### Contributing

Have a fix or want to add a feature?
[Pull Requests](https://github.com/hamue/pdoc/pulls) are welcome!

### Credits

Thank you to all of [the contributors](https://github.com/hamue/pdoc/contributors)!

### License

[GPL](LICENSE.md)
