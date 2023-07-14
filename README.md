## How to build the kernel

1. Intitalize your local repository using this manifest:

```
repo init -u https://github.com/oplus-sm8450-kernel/manifest.git -b KERNEL.PLATFORM.1.0.r1-12400-kernel.0
```

2. Then to sync up:

```
repo sync
```

3. Run the kernel build for your device. E.g for waipio:

```
./build.sh waipio
```

4. Find the build artifacts in `device/qcom/waipio-kernel/`. This includes the kernel (Image), the kernel modules, dtb and dtbo, kernel headers and some host utilities.
