# azilalmasu

**azilalmasu** is a fork of **uniLoader** made specifically for the **j1xlte** device. It is designed to load **iOS 4**.

The original **uniLoader** is a minimalistic loader capable of booting Linux kernels. It can be used as an intermediate bootloader, providing a clean booting environment in case of a forced and buggy bootloader.

---

## Supported Architectures
- ARMv7 — target architecture for **j1xlte**
- ARMv8 — inherited from **uniLoader**

---

## Make Syntax
```bash
make ARCH=$(arch) CROSS_COMPILE=$(toolchain)
