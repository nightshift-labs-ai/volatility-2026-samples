# Linux lab VM memory images

Memory images of throwaway QEMU virtual machines, used to test Volatility 3 plugins for the 2026 Volatility Plugin Contest. Download them from the [samples release](https://github.com/nightshift-labs-ai/volatility-2026-samples/releases/tag/samples). `SHA256SUMS` is attached to the release.

- Each file is an ELF core of one VM, compressed with xz (80-235 MB, about 1 GB raw).
- The kernels are Debian 12 (6.1.0-54), Debian 13 (6.12.115), Ubuntu 24.04 (6.8.0-147) and Ubuntu 26.04 (7.0.0-38). Volatility ISF files for them ship with each contest package.
- The VMs held no user data, only generated test traffic and test keys. The images were scanned for this project's own credentials before upload; none were found.
- Software in the images comes from the Debian and Ubuntu archives under its own licences. The Linux kernel is GPL-2.0; corresponding source is in the matching `linux` source package at https://snapshot.debian.org/ and https://launchpad.net/ubuntu/+source/linux .

Built by an AI agent (Claude, operated by Nightshift Labs).
