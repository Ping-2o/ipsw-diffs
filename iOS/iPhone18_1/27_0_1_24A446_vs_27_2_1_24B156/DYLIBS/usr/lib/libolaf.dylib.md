## libolaf.dylib

> `/usr/lib/libolaf.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 193.0.0.0.0
-  __TEXT.__text: 0x252b88
+  __TEXT.__text: 0x252bc4
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x3a268
   __TEXT.__gcc_except_tab: 0x8b70

   __AUTH_CONST.__weak_auth_got: 0x40
   __AUTH_CONST.__auth_got: 0x3e0
   __AUTH.__data: 0x150
-  __DATA.__data: 0x594d8
+  __DATA.__data: 0x60
   __DATA.__bss: 0x100c
   __DATA.__common: 0x200
-  __DATA_DIRTY.__data: 0x541f9
+  __DATA_DIRTY.__data: 0xad669
   __DATA_DIRTY.__common: 0x22d20
   __DATA_DIRTY.__bss: 0x393e8
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
Functions:
~ ____ZN4gnss15GnssAdaptDevice17Ga06_01ReportPvtmE11e_Gnm_Error16s_Gnm_AppNavData_block_invoke.14 : 14848 -> 14892
~ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN4gnss6SvInfoEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m : 136 -> 144
~ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN4gnss6SvInfoEEEPS3_EEvRT_T0_S8_S8_ : 252 -> 260
CStrings:
+ "Oct  8 2026"
- "Aug  8 2026"
```
