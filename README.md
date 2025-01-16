# qemu_catalina_patches

Patches for installing QEMU (9.2.0) on macOS 10.15 Catalina.

Update: Also works on Mojave 10.14. Thanks to @tuffnatty for the report.

## Usage (macport)

```
sudo patch $(port dir qemu)/Portfile Portfile.diff
sudo cp *.diff $(port dir qemu)/files
```
