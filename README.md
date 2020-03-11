
# NEO GEO for [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki) 

This is an FPGA implementation of the NEO GEO/MVS system by [Furrtek](https://www.patreon.com/furrtek/posts)

The only modification in this fork is a tweaked main clock from 24MHz (MVS) to 24.167829MHz (AES) (taken from [here](https://wiki.neogeodev.org/index.php?title=Clock)).

This allows having a refresh rate of 59.6Hz which is closer to the NTSC standard and should be accepted by some devices which do not like "exotic" refresh rates such as the BKM-68x or some plasma TVs.
