Configuration files for GPU Passthrough with Proxmox

Disabling legacy usb devices requires "tablet: 0" and it breaks GUI USB plugging

You can add devices manually, see /etc/pve/qemu-server/example.conf

GUI PCI-E plugging for gpu's still works normally, toggle on: "Primary GPU","ROM-Bar" and "PCI-Express"

GUI PCI-E plugging for audio devices still works normally, toggle on "ROM-Bar" and "PCI-Express"
 
