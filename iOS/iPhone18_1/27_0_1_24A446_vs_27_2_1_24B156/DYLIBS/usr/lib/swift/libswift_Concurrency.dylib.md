## libswift_Concurrency.dylib

> `/usr/lib/swift/libswift_Concurrency.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-6.4.0.31.5
-  __TEXT.__text: 0x75dbc
+6.4.2.1.9
+  __TEXT.__text: 0x75dec
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x30aa
   __TEXT.__cstring: 0x2266

   __TEXT.__swift_as_entry: 0x2b4
   __TEXT.__swift_as_ret: 0x34c
   __TEXT.__swift_as_cont: 0x500
-  __TEXT.__unwind_info: 0x2c18
+  __TEXT.__unwind_info: 0x2c10
   __TEXT.__eh_frame: 0x6608
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __AUTH_CONST.__auth_got: 0x8b0
   __AUTH.__data: 0xa70
   __DATA.__data: 0xf0
-  __DATA.__bss: 0x43a0
+  __DATA.__bss: 0x4380
   __DATA.__common: 0x88
-  __DATA_DIRTY.__data: 0x470
+  __DATA_DIRTY.__data: 0x468
   __DATA_DIRTY.__bss: 0x19d0
   __DATA_DIRTY.__common: 0x70
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/system/libdispatch.dylib
-  Functions: 3046
-  Symbols:   5829
+  Functions: 3045
+  Symbols:   5827
   CStrings:  217
 
Symbols:
- __ZL19dispatchEnqueueFunc
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
Functions:
~ _swift_dispatchEnqueueGlobal : 180 -> 172
~ _swift_dispatchEnqueueMain : 32 -> 24
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
~ _$ss16AsyncMapSequenceV8IteratorV4next9isolationq_SgScA_pSgYi_tYa7FailureQzYKFTY1_ : 528 -> 532
~ _$ss23AsyncCompactMapSequenceV8IteratorV4next9isolationq_SgScA_pSgYi_tYa7FailureQzYKFTY1_ : 532 -> 536
~ _$sScs8IteratorV4next9isolationxSgScA_pSgYi_tYaq_YKFTY2_ : 128 -> 132
~ _swift_task_enqueueOnDispatchQueue : 32 -> 24
~ _$ss22AsyncDropFirstSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY0_ : 692 -> 696
~ _$ss22AsyncDropFirstSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY2_ : 996 -> 1004
~ _$ss22AsyncDropWhileSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY0_ : 720 -> 724
~ _$ss22AsyncDropWhileSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY4_ : 956 -> 964
~ _$ss19AsyncFilterSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY1_ : 512 -> 516
~ _$ss19AsyncFilterSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY4_ : 160 -> 164
~ _$ss20AsyncFlatMapSequenceV8IteratorV4next9isolation7ElementQy_SgScA_pSgYi_tYa7FailureQzYKFTY0_ : 1100 -> 1104
~ _$ss20AsyncFlatMapSequenceV8IteratorV4next9isolation7ElementQy_SgScA_pSgYi_tYa7FailureQzYKFTY2_ : 1468 -> 1480
~ _$ss20AsyncFlatMapSequenceV8IteratorV4next9isolation7ElementQy_SgScA_pSgYi_tYa7FailureQzYKFTY4_ : 724 -> 732
~ _$ss20AsyncFlatMapSequenceV8IteratorV4next9isolation7ElementQy_SgScA_pSgYi_tYa7FailureQzYKFTY8_ : 1528 -> 1540
~ _$ss20AsyncFlatMapSequenceV8IteratorV4next9isolation7ElementQy_SgScA_pSgYi_tYa7FailureQzYKFTY11_ : 560 -> 568
~ _$ss19AsyncPrefixSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY0_ : 560 -> 564
~ _$ss24AsyncPrefixWhileSequenceV8IteratorV4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTY2_ : 512 -> 516
CStrings:
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
- "Initialized count set to greater than specified capacity."
```
