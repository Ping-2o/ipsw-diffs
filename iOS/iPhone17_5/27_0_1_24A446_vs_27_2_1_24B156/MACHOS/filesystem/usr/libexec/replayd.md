## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-740.63.1.2.0
-  __TEXT.__text: 0xb929c
+765.15.2.0.0
+  __TEXT.__text: 0xbaecc
   __TEXT.__auth_stubs: 0x1920
-  __TEXT.__objc_stubs: 0xf0e0
-  __TEXT.__objc_methlist: 0x73c8
+  __TEXT.__objc_stubs: 0xf340
+  __TEXT.__objc_methlist: 0x74b0
   __TEXT.__const: 0x3e4
   __TEXT.__gcc_except_tab: 0xfc8
-  __TEXT.__objc_methname: 0x15d0c
-  __TEXT.__oslogstring: 0x1634a
-  __TEXT.__cstring: 0x17b48
+  __TEXT.__objc_methname: 0x15f9b
+  __TEXT.__oslogstring: 0x16809
+  __TEXT.__cstring: 0x17d26
   __TEXT.__objc_classname: 0xa44
-  __TEXT.__objc_methtype: 0x4403
-  __TEXT.__unwind_info: 0x2310
-  __DATA_CONST.__const: 0x2ab8
-  __DATA_CONST.__cfstring: 0x5ce0
+  __TEXT.__objc_methtype: 0x4410
+  __TEXT.__unwind_info: 0x2378
+  __DATA_CONST.__const: 0x2b00
+  __DATA_CONST.__cfstring: 0x5d40
   __DATA_CONST.__objc_classlist: 0x278
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x130

   __DATA_CONST.__auth_got: 0xca0
   __DATA_CONST.__got: 0xc88
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x11310
-  __DATA.__objc_selrefs: 0x4690
-  __DATA.__objc_ivar: 0xd7c
+  __DATA.__objc_const: 0x113b8
+  __DATA.__objc_selrefs: 0x4728
+  __DATA.__objc_ivar: 0xd88
   __DATA.__objc_data: 0x18b0
   __DATA.__data: 0xe54
   __DATA.__bss: 0x268

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3639
+  Functions: 3683
   Symbols:   802
-  CStrings:  7343
+  CStrings:  7391
 
