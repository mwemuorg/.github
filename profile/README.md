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

### Contributors

[![Contributors](https://contrib.rocks/image?repo=mwemuorg/mwemu)](https://github.com/mwemuorg/mwemu/graphs/contributors)

Core work by [@sha0coder](https://github.com/sha0coder) (creator & maintainer),
[@brandonros](https://github.com/brandonros) (AArch64, macOS & serialization),
[@acheron2302](https://github.com/acheron2302) (DLL emulation, loaders, optimizations),
[@mrexodia](https://github.com/mrexodia) (GDB stub),
[@ElCapor](https://github.com/ElCapor) (instruction hooks & exceptions) and
[@SleathCobra](https://github.com/SleathCobra) (pymwemu).

Thanks also to everyone who opened issues and shaped the direction —
[@Thell](https://github.com/Thell) (who first proposed a library back in the scemu days),
[@darknessxk](https://github.com/darknessxk),
[@icyfox168168](https://github.com/icyfox168168),
[@carouselcarousel](https://github.com/carouselcarousel),
[@omarandlorraine](https://github.com/omarandlorraine) and more.

### License

mwemu is licensed under **GPL-3.0-only**. For commercial or proprietary use under different terms, contact the author for a separate license.
