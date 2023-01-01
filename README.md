# Actions

Collection of GitHub Actions workflows I use in one repository for easy management.

## Workflows

Please refer to the actual workflow file for supported inputs.

| Import URL                                                     | Description                                             |
|----------------------------------------------------------------|---------------------------------------------------------|
| `ghifari160/actions/.github/workflows/fat-builder.yaml` | Builds universal macOS binary from two input archives. The workflow expects the binaries to be located in `bin` subdirectory within each archives |
| `ghifari160/actions/.github/workflows/go-builder-linux.yaml`   | Builds Go Linux binaries (x86 and ARM).                 |
| `ghifari160/actions/.github/workflows/go-builder-macos.yaml`   | Builds Go macOS binaries (amd64, ARM, and universal).   |
| `ghifari160/actions/.github/workflows/go-builder-windows.yaml` | Builds Go Windows binaries (x86).                       |
| `ghifari160/actions/.github/workflows/go-builder.yaml`         | Builds Go binary for the specified `GOOS` and `GOARCH`. |
| `ghifari160/actions/.github/workflows/packager-macos.yaml`     | Packages for a macOS release.                           |
