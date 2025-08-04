# 一键管理服务器运维工具
<img width="1600" height="1491" alt="image" src="https://github.com/user-attachments/assets/12f73489-edd0-45b7-b678-35df5cf376a8" />

支持的操作系统

1. macOS（Darwin系统）

- 使用Homebrew作为包管理器

- 自动检测是否安装Homebrew并提供安装选项

2. Debian系列

- Ubuntu

- Debian

- Linux Mint

- Elementary OS

- Pop!_OS

- Kali Linux

- Deepin

- 使用apt作为包管理器

3. RedHat系列

- CentOS

- RHEL (Red Hat Enterprise Linux)

- Fedora (使用dnf)

- Rocky Linux

- AlmaLinux

- Oracle Linux

- 使用yum/dnf作为包管理器

4. Arch系列

- Arch Linux

- Manjaro

- EndeavourOS

- 使用pacman作为包管理器

5. SUSE系列

- openSUSE

- SLES (SUSE Linux Enterprise Server)

- 使用zypper作为包管理器

支持的系统架构

1. x86_64 / amd64（英特尔/AMD 64位架构）

2. aarch64 / arm64（ARM 64位架构）

脚本会自动检测系统类型、版本、架构和适用的包管理器，并根据检测结果提供相应的安装方法和配置。对于不完全支持的系统，脚本会尝试继续执行，但可能会提示某些功能可能无法正常运行。

该脚本提供了丰富的服务安装和配置功能，适用于多种Linux发行版和macOS系统，是一个跨平台的服务器管理工具。
