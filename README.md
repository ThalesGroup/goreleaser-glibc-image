# `goreleaser` glibc container image

## Get started

TL;DR: You can use this container image in your terminal:

```bash
podman pull ghcr.io/thalesgroup/goreleaser-glibc-image:<my_tag>
docker pull ghcr.io/thalesgroup/goreleaser-glibc-image:<my_tag>
```

or within your Containerfiles:

```docker
FROM ghcr.io/thalesgroup/goreleaser-glibc-image:<my_tag>
```

or from a Gitlab ci Job:

TODO: add a sample of Gitlab ci `.gitlab.yml`.

## Documentation

[Documentation](docs/README.md)

## Contributing

If you are interested in contributing to the XXX project, start by reading the [Contributing guide](/CONTRIBUTING.md).

## License

The chosen license in accordance with legal department must be defined into an explicit [LICENSE](https://github.com/ThalesGroup/template-project/blob/master/LICENSE) file at the root of the repository
You can also link this file in this README section.

Our container ships with `trivy`, `syft`, `cosign`, `ko-build/ko` and `goreleaser`:

* [`aquasecurity/trivy`](https://github.com/aquasecurity/trivy) is under Apache-2.0 license
* [`anchore/syft`](https://github.com/anchore/syft) is under Apache-2.0 license
* [`sigstore/cosign/`](https://github.com/sigstore/cosign/) is under Apache-2.0 license
* [`ko-build/ko`](https://github.com/ko-build/ko) is under Apache-2.0 license
* [`goreleaser/goreleaser`](https://github.com/goreleaser/goreleaser) is under MIT License
