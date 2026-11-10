## libcompression.dylib

> `/usr/lib/libcompression.dylib`

```diff

-212.0.1.0.0
-  __TEXT.__text: 0x64e0c
-  __TEXT.__const: 0x76e91
-  __TEXT.__cstring: 0x2ec
+212.42.1.0.0
+  __TEXT.__text: 0x646ec
+  __TEXT.__const: 0x76ec1
+  __TEXT.__cstring: 0x2f9
   __TEXT.__unwind_info: 0x710
   __TEXT.__eh_frame: 0x450
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x10a0
   __AUTH_CONST.__auth_got: 0x188
-  __DATA.__data: 0x480
+  __DATA.__data: 0x420
   __DATA.__common: 0x1200
+  __DATA_DIRTY.__data: 0x60
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/liblzma.5.dylib
-  Functions: 547
-  Symbols:   719
-  CStrings:  49
+  Functions: 548
+  Symbols:   720
+  CStrings:  50
 
Symbols:
+ _getDecoderTable
Functions:
~ _lzvnDecode : 1136 -> 1132
~ _lzfseDecode : 5032 -> 5040
~ _zlibDecodeBufferSafe : 2596 -> 1824
~ _ProcessCommands : 2540 -> 2616
~ _SafeProcessCommands : 2828 -> 2808
~ _lz4raw_decode_buffer : 164 -> 172
~ _zlibDecodeBuffer : 2352 -> 1580
~ _readHuffmanTable : 2052 -> 1036
~ _DecodeLiteralBlockSwitch : 520 -> 532
~ _DecodeDistanceBlockSwitch : 468 -> 480
~ _DecodeCommandBlockSwitch : 444 -> 456
~ _zlib_stream_get_encode_state_size : 52 -> 12
~ _lzbitmap_decode : 2224 -> 2372
~ _lzbitmap_decode_buffer : 52 -> 60
+ _getDecoderTable
~ _msh_decode_buffer : 3660 -> 3760
~ _lz24_decode_buffer : 696 -> 712
~ _SafeDecodeCommandBlockSwitch : 800 -> 812
~ _SafeDecodeLiteralBlockSwitch : 880 -> 892
~ _SafeDecodeDistanceBlockSwitch : 824 -> 836
~ _smb_lznt1_decode_buffer : 524 -> 516
~ _lzfse_decode_buffer_output_size : 504 -> 500
~ _lzfse_decode_buffer_iboot : 2956 -> 2968
~ _lzfse_decode_lzvn_block_iboot : 460 -> 456
~ _smb_lz77h_decode_buffer : 1308 -> 1300
~ _lzbitmap_fast_decode : 1528 -> 1376
~ _lzbitmap_fast_decode_buffer : 52 -> 60
~ _smb_lz77_decode_buffer : 476 -> 468
~ _lzx_decode_buffer : 2292 -> 2300
~ _lzma_stream_end : 56 -> 60
CStrings:
+ "BLOCK_SWITCH"
```
