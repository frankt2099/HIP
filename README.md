## Contributing

If you plan to add a new _HOPEEcosystem Improvement Proposal (HIP)_ follow this guide:

1. Fork [this repository](https://github.com/Light-Ecosystem/HIP) by clicking 'Fork' in the top right.
2. Install the project dependencies: `npm install`. Note the repository works with `Node v18`.
3. Create a new HIP file with an UPPERCASE_IDENTIFIER: `SOME_HIP.md` following the [HIP template](./X-HIP.md) inside `content/HIPs/` directory.
4. Submit a [Pull Request (PR)](https://github.com/Light-Ecosystem/HIP/pulls) to the [main](https://github.com/Light-Ecosystem/HIP/tree/main).

Your PR must follow the formatting criteria enforced by the build, as detailed in the HIP template. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the HIP as a whole.

If your HIP requires images, the image files should be included in a subdirectory of the `assets` folder for that HIP as follow: `assets/[UPPERCASE_IDENTIFIER]` (for HIP **SOME_HIP** it would be `assets/SOME_HIP/`). When linking to an image in the HIP, you must use the full url for the raw content, for example `https://raw.githubusercontent.com/Light-Ecosystem/HIP/main/content/assets/[UPPERCASE_IDENTIFIER]/image.png`.