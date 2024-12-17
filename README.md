# `make` commands
  - `macos_arm64` : make ovm bootable image for macos arm64
  - `wsl2_amd64`  : make ovm wsl2 rootfs distribute



# Development environment
- `SKIP_BUILD_PROOT=true`: Skip build [proot](https://github.com/proot-me/proot)
- `SKIP_APT_GET_INSTALL=true`: Skip `apt update && apt install -y required package`
- `VM_PROVIDER=qemu`: using qemu as vm provider
