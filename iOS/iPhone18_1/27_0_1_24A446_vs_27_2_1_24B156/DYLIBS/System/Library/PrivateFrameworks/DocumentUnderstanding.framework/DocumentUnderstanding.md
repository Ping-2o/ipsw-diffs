## DocumentUnderstanding

> `/System/Library/PrivateFrameworks/DocumentUnderstanding.framework/DocumentUnderstanding`

```diff

-176.3.0.1.0
-  __TEXT.__text: 0x1bc090
+192.0.0.0.0
+  __TEXT.__text: 0x1c1ee0
   __TEXT.__objc_methlist: 0x89d4
-  __TEXT.__const: 0xcc50
+  __TEXT.__const: 0xcc60
   __TEXT.__dlopen_cstrs: 0xaa
   __TEXT.__constg_swiftt: 0x5644
   __TEXT.__swift5_typeref: 0x2b3e

   __TEXT.__swift5_fieldmd: 0x3dd0
   __TEXT.__swift5_builtin: 0x140
   __TEXT.__swift5_assocty: 0x9a8
-  __TEXT.__cstring: 0xb097
+  __TEXT.__cstring: 0xb243
   __TEXT.__swift5_proto: 0x764
   __TEXT.__swift5_types: 0x388
-  __TEXT.__swift5_capture: 0xabc
+  __TEXT.__swift5_capture: 0xd5c
   __TEXT.__oslogstring: 0x58e3
   __TEXT.__swift_as_entry: 0x280
   __TEXT.__swift_as_ret: 0x2c8
   __TEXT.__swift_as_cont: 0x430
   __TEXT.__swift5_protos: 0x24
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__gcc_except_tab: 0x40f0
-  __TEXT.__unwind_info: 0x7888
-  __TEXT.__eh_frame: 0xa46c
+  __TEXT.__gcc_except_tab: 0x4178
+  __TEXT.__unwind_info: 0x78b8
+  __TEXT.__eh_frame: 0xa490
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0xc0
   __DATA_CONST.__got: 0xe30
-  __AUTH_CONST.__const: 0x9668
+  __AUTH_CONST.__const: 0x9cf8
   __AUTH_CONST.__cfstring: 0x280
   __AUTH_CONST.__objc_const: 0x8e30
   __AUTH_CONST.__weak_auth_got: 0x48
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1b88
+  __AUTH_CONST.__auth_got: 0x1b90
   __AUTH.__objc_data: 0x33b8
   __AUTH.__data: 0x3370
   __AUTH.__thread_vars: 0x30

   __DATA.__bss: 0xb259
   __DATA.__common: 0x7b1
   __DATA_DIRTY.__objc_data: 0x1ad0
-  __DATA_DIRTY.__data: 0x3078
+  __DATA_DIRTY.__data: 0x3070
   __DATA_DIRTY.__bss: 0x1c30
   __DATA_DIRTY.__common: 0x2d0
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13417
+  Functions: 13476
   Symbols:   875
-  CStrings:  1143
+  CStrings:  1153
 
CStrings:
+ "!pieces_blob.empty()"
+ "(piece_offsets_[i]) < (pieces_blob.size())"
+ "(pieces_blob.back()) == ('\\0')"
+ "(unk_id_) < (GetPieceSize())"
+ "(unk_id_) >= (0)"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/src/mmap_model_proto.cc"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1161: exception: failed to insert key: negative value"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1163: exception: failed to insert key: zero-length key"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1177: exception: failed to insert key: invalid null character"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1182: exception: failed to insert key: wrong key order"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1394: exception: failed to modify unit: too large offset"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1730: exception: failed to build double-array: invalid null character"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1732: exception: failed to build double-array: negative value"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1747: exception: failed to build double-array: wrong key order"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:798: exception: failed to resize pool: std::bad_alloc"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:914: exception: failed to build rank index: std::bad_alloc"
+ "The trie of the pieces is invalid."
+ "The trie of the reserved ids is invalid."
+ "pieces_.validate(GetPieceSize())"
+ "precompiled_charsmap is invalid."
+ "reserved_id_map_.validate(GetPieceSize())"
- "(num_nodes) < (trie_results.size())"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1111: exception: failed to insert key: negative value"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1113: exception: failed to insert key: zero-length key"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1127: exception: failed to insert key: invalid null character"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1132: exception: failed to insert key: wrong key order"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1344: exception: failed to modify unit: too large offset"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1680: exception: failed to build double-array: invalid null character"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1682: exception: failed to build double-array: negative value"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1697: exception: failed to build double-array: wrong key order"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:748: exception: failed to resize pool: std::bad_alloc"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:864: exception: failed to build rank index: std::bad_alloc"
```