Symbols:
+ __exit
- _notify_register_check
CStrings:
+ " [ERROR] %{public}s:%d RPConnectionManager: SIGTERM cleanup window elapsed, exiting cleanly"
+ " [ERROR] %{public}s:%d Unable to re-latch capture display on session reuse: no current FBS layout identity"
+ " [ERROR] %{public}s:%d failed to create SCPreviewSession for previewID=%@"
+ " [ERROR] %{public}s:%d failed to stop own session"
+ " [ERROR] %{public}s:%d maximum preview count (%lu) reached for previewContent=%d"
+ " [ERROR] %{public}s:%d missing or malformed previewID in previewConfig (got %@)"
+ " [ERROR] %{public}s:%d no client found for %{public}@, nothing to stop"
+ " [ERROR] %{public}s:%d no preview found for previewID=%@ content=%d"
+ " [ERROR] %{public}s:%d pickerDidCancel rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d pickerDidDismiss rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d previewID=%@ already exists for previewContent=%d"
+ " [ERROR] %{public}s:%d stopAllActiveClients: caller pid %d lacks system recording entitlement, scoping stop to its own sessions"
+ " [ERROR] %{public}s:%d unsupported previewContent=%d"
+ " [INFO] %{public}s:%d %p hasStarted=%d micDeviceUID=%@ micCaptureSessionCount=%ld"
+ " [INFO] %{public}s:%d Stopped recording due to display change, outputURL: %@ error: %@"
+ " [INFO] %{public}s:%d didStart=%d pid=%d attributionSource=%ld micDeviceUID=%@"
+ " [INFO] %{public}s:%d skipping invalid pid=%@"
+ " [INFO] %{public}s:%d stop own session success"
+ "-[RPConnectionManager handleSIGTERMWithExitAfter:exitBlock:]"
+ "-[RPConnectionManager handleSIGTERMWithExitAfter:exitBlock:]_block_invoke"
+ "-[RPConnectionManager pickerDidCancel:forStream:]"
+ "-[RPConnectionManager pickerDidDismiss:forStream:isCancelled:]"
+ "-[RPConnectionManager stopAllActiveClients]"
+ "-[RPRecordingManager stopActiveSessionForClientWithBundleID:]"
+ "-[RPRecordingManager stopActiveSessionForClientWithBundleID:]_block_invoke"
+ "-[RPSession handleCaptureDisplayIDUpdate:]"
+ "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withAuditToken:micDeviceUID:]"
+ "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withPID:attributionSource:micDeviceUID:]"
+ "@\"NSUUID\""
+ "RPConnectionManager: stopAllActiveClients completed for the calling client only"
+ "RPConnectionManager: stopAllActiveClientsInternal"
+ "RPConnectionManager: stopAllActiveClientsInternal completed"
+ "RPEnableEdgeLightDev"
+ "T@\"NSUUID\",R,N,V_previewID"
+ "T@\"SCClipSession\",&,V_clipSession"
+ "VB40@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32"
+ "VB40@0:8@16@24@32"
+ "_cameraPreviewSessions"
+ "_displayFrameOnCameraPreviewSessions:"
+ "_displayFrameOnScreenPreviewSessions:"
+ "_micDeviceUID"
+ "_screenPreviewSessions"
+ "_screenStreamsLock"
+ "_stopAndRemoveAllPreviewSessions"
+ "clipSession"
+ "com.screenCaptureKit.previewUpdateQueue.%@"
+ "currentLayout"
+ "edgeLightDevOverrideActive"
+ "elapsedClipBufferingSeconds"
+ "getStreamWithStreamID:"
+ "getStreamsSnapshot"
+ "handleCaptureDisplayIDUpdate:"
+ "handleSIGTERM"
+ "handleSIGTERMWithExitAfter:exitBlock:"
+ "initSystemTapWithFormat:excludePIDs:"
+ "initWithUUIDString:"
+ "previewID"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "removeStreamWithStreamID:"
+ "setClipSession:"
+ "setStream:withStreamID:"
+ "showRemoteAlertOfType:application:bundleID:"
+ "stopActiveSessionForClientWithBundleID:"
+ "stopAllActiveClientsInternal"
+ "unknown"
+ "updateMicrophoneCaptureDidStart:withAuditToken:micDeviceUID:"
+ "updateMicrophoneCaptureDidStart:withPID:attributionSource:micDeviceUID:"
+ "v24@?0@\"NSError\"8Q16"
+ "v32@0:8d16@?24"
+ "v40@0:8B16i20q24@32"
+ "v60@0:8B16{?=[8I]}20@52"
- " [ERROR] %{public}s:%d failed to start previewContent=%d alreadyStarted=%d"
- " [ERROR] %{public}s:%d failed to stop previewContent=%d alreadyStopped=%d"
- " [INFO] %{public}s:%d %p hasStarted=%d micCaptureSessionCount=%ld"
- " [INFO] %{public}s:%d Stopped recording due to display change"
- " [INFO] %{public}s:%d didStart=%d pid=%d attributionSource=%ld"
- "-[RPSession setUpFrontBoardServices]_block_invoke"
- "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withAuditToken:]"
- "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withPID:attributionSource:]"
- "@\"SCPreviewSession\""
- "RPConnectionManager: stopAllActiveClients completed"
- "RPDaemonRun_block_invoke"
- "VB32@0:8@\"NSString\"16@\"NSString\"24"
- "VB32@0:8@16@24"
- "Vv32@0:8@\"NSString\"16@\"NSString\"24"
- "_cameraPreviewSession"
- "_screenPreviewSession"
- "com.screenCaptureKit.previewUpdateQueue"
- "dismissReactionsTipForApplication:bundleID:"
- "showReactionsTipForApplication:bundleID:"
- "updateMicrophoneCaptureDidStart:withAuditToken:"
- "updateMicrophoneCaptureDidStart:withPID:attributionSource:"
- "v32@0:8B16i20q24"
- "valueForKey:"
```
