## agx_b000

> `Firmware/agx/armfw_g17p.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3bb38
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3bc34
+  __TEXT.__gxf_code: 0x5140
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1cf8
+  __TEXT.__const: 0x1d3d
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__cstring: 0x2295
   __TEXT.__init_offsets: 0x0
-  __TEXT.__chain_starts: 0x20
-  __DATA.__gxf_data: 0x80b8
+  __TEXT.__chain_starts: 0x24
+  __DATA.__gxf_data: 0x8168
   __DATA.__data: 0x17c98
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x830

   __DATA.__zerofill: 0x5b1d8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
   Functions: 433
-  Symbols:   187
+  Symbols:   191
   CStrings:  233
 
Symbols:
+ _agfUPPLRegisterPageCount
+ _agfUPPLRegisterPages
+ _gClientFunctions
+ _premap_ranges
Functions:
~ sub_fffffc000000a81c : 316 -> 332
~ sub_fffffc000000b268 -> sub_fffffc000000b278 : 10924 -> 11008
~ sub_fffffc0000032e98 -> sub_fffffc0000032efc : 384 -> 388
~ sub_fffffc0000037940 -> sub_fffffc00000379a8 : 432 -> 468
~ sub_fffffc0000037af0 -> sub_fffffc0000037b7c : 428 -> 540
~ sub_fffffc000003b9f4 -> sub_fffffc000003baf0 : 332 -> 324
CStrings:
+ "Oct 13 2026 21:07:22"
- "Aug 13 2026 21:36:12"
```
