## agx_b000

> `Firmware/agx/armfw_g18p.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cc14
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3cc68
+  __TEXT.__gxf_code: 0x5120
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1068
+  __TEXT.__const: 0x10ad
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
   __TEXT.__cstring: 0x23fc
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
   Functions: 416
-  Symbols:   168
+  Symbols:   172
   CStrings:  237
 
Symbols:
+ _agfUPPLRegisterPageCount
+ _agfUPPLRegisterPages
+ _gClientFunctions
+ _premap_ranges
Functions:
~ sub_fffffc000000b3d8 : 316 -> 332
~ sub_fffffc000000be28 -> sub_fffffc000000be38 : 11152 -> 11068
~ sub_fffffc0000033f9c -> sub_fffffc0000033f58 : 384 -> 388
~ sub_fffffc0000038a44 -> sub_fffffc0000038a04 : 432 -> 468
~ sub_fffffc0000038bf4 -> sub_fffffc0000038bd8 : 428 -> 540
~ sub_fffffc000003cad0 -> sub_fffffc000003cb24 : 324 -> 332
CStrings:
+ "Oct 13 2026 21:07:13"
- "Aug 13 2026 21:35:55"
```
