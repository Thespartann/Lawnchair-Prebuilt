## Lawnchair-Prebuilt

**This repo is a template for adding a prebuilt apk to a Rom.**

**Guide**

Clone this anywhere you want. For example you can clone it into 
`rom/packages/apps` or `vendor/rom/prebuilt/app`

After that you need to tell the Rom to add the package like show in the 
commit:

* https://github.com/LineageOMS/android_vendor_cm/commit/218eed7ae28e1185bf922af710f2b944b6241bc4

__(Some Roms add their packages in packages.mk instead of common.mk, for 
example AOSiP)__

That's mostly it. The package could also be added to 
`build/target/product/core.mk` 
