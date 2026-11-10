## livefiles_hfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_hfs.dylib`

```diff

-751.0.0.0.0
-  __TEXT.__text: 0x3d4d8
+753.42.1.0.0
+  __TEXT.__text: 0x3d9a4
   __TEXT.__const: 0x4e60
-  __TEXT.__oslogstring: 0x5ed7
+  __TEXT.__oslogstring: 0x5fd3
   __TEXT.__cstring: 0x270a
   __TEXT.__unwind_info: 0x6d8
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libSystem.B.dylib
   Functions: 677
   Symbols:   646
-  CStrings:  751
+  CStrings:  756
 
Functions:
~ _VerifyHeader : 212 -> 224
~ _hfs_swap_BTNode : 3168 -> 3444
~ _hfs_swap_HFSPlusBTInternalNode : 4888 -> 4912
~ _hfs_vnop_setxattr : 3008 -> 3616
~ _RotateLeft : 960 -> 992
~ _DeleteRecord : 284 -> 380
~ _DeleteOffset : 88 -> 268
CStrings:
+ "DeleteOffset: index %u >= numRecords %u."
+ "DeleteRecord: index %u >= numRecords %u."
+ "hfs_UNswap_BTNode: initial record at bad offset (0x%04X)\n"
+ "hfs_setxattr: orphan overflow attr record vol=%s %d,%s\n"
+ "hfs_swap_BTNode: initial record at bad offset (0x%04X)\n"
```
