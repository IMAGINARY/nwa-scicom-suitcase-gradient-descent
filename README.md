# nwa-scicom-suitcase-gradient-descent

Gradient Descent as a suitcase exhibit for NWA Science Communication.

## Usage

Open the `index.html` or the `index-idle-reload.html` file in the `dist` directory with a web browser.

The `index-idle-reload.html` file includes an idle reload feature that refreshes the exhibit after a period of
inactivity. It has the following URL parameters:
- `idleTimeout` (`number`, default: 300): Time of inactivity in seconds before the idle reload is triggered.
- `ignoreButton`: Gamepad button index to ignore for idle detection (default: none). Can be used multiple times.

## Building

Requires Node.js (v18.19 or greater) and npm.

Run the following from the root directory of the project:

```bash
npm install
npm run build
```

This will create a `dist` directory with the compiled exhibit. This directory can be served by any web server.

## Credits

This adaptation was developed by Eric Londaits and Christian Stussak for Imaginary gGmbH.

## License

Code licensed under the MIT License. See [LICENSE](LICENSE) for details.

Copyright 2025 Imaginary gGmbH.

