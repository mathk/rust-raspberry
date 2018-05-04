Linking with :

```bash
arm-none-eabi-gcc -T layout.ld -o myos.elf -ffreestanding -O2 -nostdlib -static -nostartfiles -lk -L./libc  -lgcc boot.o target/armv7-unknown-linux-gnueabihf/debug/libkernel.rlib
```