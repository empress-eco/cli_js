<p align="center">
cli_js is a powerful Command Line Interface designed to streamline the process of building and managing EmpressJS applications. It is tailored to simplify app creation, model definition, and application serving in development mode, as well as building applications for deployment.
<br />
<a href="https://empress.eco/">Explore the Docs</a> |
<a href="https://github.com/empress-eco/cli_js/issues">Report Bugs</a> |
<a href="https://github.com/empress-eco/cli_js/issues">Request Features</a> |
<a href="https://github.com/empress-eco/cli_js">Support</a>
</p>

## About cli_js

### Overview
cli_js is designed with developers in mind, offering predefined templates for rapid app creation, easy model generation and seamless app serving with auto-reload capabilities. Whether you're working in a browser or Electron, cli_js has got you covered. 

### Key Features
- Rapid app creation with predefined templates
- Easy model generation
- Seamless app serving in Browser and Electron with auto-reload capability 
- Application build feature (under development)

## Getting Started with cli_js

### Prerequisites
Before getting started, ensure that Node.js and NPM are installed in your development environment.

### Installation
To install cli_js globally using NPM, use the following command:

```sh
npm i -g https://github.com/empress-eco/cli_js.git
```

## Usage

cli_js offers a variety of commands for easy app management. Here's a quick start guide:

1. **Create a new app:** Use the command `Empress create-app app-name`, then follow the prompts to select a boilerplate, target platform, and package manager.

```sh
Empress create-app app-name
```

2. **Create a new model:** Use the command `Empress create-model model-name` and provide the model details as prompted.

```sh
Empress create-model model-name
```

3. **Serve your application:** Use the `Empress start` command to serve your app in the browser or `Empress start electron` to serve your app in Electron.

```sh
Empress start 
Empress start electron
```

## Contribution Guidelines
We warmly welcome contributions from the developer community! To contribute, follow these steps:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

Your contributions will help make cli_js an even more powerful tool for EmpressJS app development!

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the MIT License.

We extend our heartfelt thanks to the Empress Community, whose pioneering work and ongoing support have been instrumental in powering this project. We appreciate their dedication and innovation in creating the essential tools we rely on.