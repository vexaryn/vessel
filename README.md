[![license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# Vessel - Hive Desktop Wallet

Vessel is a lightweight desktop wallet for the Hive blockchain, allowing you to interact with your wallet without running the full blockchain locally.

### [Official Website](https://vesselwallet.org)

### [Latest Release](https://github.com/vexaryn/vessel/releases)

## Features

- Cross-platform desktop wallet for Windows, macOS, and Linux
- Built with Electron, React, Redux, and Hive JS
- Support for `hive://` and `vessel://` protocol links

## Getting Started

1. Download the latest version of Vessel from the [Releases](https://github.com/vexaryn/vessel/releases) page.
2. Install or launch the version for your operating system.
3. Open Vessel and add your Hive account.
4. Review all transaction details carefully before signing or broadcasting an operation.

## Installing and Running From Source

Vessel uses an older Electron/Node.js toolchain. Depending on your environment, a compatible legacy Node.js setup may be required to install the original dependencies successfully.

```bash
# Clone the repository
git clone https://github.com/vexaryn/vessel.git
cd vessel

# Install dependencies
yarn install
# or
npm install

# Build the application
npm run build

# Start Vessel
npm start
```

### Development

To run the development environment:

```bash
npm run dev
```

### Creating Application Packages

The project includes scripts for creating desktop application packages:

```bash
# Windows
npm run package-win

# Linux
npm run package-linux

# Build all configured targets
npm run package-all
```

## Development and Testing

The project includes scripts for linting, type checking, testing, building, and end-to-end testing.

```bash
# Run tests
npm test

# Run linting
npm run lint

# Run Flow type checks
npm run flow

# Run end-to-end tests
npm run test-e2e

# Run the complete validation sequence
npm run test-all
```

## Security

- Never share your private keys or passwords.
- Keep secure backups of your Hive account credentials.
- Download Vessel only from the official website or this repository's Releases page.
- Review transaction details carefully before signing or broadcasting an operation.
- Verify release files when checksums or signatures are provided.

## No Support & No Warranty

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.

## License

Vessel is open-source software licensed under the MIT License.
