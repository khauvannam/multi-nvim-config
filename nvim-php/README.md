## **Neovim PHP Development Config (nvim-php)**

This configuration is tailored for PHP development using **LazyVim** as the base framework. It provides a robust and modern development experience with intelligent code analysis and static checking.

### Key Features:

* **LazyVim**: Streamlined, opinionated Neovim starter powered by `lazy.nvim`. Includes a curated set of plugins and sensible defaults.
* **Intelephense (LSP)**: Provides fast and comprehensive PHP language support including autocompletion, go-to-definition, hover documentation, and more.
* **PHPStan Integration**: Static analysis tool for catching potential bugs and enforcing strict typing and coding standards.
* **Container-Aware Configuration**: Uses `NVIM_APPNAME=nvim-php` for isolated config, ideal for Distrobox or similar containerized workflows.
* **Auto-Installation**: LazyVim handles plugin setup automatically on first run.

### Workflow Highlights:

* Syntax-aware editing with treesitter
* Linting and diagnostics surfaced inline via LSP and PHPStan
* Format-on-save support (configurable)
* Git integration and project-level file navigation
