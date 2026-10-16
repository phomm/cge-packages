# Castle Game Engine Packages

This is currently a semi-official repository for packages and extensions for
[Castle Game Engine](https://castle-engine.io/). The engine's official source
code is available in the [castle-engine GitHub repository](https://github.com/castle-engine/castle-engine).

The package system is under development. See the
[packages system roadmap](https://castle-engine.io/roadmap#packages) for plans
and progress.

## Contributing

Contributions are welcome. To add or update a package, add or edit its JSON
file in [`data/`](data/). Use the package title to name the file, lowercased
with spaces replaced by dashes, and include the package details and links.
Place package images in [`images/`](images/) and refer to them by filename in
the JSON.

## Usage

When changes to `data/*.json` are pushed, GitHub Actions automatically
generates the combined `unified.json` package index and commits it to the
repository, this resulting file is used by castle engine tool-chain 
to operate packages in projects (editor and build-tool)
