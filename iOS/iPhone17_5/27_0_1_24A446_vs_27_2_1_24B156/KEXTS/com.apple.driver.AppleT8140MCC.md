## com.apple.driver.AppleT8140MCC

> `com.apple.driver.AppleT8140MCC`

```diff

-127.0.3.0.0
+127.40.5.0.0
   __TEXT.__const: 0x50
-  __TEXT.__cstring: 0x5ba5
-  __TEXT.__os_log: 0x266f
-  __TEXT_EXEC.__text: 0x16f88
+  __TEXT.__cstring: 0x5c11
+  __TEXT.__os_log: 0x26cb
+  __TEXT_EXEC.__text: 0x170ac
   __TEXT_EXEC.__auth_stubs: 0x5b0
   __DATA.__data: 0x83e8
   __DATA.__common: 0x1f0

   __DATA_CONST.__got: 0xc0
   Functions: 573
   Symbols:   0
-  CStrings:  926
+  CStrings:  930
 
Functions:
~ sub_fffffff00980b288 -> sub_fffffff00984ad68 : 304 -> 340
~ ____ZN25AppleMemCacheControllerV230getDataCollectionMemDescriptorEv_block_invoke : 248 -> 404
~ __ZN20AppleMCCUserClientV219clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 600 -> 700
CStrings:
+ "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
+ "%s:%d: No data collection buffer available\n\n"
+ "Failed to create mem descriptor for shared data queue\n"
+ "No data collection buffer available\n"
```
