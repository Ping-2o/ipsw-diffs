## MessagesSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MessagesSnippetProviderPlugin.bundle/MessagesSnippetProviderPlugin`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA.__objc_const`

```diff

-3600.47.22.11.3
-  __TEXT.__text: 0x2c844
-  __TEXT.__auth_stubs: 0x2090
-  __TEXT.__objc_stubs: 0x420
-  __TEXT.__const: 0xd18
-  __TEXT.__swift5_typeref: 0x3f9
-  __TEXT.__swift5_capture: 0x1c0
-  __TEXT.__oslogstring: 0x16f7
+3605.21.1.11.2
+  __TEXT.__text: 0x34c7c
+  __TEXT.__auth_stubs: 0x2390
+  __TEXT.__objc_stubs: 0x440
+  __TEXT.__const: 0xf48
+  __TEXT.__swift5_typeref: 0x473
+  __TEXT.__swift5_capture: 0x240
+  __TEXT.__oslogstring: 0x1ac7
   __TEXT.__objc_classname: 0x83
-  __TEXT.__objc_methname: 0x1a7
+  __TEXT.__objc_methname: 0x1b4
   __TEXT.__objc_methtype: 0x1
-  __TEXT.__constg_swiftt: 0x164
-  __TEXT.__swift5_reflstr: 0xb5
-  __TEXT.__swift5_fieldmd: 0x118
-  __TEXT.__swift5_proto: 0x2c
-  __TEXT.__swift5_types: 0x28
-  __TEXT.__swift5_assocty: 0x90
-  __TEXT.__cstring: 0x281
-  __TEXT.__swift_as_entry: 0xb8
-  __TEXT.__swift_as_ret: 0xc4
-  __TEXT.__swift_as_cont: 0xcc
-  __TEXT.__unwind_info: 0x790
-  __TEXT.__eh_frame: 0x13f0
-  __DATA_CONST.__const: 0x7d8
+  __TEXT.__constg_swiftt: 0x19c
+  __TEXT.__swift5_reflstr: 0xa5
+  __TEXT.__swift5_fieldmd: 0x12c
+  __TEXT.__swift5_proto: 0x34
+  __TEXT.__swift5_types: 0x30
+  __TEXT.__cstring: 0x2e1
+  __TEXT.__swift5_assocty: 0xc0
+  __TEXT.__swift_as_entry: 0xf4
+  __TEXT.__swift_as_ret: 0xfc
+  __TEXT.__swift_as_cont: 0x10c
+  __TEXT.__unwind_info: 0x900
+  __TEXT.__eh_frame: 0x1928
+  __DATA_CONST.__const: 0x900
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x1050
-  __DATA_CONST.__got: 0x3b0
-  __DATA_CONST.__auth_ptr: 0x400
+  __DATA_CONST.__auth_got: 0x11d0
+  __DATA_CONST.__got: 0x438
+  __DATA_CONST.__auth_ptr: 0x468
   __DATA.__objc_const: 0x148
-  __DATA.__objc_selrefs: 0x108
-  __DATA.__data: 0x4f8
-  __DATA.__bss: 0x5d0
+  __DATA.__objc_selrefs: 0x110
+  __DATA.__data: 0x5d8
+  __DATA.__bss: 0x6d0
   __DATA.__common: 0x18
   - /System/Library/Frameworks/AppIntents.framework/AppIntents
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/Intents.framework/Intents
   - /System/Library/Frameworks/UIKit.framework/UIKit
+  - /System/Library/PrivateFrameworks/AppIntentsServices.framework/AppIntentsServices
   - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
   - /System/Library/PrivateFrameworks/DialogEngine.framework/DialogEngine
   - /System/Library/PrivateFrameworks/FlowToolTypes.framework/FlowToolTypes

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 823
-  Symbols:   152
-  CStrings:  125
+  Functions: 950
+  Symbols:   153
+  CStrings:  145
 
Symbols:
+ ___stack_chk_fail
+ ___stack_chk_guard
- _swift_release_x12
CStrings:
+ "#%s %s MessageEntity has neither author nor body; skipping row"
+ "#%s %s Unsupported: Skip for current idiom: %s."
+ "#%s %s a display item is not a MobileSMS MessageEntity; leaving this response to the default pipeline"
+ "#%s %s context is nil."
+ "#%s %s no draft entities found."
+ "#%s %s no renderable MessageEntity in handle"
+ "#%s %s not on Apple TV"
+ "#%s %s responseType is not an inform"
+ "#%s %s responseType is not ask or confirm."
+ "#%s deviceIdiom is empty."
+ "#HomeDraftSnippetHandler built draft snippet model - contactName: %s, hasContent: %{bool}d"
+ "#HomeDraftSnippetHandler handling response"
+ "#HomeDraftSnippetHandler no draft value found in response items"
+ "#MessagesReadingSnippetHandler Building chained OfferFullRead"
+ "#MessagesReadingSnippetHandler Building chained OfferReply"
+ "#MessagesReadingSnippetHandler Chained %ld AddViews for silent CarPlay announce follow-up"
+ "#MessagesReadingSnippetHandler Chained pattern produced no AddViews; falling back to read-only output"
+ "#MessagesReadingSnippetHandler Failed to build chained pattern: %@. Falling back to read-only output."
+ "#MessagesReadingSnippetHandler homeAccessory OpenConversationIntent failed: %@"
+ "#MessagesReadingSnippetHandler homeAccessory first-party reading, executing OpenConversationIntent"
+ "#MessagesSendSnippetHandler %s Unsupported: Idiom is empty."
+ "#MessagesSendSnippetHandler %s Unsupported: Skip for current idiom: %s"
+ "#MessagesSendSnippetHandler %s Unsupported: Skip for non sendDraftMessageFlowTool"
+ "#SystemResponse %s didn't find a single sourceToolId: %s"
+ "#SystemResponse %s sourceTool doesn't match sendDraftMessage or editMessage"
+ "com.apple.MobileSMS"
+ "isFromSentMessageTool"
+ "messageEntities(in:)"
+ "simpleItem(for:isSentMessageEntityResponse:)"
+ "spokenPhrase"
- "#MessagesReadingSnippetHandler Chained %ld OfferReply AddViews for silent CarPlay announce reply prompt"
- "#MessagesReadingSnippetHandler Chained OfferReply produced no AddViews; falling back to read-only output"
- "#MessagesReadingSnippetHandler Failed to build chained OfferReply: %@. Falling back to read-only output."
- "#MessagesSendSnippetHandler %s Didn't find a SendDraftMessageIntent or EditMessageFlowTool"
- "#MessagesSendSnippetHandler %s Didn't find a toolId: %s"
- "#MessagesSendSnippetHandler %s Unsupported: Skip for current idiom"
- "#MessagesSendSnippetHandler %s Unsupported: Skip for system response"
- "#MessagesSendSnippetHandler %s responseType: %s"
- "#MessagesSendSnippetHandler %s values: %s"
- "isSentMessageEntityResponse(systemResponse:)"
```
