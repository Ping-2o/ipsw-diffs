## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

```diff

-3288.2.1.0.0
+3288.42.1.0.0
   __TEXT.__const: 0x94c
-  __TEXT.__cstring: 0x4ff24
-  __TEXT_EXEC.__text: 0x153504
+  __TEXT.__cstring: 0x50305
+  __TEXT_EXEC.__text: 0x1541bc
   __TEXT_EXEC.__auth_stubs: 0x2360
   __DATA.__data: 0x754
-  __DATA.__bss: 0xd88
+  __DATA.__bss: 0xd00
   __DATA_CONST.__mod_init_func: 0x10
   __DATA_CONST.__mod_term_func: 0x10
-  __DATA_CONST.__const: 0x6890
+  __DATA_CONST.__const: 0x6898
   __DATA_CONST.__kalloc_type: 0x5440
   __DATA_CONST.__kalloc_var: 0x2bc0
   __DATA_CONST.__assert: 0x14
   __DATA_CONST.__auth_got: 0x11b0
   __DATA_CONST.__got: 0x158
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 2396
+  Functions: 2399
   Symbols:   0
-  CStrings:  6953
+  CStrings:  6967
 
CStrings:
+ "%s:%d: %s Cannot decompress data from inode %lld on a sealed volume\n"
+ "%s:%d: %s Defrag run time %llu.%03llumSec, reallocated %llu blocks in %llu extents across %llu dstreams, finished with error %d\n"
+ "%s:%d: %s Detected a hole on a sealed volume at offset %lld in %lld\n"
+ "%s:%d: %s Failed to invalidate and push %llu:%llu for ino %llu, err %d\n"
+ "%s:%d: %s IP base %lld:%lld is not free in the bitmap! error %d isallocated %d\n"
+ "%s:%d: %s IP bm base %lld:%lld is not free in the bitmap! error %d isallocated %d\n"
+ "%s:%d: %s Invalid residency reason %d, out of bounds\n"
+ "%s:%d: %s Missing dstream %lld of inode %lld on a sealed volume\n"
+ "%s:%d: %s apfs_rr: cleanup 0 failed to decrement head split crypto refcount (ret %d) \n"
+ "%s:%d: %s apfs_rr: cleanup first failed to decrement crypto refcount (ret %d) \n"
+ "%s:%d: %s apfs_rr: cleanup last failed to decrement crypto refcount (ret %d) \n"
+ "%s:%d: %s applied dstream workaround inode %llu\n"
+ "%s:%d: %s failed to remove extents iteratively\n"
+ "%s:%d: %s find_new_metadata(old_block_count %lld, resize_block_count %lld)\n"
+ "%s:%d: %s ino %llu '%s' cp_open() failed with EILSEQ\n"
+ "%s:%d: %s ino %llu, failed to get region covering %llu+%zu, error %d\n"
+ "%s:%d: %s punch hole dstream and file size mismatch: [%llu, %llu); ino %llu, file_size %llu, dstream exists %d, size %llu, alloced_size %llu\n"
+ "%s:%d: %s request flags: 0x%llx type: 0x%llx min_size: %lld: max_age %lld desired_amt: %lld (age-for-urgency: %lld, requesting uid: %d, search_start_time: %llu)\n"
+ "12111112122212121111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111"
+ "12111112122212121112111222222222222222221111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111111111111111111112"
+ "2026/10/13"
+ "20:57:28"
+ "3288.42.1"
+ "FX defrag: Number of dstreams with at least one reallocated extent"
+ "Oct 13 2026"
+ "apfs-3288.42.1"
+ "btree_node_compact"
+ "decrement_dstream_id_for_deletion"
- "%s:%d: %s Defrag run time %llu.%03llumSec, reallocated %llu blocks in %llu extents, finished with error %d\n"
- "%s:%d: %s Failed to invalidate %llu:%llu for ino %llu, err %d\n"
- "%s:%d: %s Failed to msync for ino %llu\n"
- "%s:%d: %s find_new_metadata(available_block_index %lld, nxr_st->resize_block_count %lld)\n"
- "%s:%d: %s request flags: 0x%llx type: 0x%llx min_size: %lld: max_age %lld desired_amt: %lld (age-for-urgency: %lld, requesting uid: %d)\n"
- "%s:%d: container is locked to be loadable only by pid <%d>, refusing request to load the container by pid <%d> device = %s\n"
- "1211111212221212111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111"
- "1211111212221212111211122222222222222222111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111112111111111111111111111111111111111111111111111111111111111111111111111111111111111111111112"
- "2026/08/13"
- "21:26:23"
- "3288.2.1"
- "Aug 13 2026"
- "apfs-3288.2.1"
- "decrement_dstream_id_for_deletion_ex"
```
