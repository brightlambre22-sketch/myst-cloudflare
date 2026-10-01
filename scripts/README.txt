Put your Linux boot image in public/boot/.

Examples:
  public/boot/linux.iso
  public/boot/linux.img

Then deploy with:
  npx wrangler deploy

Open:
  /vm.html?boot=linux.iso
or
  /vm.html?boot=linux.img

The browser runs the v86 VM. The Worker serves the boot image as a static asset.
