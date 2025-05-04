# victus-gaming-15-kernel-tweaks
This shi fixed my random freezes that made Linux unusable.

---

# Changes:

I basically added the following to the `GRUB_CMDLINE_LINUX_DEFAULT=` line in /etc/default/grub:

```module_blacklist=ucsi_acpi zswap.enabled=0 intel_idle.max_cstate=4```
