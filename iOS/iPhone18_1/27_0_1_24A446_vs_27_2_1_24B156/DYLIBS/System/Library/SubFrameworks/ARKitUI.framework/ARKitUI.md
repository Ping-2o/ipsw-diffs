## ARKitUI

> `/System/Library/SubFrameworks/ARKitUI.framework/ARKitUI`

```diff

-781.0.7.0.0
-  __TEXT.__text: 0x2b9b4
-  __TEXT.__objc_methlist: 0x2988
-  __TEXT.__const: 0x948
-  __TEXT.__oslogstring: 0x192e
-  __TEXT.__cstring: 0xdcf
+781.40.6.0.0
+  __TEXT.__text: 0x2be40
+  __TEXT.__objc_methlist: 0x2990
+  __TEXT.__const: 0x958
+  __TEXT.__oslogstring: 0x1b1f
+  __TEXT.__cstring: 0xdf2
   __TEXT.__gcc_except_tab: 0xcd8
   __TEXT.__unwind_info: 0xc20
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22c0
+  __DATA_CONST.__objc_selrefs: 0x22c8
   __DATA_CONST.__objc_superrefs: 0x138
   __DATA_CONST.__got: 0x590
   __AUTH_CONST.__const: 0x3c0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 987
-  Symbols:   2153
-  CStrings:  235
+  Functions: 989
+  Symbols:   2156
+  CStrings:  241
 
Symbols:
+ -[ARSCNView _resizeDrawableOfMetalLayer:toCoverPointSize:]
+ _ARSCNMetalLayerFromRenderLayer
+ _NSStringFromCGSize
CStrings:
+ "%{public}@ <%p>: Assigned viewLayer to session <%p>. window=%d, bounds=%@, sessionAngle=%.0f"
+ "%{public}@ <%p>: Counter-rotating %.0f -> %.0f: oldDelta=%.1f, duration=%.3f"
+ "%{public}@ <%p>: No previous angle; skipping counter-rotation for %.0f."
+ "%{public}@ <%p>: Publishing orientation swap %ld -> %ld (angle %.0f -> %.0f). baseline=%@ (has=%d), pendingRotationBaselineSize=%@, snapshotState=%ld"
+ "%{public}@ <%p>: didMoveToWindow: window=%d, bounds=%@, viewRotationAngle=%.0f, hasBaselineBounds=%d"
+ "%{public}@ <%p>: viewRotationAngle updated to %.0f (from %.0f, hasBaselineBounds %d, %s)"
+ "adopting silently"
+ "counter-rotating"
- "%{public}@ <%p>: viewRotationAngle updated to %.0f"
- "viewRotationAngle updated to %.0f"
```
