Hi!

/*
   void todo(void) {
        printf("misha_livecd");
   }
*/

This is one of my projects for learning operating systems.
Live-cd image builder
Project name - /* todo();  */ ( because the word is built accordingly to C lang )

Use scripts build_iso and run_iso in ./scripts/ directory
for building and running image correspondingly

Packages, you probably may need:
for making iso image:
apt install xorriso syslinux isolinux squashfs-tools

for testing it on qemu:
apt install qemu qemu-kvm virt-manager bridge-utils

for compiling the linux kernel:
apt install libncurses-dev gawk flex bison openssl libssl-dev dkms libelf-dev libudev-dev libpci-dev libiberty-dev autoconf

It's not tested so well yet as I wish it to be 
but it makes its job well in general case

Sorry that I talk to myself in comments occasionally
It's kinda lack of communication with outside world lol

Any contributions are welcome!
