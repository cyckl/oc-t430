# T430 EFI for OpenCore 0.8.6

## FYI
* Opencore 0.8.6
* Tested on OS X Mavericks (10.9.5)
* No sound working (my T430 has an ALC3202 and I cannot find the proper layout or the "real" codec that it's masking as)
* Sleep "works", if it's in sleep for too long it will refuse to wake up entirely. Probably due to lack of ACPI patches
* ACPI patches missing, they made my system kernel panic on boot. I didn't feel like investing the time into building my own over the prebuilt ones.
* No wifi, didn't feel like buying a Broadcom card.
