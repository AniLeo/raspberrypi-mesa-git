## raspberry-mesa-git
Arch Linux mesa-git AUR package for Raspberry Pi systems running [Arch Linux ARM](https://archlinuxarm.org/)

#### OpenGL/gallium drivers included:
- softpipe (Software-only reference driver)
- llvmpipe (Software-only performant driver)
- zink (OpenGL-on-Vulkan driver)
- virgl (Virtual GPU for use inside QEMU VMs)
- svga (Virtual GPU for use inside VMWare VMs)
- vc4 (Hardware Broadcom OpenGL driver for Raspberry Pi 3 and older devices)
- v3d (Hardware Broadcom OpenGL driver for Raspberry Pi 4 and newer devices)

#### Vulkan drivers included:
- swrast/lavapipe (Software-only driver)
- virtio (Virtio-GPU protocol for Vulkan command serialization)
- broadcom/v3dv (Hardware Broadcom Vulkan driver for Raspberry Pi 4 and newer devices)

#### Patches included:
- [v3d: Use the state uploader for QUNIFORM_UBO_ADDR](https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests/30986), required for RPCS3 to work with OpenGL
