## Diagnostic-8340

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8340.appex/Diagnostic-8340`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1307.2.4.0.0
-  __TEXT.__text: 0xb854
+1307.40.66.0.0
+  __TEXT.__text: 0xb8bc
   __TEXT.__auth_stubs: 0x8c0
   __TEXT.__objc_stubs: 0x860
   __TEXT.__objc_methlist: 0x2fc
   __TEXT.__const: 0x110
   __TEXT.__gcc_except_tab: 0x2b4
   __TEXT.__oslogstring: 0xb85
-  __TEXT.__cstring: 0x1cda
+  __TEXT.__cstring: 0x1ce6
   __TEXT.__objc_classname: 0x4e
   __TEXT.__objc_methname: 0x9f4
   __TEXT.__objc_methtype: 0x147
   __TEXT.__unwind_info: 0x228
   __DATA_CONST.__const: 0x178
-  __DATA_CONST.__cfstring: 0x1080
+  __DATA_CONST.__cfstring: 0x10a0
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10

   - /usr/lib/updaters/libSavageUpdater_iOS.dylib
   Functions: 308
   Symbols:   208
-  CStrings:  546
+  CStrings:  547
 
Functions:
~ sub_100007af8 : 936 -> 952
~ sub_100008ca8 -> sub_100008cb8 : 1148 -> 1236
CStrings:
+ "SessionUUID"
```
