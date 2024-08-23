# Metta Prebuilt Binary

This repository is intended to provide a quick and easy way to install and run Metta on your system.

## Quick Setup

To quickly set up and run the Metta binary, run the following command in your terminal:

```bash
curl -fsSL https://raw.githubusercontent.com/iCog-Labs-Dev/metta-prebuilt-binary/main/install.sh | bash
```

## Usage

After running the setup script, you can start using Metta directly from the terminal.

### Linux
- `metta-run`: Run Metta with the Python environment automatically activated.
- `metta`: Run Metta without activating the Python environment automatically but you need to activate it manually.

### Running Metta

- To run a Metta file:

  ```bash
  metta-run example.metta
  ```

- To format binary tree:

  ```bash
  metta-run example.metta fbt
  ```

- To format constraint tree:

  ```bash
  metta-run example.metta fct
  ```
- To format any output you get from metta-run:

  ```bash
  metta-run example.metta f
  ```

- To run Metta without automatically activating the Python environment (you need to activate it manually first):

  ```bash
  source $HOME/metta-bin/venv/bin/activate
  metta example.metta
  ```

## Update

To update the Metta binary and its environment, run the following command:

```bash
curl -fsSL https://raw.githubusercontent.com/iCog-Labs-Dev/metta-prebuilt-binary/main/update.sh | bash
```

## Uninstall

To uninstall the Metta binary and remove its environment, manually delete the installation directory and binaries:

```bash
curl -fsSL https://raw.githubusercontent.com/iCog-Labs-Dev/metta-prebuilt-binary/main/uninstall.sh | bash
```

## Windows

Unfortunately, this setup script is designed for Unix-like systems. We recommend using Linux for a seamless experience. However, if you're on Windows, you can use the Windows Subsystem for Linux (WSL) to install and run the Metta binary. Follow these steps:

1. Install WSL by following [Microsoft's official guide](https://docs.microsoft.com/en-us/windows/wsl/install).
2. Set up a Linux distribution of your choice.
3. Run the setup script inside your WSL terminal:

```bash
curl -fsSL https://raw.githubusercontent.com/iCog-Labs-Dev/metta-prebuilt-binary/main/install.sh | bash
```

Come, join us in the world of Linux for a smoother and more powerful development experience!

## Troubleshooting

If you encounter any issues during installation or usage, please open an issue on the [GitHub repository](https://github.com/iCog-Labs-Dev/metta-prebuilt-binary/issues).
