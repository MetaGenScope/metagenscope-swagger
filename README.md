# MetaGenScope Swagger

> Swagger API spec for MetaGenScope.

## Getting Started

`metagenscope-swagger` is run as part of [`metagenscope-main`](https://github.com/bchrobot/metagenscope-main).

### Running

> **Note:** be aware of which Docker environment your shell is configured for: `docker-machine ls`. This will affect what URL you will use to access the Swagger client.

Build the image:

```sh
$ docker build -t metagenscope-swagger .
```

Set up environment:

```sh
$ export API_URL=https://raw.githubusercontent.com/bchrobot/metagenscope-swagger/master/swagger.yml
```

Run the image, exposing the Swagger client on port 8080:

```sh
$ docker run -p 8080:8080 -e API_URL metagenscope-swagger
```

Visit client at `http://localhost:8080`.

## Contributing

Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository][project-tags].

## Release History

See [`CHANGELOG.md`](CHANGELOG.md)

## Authors

* **Benjamin Chrobot** - _Initial work_ - [bchrobot](https://github.com/bchrobot)

See also the list of [contributors][contributors] who participated in this project.

## License

This project is licensed under the MIT License - see the [`LICENSE.md`](LICENSE.md) file for details.


[project-tags]: https://github.com/bchrobot/metagenscope-swagger/tags
[contributors]: https://github.com/bchrobot/metagenscope-swagger/contributors
