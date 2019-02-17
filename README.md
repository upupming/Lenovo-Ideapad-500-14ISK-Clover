# Mojave Hackintosh for Lenovo Ideapad 500-14ISK

Copy and modification of [upupming/Lenovo-G50-80-Clover](https://github.com/upupming/Lenovo-G50-80-Clover), working perfectly on my Lenovo Ideapad 500-14ISK. Read that carefully before diving here.

## Specs

```txt
Model: Lenovo Ideapad 500-14ISK
BIOS version: CFCN24WW
CPU: i6-6200U, HD 520 Graphic
RAM: 4GB
Ethernet: RTL8111
```

See details at [here](https://pcsupport.lenovo.com/us/en/products/laptops-and-netbooks/500-series/500-14isk/80ns/80ns001lcd/mp12u7xn/downloads).

## DSDT patches

See [patches.txt](./DSDT-patching/patches.txt). Only `DSDT.aml` is patched and all `SSDT-*.aml` are ignored.

## Audio

Use `AppleALC.kext` + `layout-id`=15.

![20190217052235.png](https://i.loli.net/2019/02/17/5c69601f3dc8e.png)
