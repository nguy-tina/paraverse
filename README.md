# Paraverse

Paraverse assembles the public record of a conference into a knowledge base you can
browse. It covers sessions, speakers, people, organizations, repositories and packages.
Every kind of entity is stored as plain YAML records in one shared format, so different
editions and different conferences line up side by side.
Each record cites the sources it was built from.

The first conference covered is
[GitHub Universe](https://github.com/jlevy/universe2026-md#readme).
Its dataset pipeline crawls the official conference website and agenda, then enriches
identified accounts with public professional profiles, including Bright Data’s public
profile datasets. The
[dataset guide](https://github.com/jlevy/universe2026-md#sources-and-collection)
describes collection and offline rebuilding.

Paraverse imports the dataset’s graph and records into its database and serves a browser
for exploring them. See [db/README.md](db/README.md) for installation, dataset loading
and the browser; [curation/README.md](curation/README.md) covers reviewing additional
professional connections.

## Data Policy

Everything in this repository is public.
Read the [data policy](docs/data-policy.md) before adding or changing data.
To have your data removed, open an issue or contact a maintainer.

## Contributing

Agents and humans follow [AGENTS.md](AGENTS.md).
Work is tracked with [tbd](https://github.com/jlevy/tbd), and records are validated with
[softschema](https://github.com/jlevy/softschema).

## License

[MIT](LICENSE)

<!-- This document follows common-doc-guidelines.md.
See github.com/jlevy/practical-prose and review guidelines before editing.
-->
