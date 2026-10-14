# Duckweed

FP64-free GPU application for the Einstein@Home O4abAS all-sky gravitational-wave search.
All GPU kernels run in single precision only, so the search also works on devices with
no or very slow double precision (older GPUs, Intel iGPUs, Jetson, Apple Silicon).

Builds are published on the [Releases](../../releases) page as BOINC anonymous-platform packages.

| Package | Platform | GPU API |
|---|---|---|
| `duckweed-O4AS-windows-x86_64` | Windows 10/11, 64-bit | OpenCL (NVIDIA, AMD, Intel) |
| `duckweed-O4AS-linux-arm64` | Linux arm64, glibc 2.27+ | OpenCL |
| `duckweed-O4AS-macos-arm64` | macOS 12+, Apple Silicon | OpenCL (Apple GPU) |
| `duckweed-O4AS-macos-x86_64` | macOS 10.15+, Intel | OpenCL |

Each package contains the application, an `app_info.xml`, a README with the installation steps,
the licence and SHA-256 checksums. `SHA256SUMS` in the release lists the checksums of the archives.

Licensed under the GNU GPL v3. The corresponding source code is available on request, see `SOURCE.txt` in each package.
