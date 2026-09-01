# Publishing

The first release was published manually. Later releases use GitHub OIDC.

One-time pub.dev package admin setting:

- Repository: `Zhangw1998/flutter_avif_native`
- Tag pattern: `v{{version}}`

For each release, update `version` in `pubspec.yaml` and `CHANGELOG.md`, commit to `main`, wait for CI, then push the matching tag:

```sh
git tag v0.1.1
git push origin v0.1.1
```

Publish the required `avif_native` version before updating this package to depend on it.
