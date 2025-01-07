# debootstrap-kali-rolling-luks2-secure-boot-guide
I will demonstrate how to use debootstrap to build Kali Linux on a USB thumb drive. While in chroot, I will demonstrate how to compile grub2 with ArchLinux's grub-improved-luks2 that allows me to encrypt the root system with argon2id password hashing algorithm. Lastly, I will create machine owner key (MOK) to sign grub bootloader and vmlinuz.
