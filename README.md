# triangOS

tiangOS is an experimental, minimal operating system project. This repository contains the sources, build scripts, and documentation for developing and running triangOS in emulators or on supported hardware.

Status
------
This project is in active development. Expect breaking changes and incomplete features.

Key features (planned or in-progress)
- Minimal kernel with task switching
- Basic driver support (keyboard, screen, disk)
- Simple userspace environment

Getting started
---------------
Requirements
- A modern Linux or macOS development environment
- Rust (if the project is Rust-based) or GCC/Clang for C/C++ projects
- qemu-system-x86_64 for running the OS in an emulator

Build (example)
1. Clone the repo:
   ```bash
   git clone https://github.com/dave41413/triangOS.git
   cd triangOS
   ```
2. Build using the provided build script (adjust for the project's build system):
   ```bash
   ./build.sh
   ```

Run in QEMU (example)
```bash
qemu-system-x86_64 -drive format=raw,file=build/triangos.img -m 512
```

Contributing
------------
Contributions are welcome. Please open issues for bugs or feature requests and submit pull requests for fixes or enhancements. Include tests and documentation where applicable.

License
-------
Specify a license for your project (e.g., MIT, Apache-2.0). If you don't have one yet, consider adding a LICENSE file.

Contact
-------
If you need help or want to collaborate, open an issue or contact the repository owner.
