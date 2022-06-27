# About
GDAPI is [my](https://github.com/Quasar-Kim) personal project to provide javascript packages to interact with gamefiles of game Geometry Dash.
All packages are publish to npm in [@gdapi] scope and can be easily added to your project.

Features
- **Works on both browser and Node.js environment**: All packages are tested against browser environment and will be tested against node environment.
- **Modular architecture**: this project consists of various small packages instead of a giant one.
- **modern javascript**: Supports Promise API.

# Status
- [`crypto`](https://www.npmjs.com/package/@gdapi/crypto): Encrypts/decrypts gamefiles and levels. **Published on npm**.
- [`plist`](https://www.npmjs.com/package/@gdapi/plist): Parse/stringify simplified plist inside gamefiles. **Published on npm**.
- `gamefile`: Parse/stringify gamefiles into readable javascript object using crypto and plist module. **In developement**.
- `level-str`: Encode/decode encoded level string.
- `level`: Parse/stringify encoded level string into readable javascript object using crypto and level-str module.

