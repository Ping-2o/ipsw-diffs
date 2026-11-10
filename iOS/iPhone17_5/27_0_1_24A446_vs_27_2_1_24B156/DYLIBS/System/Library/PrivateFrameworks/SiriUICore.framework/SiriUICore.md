## SiriUICore

> `/System/Library/PrivateFrameworks/SiriUICore.framework/SiriUICore`

```diff

-3600.9.2.0.0
-  __TEXT.__text: 0x2b95c
+3605.4.1.0.0
+  __TEXT.__text: 0x2ba54
   __TEXT.__objc_methlist: 0x3448
-  __TEXT.__const: 0x7f172
-  __TEXT.__cstring: 0x87ea
-  __TEXT.__oslogstring: 0xd3d
+  __TEXT.__const: 0x68982
+  __TEXT.__cstring: 0x885b
+  __TEXT.__oslogstring: 0xd80
   __TEXT.__gcc_except_tab: 0x380
   __TEXT.__dlopen_cstrs: 0x5a
   __TEXT.__ustring: 0x14

   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x640
+  __AUTH_CONST.__auth_got: 0x648
   __AUTH.__objc_data: 0xec8
   __AUTH.__data: 0x28
   __DATA.__objc_ivar: 0x74c

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1151
-  Symbols:   2548
-  CStrings:  374
+  Functions: 1152
+  Symbols:   2549
+  CStrings:  377
 
Symbols:
+ _AFIsWaffleiron
+ _precalcSUICILNoise3DTextureASTC5x5
- _precalcSUICILNoise3DTexture
Functions:
~ +[SUICIntelligentLightLayer createNoiseTextureWithDevice:commandQueue:] : 428 -> 496
~ -[SUICEdgeLightMaskMetalLayer _updateForUIIdiom] : 704 -> 816
+ -[SUICIntelligentLightLayer _drawFrame:].cold.1
CStrings:
+ "!\"ASTC5x5 3D texture failed to allocate\""
+ "%s Failed to create compressed noise texture. Requires Apple3 GPU."
+ "+[SUICIntelligentLightLayer createNoiseTextureWithDevice:commandQueue:]"
```
