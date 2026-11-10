## lifs

> `/System/Library/Extensions/lifs.kext/lifs`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`

```diff

-974.0.13.0.2
-  __TEXT.__os_log: 0x1f5d
-  __TEXT.__cstring: 0x29fa
-  __TEXT.__const: 0x338
-  __TEXT_EXEC.__text: 0x2099c
+974.40.12.0.0
+  __TEXT.__os_log: 0x1ffc
+  __TEXT.__cstring: 0x2a13
+  __TEXT.__const: 0x348
+  __TEXT_EXEC.__text: 0x20e08
   __TEXT_EXEC.__auth_stubs: 0xfb0
   __DATA.__data: 0x578
   __DATA.__common: 0x138

   __DATA_CONST.__kalloc_type: 0xe40
   __DATA_CONST.__kalloc_var: 0xf0
   __DATA_CONST.__auth_got: 0x7d8
-  __DATA_CONST.__got: 0x80
+  __DATA_CONST.__got: 0x88
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 460
-  Symbols:   1227
-  CStrings:  520
+  Functions: 463
+  Symbols:   1232
+  CStrings:  524
 
Symbols:
+ _lifs_abandon_sync_req
+ _lifs_abandon_sync_req._os_log_fmt
+ _lifs_create_endio_context.kalloc_type_view_1061
+ _lifs_destroy_endio_context.kalloc_type_view_1080
+ _lifs_fsync_internal.kalloc_type_view_4068
+ _lifs_io_lock_override_owned
+ _lifs_koio_done.kalloc_type_view_2157
+ _lifs_mount.kalloc_type_view_669
+ _lifs_mount.kalloc_type_view_695
+ _lifs_mount.kalloc_type_view_873
+ _lifs_mount.kalloc_type_view_923
+ _lifs_mount.kalloc_type_view_927
+ _lifs_mount.kalloc_type_view_931
+ _lifs_reclaim_done.kalloc_type_view_5071
+ _lifs_setfsattr_done.kalloc_type_view_3995
+ _lifs_submit_io.kalloc_type_view_2139
+ _lifs_submit_koio.kalloc_type_view_2179
+ _lifs_unmount.kalloc_type_view_1082
+ _lifs_unmount_dangling_all.kalloc_type_view_1578
+ _lifs_unmount_dangling_all.kalloc_type_view_1599
+ _lifs_unmount_dangling_thread.kalloc_type_view_1551
+ _lifs_update_attrs_if_needed
+ _lifs_update_attrs_if_needed._os_log_fmt
+ _lifs_vnop_readdir.kalloc_type_view_3102
+ _lifs_vnop_readdir.kalloc_type_view_3104
+ _lifs_vnop_readdir.kalloc_type_view_3199
+ _lifs_vnop_readdir.kalloc_type_view_3201
+ _lifs_vnop_reclaim.kalloc_type_view_5115
+ _lifs_vnop_reclaim.kalloc_type_view_5169
+ _lifs_vnop_strategy.kalloc_type_view_2273
+ _lifs_vnop_strategy_done.kalloc_type_view_1867
- _lifs_create_endio_context.kalloc_type_view_991
- _lifs_destroy_endio_context.kalloc_type_view_1010
- _lifs_fsync_internal.kalloc_type_view_3952
- _lifs_koio_done.kalloc_type_view_2087
- _lifs_mount.kalloc_type_view_670
- _lifs_mount.kalloc_type_view_697
- _lifs_mount.kalloc_type_view_876
- _lifs_mount.kalloc_type_view_926
- _lifs_mount.kalloc_type_view_930
- _lifs_mount.kalloc_type_view_934
- _lifs_reclaim_done.kalloc_type_view_4955
- _lifs_setfsattr_done.kalloc_type_view_3879
- _lifs_submit_io.kalloc_type_view_2069
- _lifs_submit_koio.kalloc_type_view_2109
- _lifs_unmount.kalloc_type_view_1085
- _lifs_unmount_dangling_all.kalloc_type_view_1581
- _lifs_unmount_dangling_all.kalloc_type_view_1602
- _lifs_unmount_dangling_thread.kalloc_type_view_1554
- _lifs_vnop_readdir.kalloc_type_view_3013
- _lifs_vnop_readdir.kalloc_type_view_3015
- _lifs_vnop_readdir.kalloc_type_view_3110
- _lifs_vnop_readdir.kalloc_type_view_3112
- _lifs_vnop_reclaim.kalloc_type_view_4999
- _lifs_vnop_reclaim.kalloc_type_view_5053
- _lifs_vnop_strategy.kalloc_type_view_2203
- _lifs_vnop_strategy_done.kalloc_type_view_1797
Functions:
~ _lifs_mount_request : 764 -> 760
~ _lifs_req_callback_thread : 460 -> 456
+ _lifs_abandon_sync_req
~ _lifs_vnop_write : 1244 -> 1252
~ _lifs_vnop_read : 536 -> 544
~ _lifs_vnop_mnomap : 404 -> 492
~ _lifs_vnop_open : 1076 -> 1160
~ _lifs_vnop_close : 1016 -> 1052
~ _lifs_vnop_getattr : 1060 -> 1232
~ _lifs_vnop_pagein : 1004 -> 1012
~ _lifs_vnop_pageout : 1184 -> 1192
+ _lifs_update_attrs_if_needed
~ _lifs_io_strategy_thread : 460 -> 456
~ _lifs_endio_thread : 436 -> 424
~ _lifs_mount : 2204 -> 2180
~ _lifs_unmount : 1288 -> 1284
~ _lifs_getattr : 984 -> 988
~ _lifs_lookup_node : 176 -> 172
~ _lifs_create_node_ext : 1476 -> 1472
~ _lifs_pathconf : 136 -> 132
~ _lifs_set_io_lock_override : 100 -> 108
+ _lifs_io_lock_override_owned
~ _lifs_apply_cache_action : 348 -> 404
CStrings:
+ "\"%s: io_lock_override is already set for lnode %p by thread %p\" @%s:%d"
+ "\"%s: io_lock_override is not set for lnode %p\" @%s:%d"
+ "%s: attributes update returned error %d"
+ "%s: caught a signal, giving up with %d"
+ "%s: got %d from msleep, giving up with EIO"
+ "%s: request %llu was claimed by a reply while giving up with error %d, awaiting that reply's completion"
+ "%s: timed out, giving up with %d"
+ "111222222222222222122222222222222212111111111222222222222222211212222222112221"
+ "lifs_abandon_sync_req"
+ "lifs_update_attrs_if_needed"
- "\"%s: override is already set for lnode %p io_lock\" @%s:%d"
- "\"%s: override is not set for lnode %p io_lock\" @%s:%d"
- "%s: caught a signal, returning %d"
- "%s: got %d from msleep, returning EIO"
- "%s: timed out, returning %d"
- "11122222222222222222222222222222222222222222222222332222122222222222222212111111111222222222222222211212222222112221"
```
