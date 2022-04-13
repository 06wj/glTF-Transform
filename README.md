# glTF-Transform

[![Latest NPM release](https://img.shields.io/npm/v/@gltf-transform/core.svg)](https://www.npmjs.com/package/@gltf-transform/core)
[![Minzipped size](https://badgen.net/bundlephobia/minzip/@gltf-transform/core)](https://bundlephobia.com/result?p=@gltf-transform/core)
[![License](https://img.shields.io/badge/license-MIT-007ec6.svg)](https://github.com/donmccurdy/glTF-Transform/blob/main/LICENSE)
[![Build Status](https://github.com/donmccurdy/glTF-Transform/workflows/build/badge.svg?branch=main&event=push)](https://github.com/donmccurdy/glTF-Transform/actions?query=workflow%3Abuild)
[![Coverage](https://codecov.io/gh/donmccurdy/glTF-Transform/branch/main/graph/badge.svg?token=Z91ZYFEV09)](https://codecov.io/gh/donmccurdy/glTF-Transform)

*glTF 2.0 SDK for JavaScript, TypeScript, and Node.js.*

<!-- NOTICE: This section is duplicated in docs/INDEX.md. Please keep them in sync. -->

glTF-Transform supports reading, editing, and writing 3D models in glTF 2.0 format. Unlike 3D modeling tools — which are ideal for artistic changes to geometry, materials, and animation — glTF-Transform provides fast, reproducible, and lossless control of the low-level details in a 3D model. The API automatically manages array indices and byte offsets, which would otherwise require careful management when editing files. These traits make it a good choice for bundling, splitting, or optimizing an existing model. It can also be used to apply quick fixes for common issues, to build a model procedurally, or to easily develop custom extensions on top of the glTF format. Because the core SDK is compatible with both Node.js and Web, glTF-Transform may be used to develop offline workflows and web applications alike.

glTF-Transform is modular:

- `@gltf-transform/core`: Core SDK, providing an expressive API to read, edit, and write glTF files.
- `@gltf-transform/extensions`: [Extensions](https://gltf-transform.donmccurdy.com/extensions.html) (optional glTF features) for the Core SDK.
- `@gltf-transform/functions`: [Functions](https://gltf-transform.donmccurdy.com/functions.html) for common glTF modifications, written using the core API.
- `@gltf-transform/cli`: [CLI](https://gltf-transform.donmccurdy.com/cli.html) to apply functions to glTF files quickly or in batch.

To get started, head over to the [documentation](https://gltf-transform.donmccurdy.com).

<p align="center">
<img src="https://gltf-transform.donmccurdy.com/media/kicker.jpg" alt="Function symbol, f(📦) → 📦, where the argument and output are a box labeled 'glTF'." width="40%">
</p>

## License

Copyright 2021, MIT License.

## Credits

See [*Credits*](https://gltf-transform.donmccurdy.com/credits.html).
