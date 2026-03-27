# Document Ingestion System

## Overview

This repository contains a **document ingestion pipeline** that extracts files from GitHub and processes them for Glean search indexing.

### Features

- **GitHub Integration**: Automatically fetch files from any repository
- **Text Processing**: Clean and normalize document content
- **S3 Storage**: Save processed documents to AWS S3
- **Glean Ready**: Format documents for Glean search engine

## Quick Start

1. Clone this repository
2. Configure AWS Lambda
3. Set up environment variables
4. Deploy the function

## Architecture

## Supported File Types

- Markdown (*.md)
- Text files (*.txt)
- YAML configs (*.yaml)
- Python scripts (*.py)
- JSON files (*.json)

---

## Installation

See [docs/installation.md](docs/installation.md) for detailed setup instructions.

## Documentation

- [Getting Started](docs/getting-started.md)
- [API Reference](docs/api-reference.md)
- [Troubleshooting](docs/troubleshooting.md)

## Contributing

We welcome contributions! Please submit a pull request.

## License

MIT License - see LICENSE file for details.

## Contact

For questions, open an issue on GitHub.
