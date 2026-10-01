# sa

An AL extension project for Microsoft Dynamics 365 Business Central.

## Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [AL Language extension](https://marketplace.visualstudio.com/items?itemName=ms-dynamics-smb.al)
- Access to a Business Central environment (sandbox, Docker container, or on-premises)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Mero2026/sa.git
   cd sa
   ```

2. Open the folder in Visual Studio Code.
3. Run **AL: Go!** or create a `.vscode/launch.json` pointing at your Business Central environment.
4. Run **AL: Download Symbols** to fetch the symbol packages into `.alpackages/`.
5. Press `F5` to build and publish the extension.

## Project Structure

Build outputs and local environment files are excluded by `.gitignore`:

| Path | Purpose |
| --- | --- |
| `.vscode/` | Local launch configuration |
| `.alpackages/` | Downloaded symbol packages |
| `.alcache/` | Compiler cache |
| `.snapshots/` | Snapshot debugging files |
| `.output/` | Test output |
| `*.app` | Compiled extension packages |

## License

This project is licensed under the [MIT License](LICENSE).
