<h1 align="center">mwemu</h1>

<p align="center">
  <b>x86 / x64 / ARM64 emulator for securely emulating malware and system internals.</b>
</p>

<p align="center">
  Emulate shellcode and PE / ELF / Mach-O binaries — step by step, scriptable, no VM required.
</p>

<p align="center">
  <a href="https://mwemu.github.io/">Website</a> ·
  <a href="https://crates.io/crates/libmwemu">crates.io</a> ·
  <a href="https://pypi.org/project/pymwemu/">PyPI</a>
</p>

---

### Repositories

| Repo | What it is |
|------|------------|
| [**mwemu**](https://github.com/mwemuorg/mwemu) | The command-line emulator — the flagship tool. |
| [**libmwemu**](https://github.com/mwemuorg/libmwemu) | Core emulation engine as a Rust library ([crates.io](https://crates.io/crates/libmwemu)). |
| [**pymwemu**](https://github.com/mwemuorg/pymwemu) | Python bindings ([PyPI](https://pypi.org/project/pymwemu/)). |
| [**cmwemu**](https://github.com/mwemuorg/cmwemu) | C ABI bindings (cdylib / staticlib + generated header). |
| [**mwemu-mcp**](https://github.com/mwemuorg/mwemu-mcp) | Model Context Protocol server — drive mwemu from AI tooling. |

### Highlights

- x86 (32 & 64-bit) and AArch64 emulation
- Windows / Linux / macOS userland and system internals
- Shellcode and PE / ELF / Mach-O loaders
- Scriptable from **Rust**, **Python** and **C**
- `--winver`: genuine Windows system DLLs fetched on demand from Microsoft's symbol server (no ISO needed)

### License

mwemu is licensed under **GPL-3.0-only**. For commercial or proprietary use under different terms, contact the author for a separate license.

<sub>Built by <a href="https://github.com/sha0coder">@sha0coder</a> and contributors — and thanks to everyone who reported issues and helped shape the project.</sub>
