# Mysterium Cloudflare Browser VM

This project is a first-stage browser Linux boot test using v86 and TinyCore.

## Required binary assets

Place these files in the indicated paths before deployment:

- public/v86/libv86.js
- public/v86/v86.wasm
- public/bios/seabios.bin
- public/bios/vgabios.bin
- public/boot/TinyCore-11.0.iso
- src/mystnet.wasm (optional for the current VM page; retain for the Worker project)

Deploy with `npx wrangler deploy`.
