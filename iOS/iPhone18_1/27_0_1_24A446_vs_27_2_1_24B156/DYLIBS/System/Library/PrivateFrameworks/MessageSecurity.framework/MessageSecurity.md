## MessageSecurity

> `/System/Library/PrivateFrameworks/MessageSecurity.framework/MessageSecurity`

```diff

-341.2.1.0.0
-  __TEXT.__text: 0x4c438
+341.40.12.0.0
+  __TEXT.__text: 0x4d1a0
   __TEXT.__objc_methlist: 0x2434
-  __TEXT.__const: 0x14a4
+  __TEXT.__const: 0x14b4
   __TEXT.__gcc_except_tab: 0x78c
   __TEXT.__cstring: 0x4447
-  __TEXT.__oslogstring: 0xebc
+  __TEXT.__oslogstring: 0x100c
   __TEXT.__swift5_typeref: 0x2b0
   __TEXT.__swift5_capture: 0x10
   __TEXT.__constg_swiftt: 0x3f0

   __AUTH_CONST.__cfstring: 0x3780
   __AUTH_CONST.__objc_const: 0x4e38
   __AUTH_CONST.__auth_got: 0x948
-  __AUTH.__objc_data: 0x120
   __DATA.__objc_ivar: 0x234
-  __DATA.__data: 0x1228
+  __DATA.__data: 0xfb8
   __DATA.__bss: 0x8e0
   __DATA.__common: 0x2711
-  __DATA_DIRTY.__objc_data: 0xb88
-  __DATA_DIRTY.__data: 0xb0
+  __DATA_DIRTY.__objc_data: 0xca8
+  __DATA_DIRTY.__data: 0x320
   __DATA_DIRTY.__bss: 0x30
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswiftos.dylib
   Functions: 2221
   Symbols:   3377
-  CStrings:  608
+  CStrings:  613
 
CStrings:
+ "Invalid AES-GCM nonce length %ld, expected 12 to 16 octets"
+ "Invalid AES-GCM tag length %ld, RFC 5084 requires 12 to 16 octets"
+ "Invalid data - AES-GCM algorithm identifier carries no parameters"
+ "Invalid data - aes-ICVlen is negative or too large"
+ "aes-ICVlen %ld does not match mac length %ld"
```
