## agx_a000

> `Firmware/agx/armfw_g18p.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cfb4
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3d008
+  __TEXT.__gxf_code: 0x5120
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1068
+  __TEXT.__const: 0x10ad
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
   __TEXT.__cstring: 0x2346
   __TEXT.__init_offsets: 0x0
-  __TEXT.__chain_starts: 0x20
-  __DATA.__gxf_data: 0x80b8
+  __TEXT.__chain_starts: 0x24
+  __DATA.__gxf_data: 0x8160
   __DATA.__data: 0x17d28
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x7a8

   __DATA.__zerofill: 0x5a778
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 417
-  Symbols:   168
+  Symbols:   172
   CStrings:  235
 
Symbols:
+ _agfUPPLRegisterPageCount
+ _agfUPPLRegisterPages
+ _gClientFunctions
+ _premap_ranges
Functions:
~ sub_fffffc000000b82c : 316 -> 332
~ sub_fffffc000000c27c -> sub_fffffc000000c28c : 11152 -> 11068
~ sub_fffffc000003433c -> sub_fffffc00000342f8 : 384 -> 388
~ sub_fffffc0000038de4 -> sub_fffffc0000038da4 : 432 -> 468
~ sub_fffffc0000038f94 -> sub_fffffc0000038f78 : 428 -> 540
~ sub_fffffc000003ce70 -> sub_fffffc000003cec4 : 324 -> 332
CStrings:
+ "Oct 13 2026 20:59:44"
- "Aug 13 2026 21:28:28"
```
