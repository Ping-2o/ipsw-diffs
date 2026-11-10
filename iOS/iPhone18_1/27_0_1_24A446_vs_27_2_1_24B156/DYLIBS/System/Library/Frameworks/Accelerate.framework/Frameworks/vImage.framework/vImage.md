## vImage

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage`

```diff

-650.0.1.0.0
-  __TEXT.__text: 0x2aab10
+650.40.4.0.0
+  __TEXT.__text: 0x2ab008
   __TEXT.__delay_stubs: 0x780
   __TEXT.__delay_helper: 0x5a4
   __TEXT.__const: 0x9a330
-  __TEXT.__cstring: 0x6acb
+  __TEXT.__cstring: 0x6bc0
   __TEXT.__unwind_info: 0x2500
   __TEXT.__eh_frame: 0x26b8
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0xbf88
   __AUTH_CONST.__auth_got: 0x330
-  __DATA.__data: 0x50
+  __DATA.__data: 0x4c
   __DATA.__common: 0x8
   __DATA.__bss: 0x10
   __DATA_DIRTY.__data: 0x118

   - /usr/lib/libcompression.dylib
   Functions: 3446
   Symbols:   4385
-  CStrings:  404
+  CStrings:  406
 
Functions:
~ _ReduceToCoreFormats : 1468 -> 1564
~ _Deepmap2DecodeDefaultScratchBufferSize : 136 -> 196
~ _Deepmap2DecodeDefault : 1232 -> 1188
~ _Deepmap2DecodePalette : 672 -> 676
~ _vConvert_RGB16UtoRGBA16U : 1508 -> 1504
~ _ImagePaletteCreate : 596 -> 644
~ _vImageDeepmapEncodeCreateBuffer : 484 -> 516
~ _vImageDeepmapDecodeStreamProcess : 1532 -> 1584
~ _EncodeImageLossless : 280 -> 332
~ _EncodeImagePalette : 420 -> 444
~ _DecodeImageLossless : 264 -> 332
~ _DecodeImagePalette : 300 -> 324
~ _EncodeImageDefault : 1056 -> 1152
~ _DecodeImageDefaultScratchBufferSize : 80 -> 136
~ _DecodeImageDefault : 1100 -> 1180
~ _EncodeImageWithMehtod : 684 -> 708
~ _vImageDeepmap2EncodeCreateBuffer : 484 -> 516
~ _vImageDeepmap2DecodeStreamProcess : 1472 -> 1504
~ _Deepmap2EncodeLossless : 388 -> 416
~ _Deepmap2DecodeDefaultRawBufferSize : 68 -> 136
~ _Deepmap2DecodeDefaultMaxRawBufferSize : 28 -> 100
~ _Deepmap2EncodeDefault : 1064 -> 1160
~ _Deepmap2BuildPalette : 908 -> 948
~ _Deepmap2EncodePalette : 616 -> 660
~ _ConvertIndexedToDirect : 1168 -> 1360
CStrings:
+ "650.40.4"
+ "kvImagePrintDiagnosticsToConsole: vImageConverter: indexed color table has more entries than srcFormat->bitsPerComponent can address."
+ "kvImagePrintDiagnosticsToConsole: vImageConverter: indexed destination color table has more than 256 entries."
- "650.0.1"
```
