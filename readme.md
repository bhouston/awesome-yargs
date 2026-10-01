# Awesome Yargs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Command-line argument parsing and CLI building for Node.js.

[yargs](https://yargs.js.org) helps you build interactive command-line tools by parsing arguments and generating an elegant user interface. This list collects the packages, tools, and resources around it.

## Contents

- [Official](#official)
- [Command Organization](#command-organization)
- [Configuration and Frameworks](#configuration-and-frameworks)
- [Interactivity and Styling](#interactivity-and-styling)
- [Utilities](#utilities)
- [Documentation Generation](#documentation-generation)
- [Tutorials and Articles](#tutorials-and-articles)
- [Projects Using yargs](#projects-using-yargs)

## Official

- [yargs](https://github.com/yargs/yargs) - Command-line argument parser for Node.js, Deno, and browsers.
- [yargs Documentation](https://yargs.js.org/docs/) - Complete API reference and guides.
- [yargs Examples](https://github.com/yargs/yargs/tree/main/example) - Example CLIs covering common patterns.
- [yargs Advanced Topics](https://github.com/yargs/yargs/blob/main/docs/advanced.md) - Commands, middleware, completion, and configuration.
- [yargs TypeScript Guide](https://github.com/yargs/yargs/blob/main/docs/typescript.md) - Using yargs with TypeScript.
- [yargs-parser](https://github.com/yargs/yargs-parser) - The option parser that powers yargs, usable standalone.
- [yargs-unparser](https://github.com/yargs/yargs-unparser) - Converts a parsed argv object back to its array form.
- [cliui](https://github.com/yargs/cliui) - Multi-column terminal layout used for help output.
- [y18n](https://github.com/yargs/y18n) - Internationalization library used for localized help text.
- [@types/yargs](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/yargs) - TypeScript definitions.

## Command Organization

- [yargs-file-commands](https://github.com/bhouston/yargs-file-commands) - File-system-based command routing, where file names and directories define nested commands.
- [landlubber](https://github.com/razor-x/landlubber) - Typed command modules with built-in pino logging.

## Configuration and Frameworks

- [@ariestools/cli-kit-yargs](https://www.npmjs.com/package/@ariestools/cli-kit-yargs) - Adapter for building reusable command-line applications with cli-kit.
- [Black Flag](https://github.com/Xunnamius/black-flag) - Declarative framework for building deeply hierarchical commands on top of yargs.

## Interactivity and Styling

- [@jercle/yargonaut](https://github.com/jercle/yargonaut) - Decorates help output with chalk styles and figlet fonts.
- [yargs-interactive](https://github.com/nanovazquez/yargs-interactive) - Prompts for missing arguments interactively using Inquirer.

## Utilities

- [@bpinternal/yargs-extra](https://www.npmjs.com/package/@bpinternal/yargs-extra) - Parses options from environment variables and generates JSON Schema from option definitions.

## Documentation Generation

- [@clidoc/yargs](https://github.com/bhouston/clidoc/tree/main/packages/yargs) - Generates OpenCLI documents and CLI reference docs from yargs command modules.
- [cli-docs-generator](https://github.com/EliseevNP/cli-docs-generator) - Generates Markdown docs for a yargs CLI.
- [yargs-help-output](https://github.com/CrowdStrike/yargs-help-output) - Updates Markdown docs with the full help output of a yargs CLI.

## Tutorials and Articles

- [Building a CLI Tool with Node.js](https://thecodebarbarian.com/building-a-cli-tool-with-node-js.html) - Walkthrough of a real-world CLI with token storage.
- [Modern Node.js: Command Line Applications with yargs](https://zaiste.net/posts/modern-nodejs-cli-yargs/) - Concise introduction to commands and options.

## Projects Using yargs

- [c8](https://github.com/bcoe/c8) - Native V8 code coverage reporter.
- [electron-builder](https://github.com/electron-userland/electron-builder) - Packaging and distribution of Electron apps.
- [Jest](https://github.com/jestjs/jest) - JavaScript testing framework.
- [Lerna](https://github.com/lerna/lerna) - Monorepo management and publishing.
- [nyc](https://github.com/istanbuljs/nyc) - Istanbul command-line interface for code coverage.
- [semantic-release](https://github.com/semantic-release/semantic-release) - Fully automated version management and package publishing.
- [TypeORM](https://github.com/typeorm/typeorm) - ORM for TypeScript and JavaScript.
- [web-ext](https://github.com/mozilla/web-ext) - Command-line tool for developing browser extensions.
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Browser and mobile automation framework.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first.
