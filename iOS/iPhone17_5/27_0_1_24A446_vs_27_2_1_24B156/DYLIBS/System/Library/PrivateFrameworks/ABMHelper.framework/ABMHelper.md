## ABMHelper

> `/System/Library/PrivateFrameworks/ABMHelper.framework/ABMHelper`

```diff

-1585.0.0.0.0
-  __TEXT.__text: 0x1cb514
+1594.0.0.0.0
+  __TEXT.__text: 0x1cba10
   __TEXT.__init_offsets: 0x160
   __TEXT.__objc_methlist: 0x14
   __TEXT.__const: 0x7100
-  __TEXT.__gcc_except_tab: 0x210fc
-  __TEXT.__cstring: 0x85c7
-  __TEXT.__oslogstring: 0xdb32
-  __TEXT.__unwind_info: 0x7010
+  __TEXT.__gcc_except_tab: 0x21120
+  __TEXT.__cstring: 0x85df
+  __TEXT.__oslogstring: 0xdc17
+  __TEXT.__unwind_info: 0x7018
   __TEXT.__eh_frame: 0x138
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
-  Functions: 4299
-  Symbols:   6773
-  CStrings:  2766
+  Functions: 4300
+  Symbols:   6774
+  CStrings:  2771
 
Symbols:
+ __ZN17KernelPCIABPTrace25disableKernelTraceBuffersEv
Functions:
+ __ZN17KernelPCIABPTrace25disableKernelTraceBuffersEv
~ __ZN17KernelPCIABPTrace21updateTraceState_syncEN8dispatch13group_sessionE : 32 -> 128
~ __ZN17KernelPCIABPTrace25deregisterWithKernel_syncEv : 320 -> 420
~ __ZN17KernelPCIABPTrace23registerWithKernel_syncEv : 2060 -> 2188
~ __ZN17KernelPCIABPTrace16setProperty_syncEN8dispatch13group_sessionERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEESA_ : 1260 -> 1272
~ ____ZNK3ctu20SharedSynchronizableI5TraceE20execute_wrapped_syncIZN17KernelPCIABPTrace4initENSt3__112basic_stringIcNS5_11char_traitsIcEENS5_9allocatorIcEEEENS5_8weak_ptrIN3abm19BasebandTracingTaskEEEN8dispatch5groupEE3$_0EEDTclsr8dispatchE4syncLDnEclsr3stdE7forwardIT_Efp_EEEOSJ__block_invoke : 172 -> 184
~ __ZZN8dispatch5asyncIZNK3ctu20SharedSynchronizableI5TraceE15execute_wrappedIZN17KernelPCIABPTrace5startENS_5groupENS1_2cf11CFSharedRefIK14__CFDictionaryEEE3$_0EEvOT_EUlvE_EEvP16dispatch_queue_sNSt3__110unique_ptrISE_NSJ_14default_deleteISE_EEEEENUlPvE_8__invokeESO_ : 316 -> 328
~ __ZN5Trace6createERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEENS0_8weak_ptrIN3abm19BasebandTracingTaskEEEN8dispatch5groupE : 2504 -> 2520
CStrings:
+ "Disable kernel trace buffers returned [0x%x]"
+ "Enable kernel trace buffers returned [0x%x]"
+ "Failed to create kernel trace object to disable kernel trace buffers"
+ "Failed to start kernel trace interface to disable kernel trace buffers"
+ "kernel.pci.bin.disable"
```
