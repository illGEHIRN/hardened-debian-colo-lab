# Hardened Debian Colo Lab/Blueprint


nbde-lab/
├── README.md          # goal, lab diagram, how to reproduce, what you learned
├── vms/               # virt-install commands / scripts to create the VMs
├── tang/              # Tang setup + nftables rules
├── client/            # LUKS, clevis bind, dropbear-initramfs, static IP in initramfs
├── tamper/            # the systemd service + script
├── tests/             # each test (1–12) with its result, e.g. "07-kernel-update.md"
└── .gitignore
