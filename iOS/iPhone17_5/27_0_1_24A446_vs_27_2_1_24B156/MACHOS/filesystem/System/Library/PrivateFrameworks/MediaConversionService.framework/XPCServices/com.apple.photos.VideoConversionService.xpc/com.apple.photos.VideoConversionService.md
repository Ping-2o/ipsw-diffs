## com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.VideoConversionService.xpc/com.apple.photos.VideoConversionService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x22538
-  __TEXT.__auth_stubs: 0xb00
-  __TEXT.__objc_stubs: 0x62e0
-  __TEXT.__objc_methlist: 0x1e94
+916.57.154.0.0
+  __TEXT.__text: 0x22a2c
+  __TEXT.__auth_stubs: 0xb20
+  __TEXT.__objc_stubs: 0x6480
+  __TEXT.__objc_methlist: 0x1edc
   __TEXT.__dlopen_cstrs: 0xbe
   __TEXT.__const: 0x1c0
   __TEXT.__gcc_except_tab: 0xb68
-  __TEXT.__objc_methname: 0x8207
-  __TEXT.__oslogstring: 0x3008
-  __TEXT.__cstring: 0x3584
+  __TEXT.__objc_methname: 0x83dd
+  __TEXT.__oslogstring: 0x30db
+  __TEXT.__cstring: 0x3899
   __TEXT.__objc_classname: 0x3d5
-  __TEXT.__objc_methtype: 0xd1b
-  __TEXT.__unwind_info: 0x7c0
+  __TEXT.__objc_methtype: 0xd26
+  __TEXT.__unwind_info: 0x7c8
   __DATA_CONST.__const: 0xc20
-  __DATA_CONST.__cfstring: 0x2760
+  __DATA_CONST.__cfstring: 0x28a0
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x68
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x590
-  __DATA_CONST.__got: 0x798
-  __DATA.__objc_const: 0x2da8
-  __DATA.__objc_selrefs: 0x1d70
-  __DATA.__objc_ivar: 0x250
+  __DATA_CONST.__auth_got: 0x5a0
+  __DATA_CONST.__got: 0x7e0
+  __DATA.__objc_const: 0x2e18
+  __DATA.__objc_selrefs: 0x1de0
+  __DATA.__objc_ivar: 0x258
   __DATA.__objc_data: 0x6e0
   __DATA.__data: 0x2a0
   __DATA.__bss: 0xc8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libperfcheck.dylib
-  Functions: 693
-  Symbols:   425
-  CStrings:  1920
+  Functions: 699
+  Symbols:   436
+  CStrings:  1952
 
Symbols:
+ _AVMetadataCommonIdentifierTitle
+ _AVMetadataCommonKeyTitle
+ _AVMetadataIdentifier3GPUserDataTitle
+ _AVMetadataIdentifierQuickTimeMetadataDisplayName
+ _AVMetadataIdentifierQuickTimeMetadataRatingUser
+ _AVMetadataIdentifierQuickTimeUserDataFullName
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_PFRadarComponent
+ _OBJC_CLASS_$_PFTapToRadarDraft
+ _PFOSVariantHasInternalDiagnostics
+ _PFTapToRadarCreateDraft
CStrings:
+ "@\"NSArray\""
+ "A video conversion stopped reporting progress, so VideoConversionService force-crashed itself. The crash report records only that deliberate crash. What the conversion and the rest of the system were stuck on is in the spindump inside the attached sysdiagnose.\n\nSource resources: %@\nSource sizes: %@\nDestination: %@\nConversion task: %@ %@\nHang detector: %@\nQueue entry: %@\nRequest reason: %@\n"
+ "PAMediaConversionServiceOptionAVMetadataIncludeRatingKey"
+ "PAMediaConversionServiceOptionAVMetadataIncludeTitleKey"
+ "PAMediaConversionServiceOptionAVMetadataRatingKey"
+ "Photos Backend Media Conversion Services"
+ "Photos Video Conversion"
+ "T@\"NSArray\",&,V_certificateChainDERData"
+ "T@\"NSString\",R,V_hangDetectionSummary"
+ "Tap-to-Radar is gathering diagnostics for the stalled conversion, staying alive %.0f s so its spindump can sample us"
+ "Unable to create output image destination of type %{public}@"
+ "Unable to open a Tap-to-Radar draft for the stalled conversion: %{public}@"
+ "VideoConversionService: video conversion made no progress for an hour"
+ "_captureVideoConversionHangDiagnosticsForQueueEntry:conversionTask:"
+ "_certificateChainDERData"
+ "_hangDetectionSummary"
+ "all"
+ "certificateChainDERData"
+ "currentStateSummary"
+ "hangDetectionSummary"
+ "initWithIdentifier:name:version:"
+ "progress %.4f unchanged for %.0f s, threshold %.0f s"
+ "setCapturesPerformanceTrace:"
+ "setCertificateChainDERData:"
+ "setClassification:"
+ "setComponent:"
+ "setDisplayReason:"
+ "setProblemDescription:"
+ "setProcessName:"
+ "setTitle:"
+ "sleepForTimeInterval:"
+ "video conversion stopped making progress"
+ "\xf0!"
- "Unable to create output image destination"
```
