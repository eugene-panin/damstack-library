# damstack-library

The library of [damstack](https://github.com/eugene-panin/damstack): the
platforms and the apps it offers, in [`library.yaml`](library.yaml).
damstack reads it at most once an hour, so a stack joins or changes without a
new release of damstack.

The library is curated. A platform here is maintained with damstack; an app
here is written against the contract of a platform, what it `provides`, and
tested on it.

| Field | |
|---|---|
| `name` | what people type: `damstack deploy hashi`, `damstack app add mail` |
| `kind` | `app` for an app; a platform has none |
| `platform` | the platform an app runs on |
| `url` | the repository, named `damstack-<name>` |
| `description` | one line, for the lists of damstack |

## License

MIT, see [LICENSE](LICENSE).
