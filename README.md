# Calculator App

[简体中文文档](./doc/README_CN.md)

A modern calculator application built with Vue.js and Tauri, providing a cross-platform desktop experience.

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Responsive design
- Cross-platform support (Windows, macOS, Linux)
- Storybook component documentation
- End-to-end testing with Cypress

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/calculator.git
   cd calculator
   ```

2. Install dependencies:

   ```bash
   yarn install
   ```

3. Start the development server:

   ```bash
   yarn dev
   ```

## Usage

Run the application in development mode:

```bash
yarn dev
```

Build the application for production:

```bash
yarn build
```

## Testing

Run unit tests:

```bash
yarn test:unit
```

Run end-to-end tests:

```bash
yarn test:e2e
```

## Storybook

View component documentation:

```bash
yarn storybook
```

## Building for Desktop

To build the desktop application using Tauri:

1. Install Tauri CLI (if not already installed):

   ```bash
   cargo install tauri-cli
   ```

2. Build the application:

   ```bash
   yarn tauri build
   ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeatureName`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeatureName`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
