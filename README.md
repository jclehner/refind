rEFInd fork
===========

This fork adds a config file option that can be used to disable the external GPU
on some MacBooks. In your `refind.conf`, simply add `disable_ext_gpu=on` in the
global part.

When using this option, rEFInd will modify the `gpu-power-prefs` EFI variable,
may enable some MacBooks with broken external GPUs to boot.

Binaries can be downloaded [here](https://github.com/jclehner/refind/releases).
