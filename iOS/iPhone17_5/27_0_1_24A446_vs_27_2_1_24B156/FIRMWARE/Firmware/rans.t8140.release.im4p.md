## rans.t8140.release.im4p

> `Firmware/rans.t8140.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__data`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x45a0
-  __TEXT.__text: 0x1e5b5c
-  __TEXT.shared: 0xdfd4
+  __TEXT.__text: 0x1e5f64
+  __TEXT.shared: 0xe120
   __TEXT.read: 0x6f9c
-  __TEXT.__const: 0x5b68
-  __TEXT.__cstring: 0x25373
+  __TEXT.__const: 0x5d68
+  __TEXT.__cstring: 0x2537a
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x18
   __DATA._rtk_boot: 0x8000

   __DATA.__data: 0x5c00
   __DATA.__const: 0x2450
   __DATA.__gxf_data: 0x10
-  __DATA.core_globals: 0x162
+  __DATA.core_globals: 0x164
   __DATA._rtk_init_stack: 0x1000
   __DATA._rtk_irq_stack: 0x1000
   __DATA._rtk_exc_stack: 0x1000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x20faa8
-  Functions: 1976
+  __DATA.__zerofill: 0x20fad8
+  Functions: 1977
   Symbols:   0
-  CStrings:  3965
+  CStrings:  3964
 
CStrings:
+ "241.40.4"
+ "241.40.4~1100"
+ "AppleStorageFirmwareASP3-241.40.4~1100"
+ "Sanitize Failed"
+ "Sweep stuck detected - aborting - channel %d, die %d, plane %d"
+ "Sweep was aborted - rejecting continuation command"
+ "sanitize cmd drop - not init"
- "241.0.12"
- "241.0.12~645"
- "Abort Pad: Flow %u , Band: %u"
- "AppleStorageFirmwareASP3-241.0.12~645"
- "Sanitize already in progress, phase=%d"
- "Sanitize drop - device in shutdown"
- "mark invalid band %u S %u"
- "mark valid band %u M %u"
```
