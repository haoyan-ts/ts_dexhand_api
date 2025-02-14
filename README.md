# Dexhand Manager API

This project uses [Buf](https://buf.build/) for managing Protocol Buffers.

## Prerequisites

- [Buf CLI](https://docs.buf.build/installation) installed

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/dexhand_manager.git
    cd dexhand_manager/api
    ```

2. Install dependencies:
    ```sh
    buf mod update
    ```

## Usage

### Lint

To lint the Protobuf files, run:
```sh
buf lint
```

### Generate

To generate code from the Protobuf files, run:
```sh
buf generate
```

### Breaking Change Detection

To check for breaking changes, run:
```sh
buf breaking --against <your_base_image>
```

## Directory Structure

```
/api
├── buf.yaml            # Buf configuration file
├── buf.lock            # Buf dependency lock file
├── proto               # Directory containing Protobuf files
│   └── your_protos     # Your Protobuf files
└── README.md           # This README file
```

## Contributing

Please follow the [contribution guidelines](../CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.
