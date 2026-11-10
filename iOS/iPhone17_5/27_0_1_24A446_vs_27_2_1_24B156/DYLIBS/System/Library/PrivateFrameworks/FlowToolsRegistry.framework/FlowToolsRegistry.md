## FlowToolsRegistry

> `/System/Library/PrivateFrameworks/FlowToolsRegistry.framework/FlowToolsRegistry`

```diff

-3600.65.34.0.0
-  __TEXT.__text: 0xa5028
+3605.31.1.11.2
+  __TEXT.__text: 0xab018
   __TEXT.__objc_methlist: 0x14
-  __TEXT.__const: 0x5828
+  __TEXT.__const: 0x5838
   __TEXT.__oslogstring: 0x1954
-  __TEXT.__cstring: 0x4d54
-  __TEXT.__swift5_typeref: 0x18b4
-  __TEXT.__constg_swiftt: 0x169c
-  __TEXT.__swift5_reflstr: 0xd14
-  __TEXT.__swift5_fieldmd: 0x16d0
-  __TEXT.__swift5_proto: 0x4cc
-  __TEXT.__swift5_types: 0x26c
+  __TEXT.__cstring: 0x5484
+  __TEXT.__swift5_typeref: 0x18c2
+  __TEXT.__constg_swiftt: 0x1680
+  __TEXT.__swift5_reflstr: 0xd24
+  __TEXT.__swift5_fieldmd: 0x16d8
+  __TEXT.__swift5_proto: 0x4c4
+  __TEXT.__swift5_types: 0x268
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_protos: 0x2c
-  __TEXT.__swift5_capture: 0x920
+  __TEXT.__swift5_capture: 0x970
   __TEXT.__swift5_assocty: 0x30
-  __TEXT.__unwind_info: 0x1ef8
-  __TEXT.__eh_frame: 0x27f0
+  __TEXT.__unwind_info: 0x1f50
+  __TEXT.__eh_frame: 0x287c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x208
+  __DATA_CONST.__const: 0x248
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x78
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x3730
+  __AUTH_CONST.__const: 0x36f0
   __AUTH_CONST.__objc_const: 0x480
-  __AUTH_CONST.__auth_got: 0xce8
+  __AUTH_CONST.__auth_got: 0xcf0
   __AUTH.__data: 0x638
-  __DATA.__data: 0x660
-  __DATA.__bss: 0x58e0
-  __DATA.__common: 0x140
+  __DATA.__data: 0x670
+  __DATA.__bss: 0x58f0
+  __DATA.__common: 0x2f0
   __DATA_DIRTY.__objc_data: 0x50
-  __DATA_DIRTY.__data: 0xf08
-  __DATA_DIRTY.__common: 0x1330
-  __DATA_DIRTY.__bss: 0x3f90
+  __DATA_DIRTY.__data: 0xf30
+  __DATA_DIRTY.__common: 0x13b0
+  __DATA_DIRTY.__bss: 0x4040
   - /System/Library/Frameworks/AppIntents.framework/AppIntents
   - /System/Library/Frameworks/CoreServices.framework/CoreServices
   - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4026
+  Functions: 4142
   Symbols:   156
-  CStrings:  530
+  CStrings:  572
 
CStrings:
+ "Control media playback across devices including pause, seek, skip, speed, repeat, shuffle, subtitles, and audio language"
+ "Control media playback across devices including pause, seek, skip, speed, repeat, shuffle, subtitles, and audio language."
+ "Create Incoming Geofence"
+ "Create Outgoing Geofence"
+ "Create an incoming geofence notification for a person at a location."
+ "Create an outgoing geofence notification for a person at a location."
+ "CreateIncomingGeofenceIntent"
+ "CreateIncomingGeofenceTool"
+ "CreateOutgoingGeofenceIntent"
+ "CreateOutgoingGeofenceTool"
+ "Crisis-support categories to look up"
+ "CrisisResourceCategory"
+ "Find Item Location"
+ "Find the location of a Find My item."
+ "FindItemLocationIntent"
+ "FindItemLocationTool"
+ "Get Crisis Resources"
+ "GetCrisisResources"
+ "GetCrisisResourcesFlowTool"
+ "ISO 8601 duration for seek operations (e.g. PT30S)"
+ "MediaPlaybackControlAction"
+ "MediaPlaybackControls"
+ "MediaPlaybackControlsFlowTool"
+ "MediaPlaybackStreamEntity"
+ "Offline lookup of verified crisis-support resources"
+ "Play a sound on a Find My item."
+ "PlayItemSoundIntent"
+ "PlayItemSoundTool"
+ "Relative playback speed qualifier (normal, faster, slower)"
+ "Resource Categories"
+ "SiriFindMyFlowTools"
+ "SiriPlaybackControlFlowTools"
+ "SiriPlaybackControlFlowTools.flowtool"
+ "SiriVideoPersonEntity"
+ "The item to find the location of"
+ "The item to play a sound on"
+ "The language to set for audio or subtitles"
+ "The location for the geofence"
+ "The media playback streams to control (fetches MediaPlaybackStreamEntity)"
+ "The numeric playback speed value (e.g. 1.5, 2.0)"
+ "The person to create a geofence for"
+ "The playback control action to perform (fetches MediaPlaybackControlAction)"
+ "The trigger condition for the geofence"
+ "The type of language setting (audio or subtitle)"
+ "Whether the geofence notification is recurring"
+ "Whether the user explicitly targeted a specific device"
+ "Whether the user needs to confirm the target stream"
+ "Whether the user needs to disambiguate between multiple streams"
+ "com.apple.siri.SiriPlaybackControlAppIntentsExtension"
+ "com.apple.siri.SiriPlaybackControlAppIntentsExtension.MediaPlaybackControlsPlaceholderAppIntent"
+ "com.apple.siri.SiriPlaybackControlFlowTools"
+ "com.apple.siri.findmy.SiriFindMyFlowTools"
+ "isTargetedDevice"
+ "needsConfirmation"
+ "needsDisambiguation"
+ "playbackControls"
+ "playbackSpeedNumber"
+ "playbackSpeedQualifier"
+ "resourceCategories"
- "A standalone tool to interactively install or update marketplace applications."
- "CrisisDialogFlowTool"
- "CrisisDialogSituation"
- "Display interactive UI for installing or updating marketplace applications with rich metadata and user interaction support. Shows app cards with artwork, ratings, reviews, and install/update buttons."
- "Handle crisis dialog"
- "Handles crisis dialog for emergency and CSAM situations"
- "Interactive Install Application"
- "InteractiveInstallApplication"
- "InteractiveInstallApplicationTool"
- "List of marketplace applications to install or update"
- "SiriAppLaunchFlowTools"
- "SiriAppLaunchFlowTools.framework"
- "The crisis or CSAM situation"
- "Whether this is an update operation"
- "_MarketplaceKit_AppIntents.DisplayableMarketplaceApplication"
- "com.apple.siri.-MarketplaceIntents-AppIntents"
- "com.apple.siri.SiriAppLaunchFlowTools"
```
