# rothko stock kernel prebuilts

Imported verbatim from OS3.0.307.0.WNNCNXM. This repository contains prebuilts, not a rebuilt kernel.

- Image.lz4 is the original compressed boot kernel.
- dtb/rothko.dtb retains the original Android DT table wrapper and embedded FDT.
- dtbo.img is the matching stock image, including its original AVB data.
- Module sources and normal/recovery load lists retain their partition boundaries.
- PROVENANCE.json records every source file and SHA-256; kernel.config is extracted IKCONFIG.

There are no LK, preloader, bootloader or other firmware images here. These files alone are not an installable ROM. Image signing and compatibility checks remain separate.
