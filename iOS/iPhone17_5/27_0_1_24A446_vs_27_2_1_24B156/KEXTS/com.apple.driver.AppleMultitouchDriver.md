## com.apple.driver.AppleMultitouchDriver

> `com.apple.driver.AppleMultitouchDriver`

```diff

-10100.44.0.0.0
+10110.4.0.0.0
   __TEXT.__const: 0x1a8
-  __TEXT.__cstring: 0x22d5
-  __TEXT.__os_log: 0x3a70
-  __TEXT_EXEC.__text: 0x1d240
-  __TEXT_EXEC.__auth_stubs: 0x6a0
+  __TEXT.__cstring: 0x22d4
+  __TEXT.__os_log: 0x3acf
+  __TEXT_EXEC.__text: 0x1d350
+  __TEXT_EXEC.__auth_stubs: 0x680
   __DATA.__data: 0xca
   __DATA.__common: 0x270
   __DATA.__bss: 0x11

   __DATA_CONST.__const: 0x43d8
   __DATA_CONST.__kalloc_var: 0x280
   __DATA_CONST.__kalloc_type: 0x8c0
-  __DATA_CONST.__auth_got: 0x350
-  __DATA_CONST.__got: 0x128
+  __DATA_CONST.__auth_got: 0x340
+  __DATA_CONST.__got: 0x130
   Functions: 546
   Symbols:   0
-  CStrings:  542
+  CStrings:  543
 
Functions:
~ sub_fffffff00923a488 -> sub_fffffff009276ed8 : 204 -> 244
~ sub_fffffff00923a554 -> sub_fffffff009276fcc : 204 -> 244
~ sub_fffffff00923a6dc -> sub_fffffff00927717c : 120 -> 56
~ sub_fffffff00923a768 -> sub_fffffff0092771c8 : 104 -> 8
~ __ZN31AppleMultitouchDeviceUserClient11injectFrameEi : 372 -> 456
~ __ZN31AppleMultitouchDeviceUserClient12initWithTaskEP4taskPvjP12OSDictionary : 704 -> 740
~ sub_fffffff00923c62c -> sub_fffffff0092790a4 : 232 -> 252
~ __ZN31AppleMultitouchDeviceUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 448 -> 660
CStrings:
+ "12111112122212121111111111111222222222111111122"
+ "[HID] [%s] [Error] %s::%s [0x%llx] Could not allocate _injectionMemory in clientMemoryForType\n"
- "121111121222121211111111111112222222221111112122"
```
