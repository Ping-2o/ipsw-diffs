## trustd

> `/usr/libexec/trustd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-62460.2.3.0.0
-  __TEXT.__text: 0x59ce0
-  __TEXT.__auth_stubs: 0x23d0
-  __TEXT.__objc_stubs: 0x3380
-  __TEXT.__objc_methlist: 0xe14
-  __TEXT.__const: 0xde40
+62460.40.78.0.0
+  __TEXT.__text: 0x5be04
+  __TEXT.__auth_stubs: 0x2490
+  __TEXT.__objc_stubs: 0x3520
+  __TEXT.__objc_methlist: 0xe2c
+  __TEXT.__const: 0xde20
   __TEXT.__dlopen_cstrs: 0x54
   __TEXT.__objc_classname: 0x1b4
-  __TEXT.__objc_methname: 0x2fd4
+  __TEXT.__objc_methname: 0x312e
   __TEXT.__objc_methtype: 0xc6b
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_typeref: 0x17

   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
   __TEXT.__gcc_except_tab: 0xae0
-  __TEXT.__cstring: 0x6115
-  __TEXT.__oslogstring: 0x5d96
-  __TEXT.__unwind_info: 0x1020
-  __DATA_CONST.__const: 0x3de0
-  __DATA_CONST.__cfstring: 0x5da0
+  __TEXT.__cstring: 0x6650
+  __TEXT.__oslogstring: 0x6120
+  __TEXT.__unwind_info: 0x1050
+  __DATA_CONST.__const: 0x3f38
+  __DATA_CONST.__cfstring: 0x6740
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x78
-  __DATA_CONST.__objc_intobj: 0x120
+  __DATA_CONST.__objc_intobj: 0x138
   __DATA_CONST.__objc_arraydata: 0x100
   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_dictobj: 0x190
-  __DATA_CONST.__auth_got: 0x11f8
-  __DATA_CONST.__got: 0x930
+  __DATA_CONST.__auth_got: 0x1258
+  __DATA_CONST.__got: 0x908
   __DATA_CONST.__auth_ptr: 0x18
-  __DATA.__objc_const: 0x1750
-  __DATA.__objc_selrefs: 0xe60
-  __DATA.__objc_ivar: 0xd0
+  __DATA.__objc_const: 0x1780
+  __DATA.__objc_selrefs: 0xed0
+  __DATA.__objc_ivar: 0xd4
   __DATA.__objc_data: 0x5b8
   __DATA.__data: 0x400
-  __DATA.__bss: 0x520
+  __DATA.__bss: 0xc50
   - /System/Library/Frameworks/CFNetwork.framework/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 1204
-  Symbols:   889
-  CStrings:  2214
+  Functions: 1214
+  Symbols:   897
+  CStrings:  2335
 
Symbols:
+ _CCDigest
+ _CCDigestGetOutputSize
+ _NSURLErrorFailingURLErrorKey
+ _SecKeyVerifySignature
+ ___strlcpy_chk
+ _dirname_r
+ _freeaddrinfo
+ _getaddrinfo
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA1
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA256
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA384
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA1
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA256
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA384
+ _pread
+ _readdir
+ _rename
+ _sqlite3_close_v2
+ _statfs
+ _strcmp
+ _strlcpy
+ _strncmp
+ _strstr
+ _sysctl
+ _time
+ _unlink
- _CC_SHA224
- _CC_SHA256
- _CC_SHA384
- _CC_SHA512
- _CFPropertyListCreateXMLData
- _CFURLCreateDataAndPropertiesFromResource
- _CSSMOID_ECDSA_WithSHA1
- _CSSMOID_ECDSA_WithSHA256
- _CSSMOID_ECDSA_WithSHA384
- _CSSMOID_SHA1WithRSA
- _CSSMOID_SHA256WithRSA
- _CSSMOID_SHA384WithRSA
- _NSURLErrorFailingURLStringErrorKey
- _SecDigestCreate
- _inet_pton
- _readdir_r
- _xpc_transaction_begin
- _xpc_transaction_end
CStrings:
+ "%02x"
+ "%s-wal"
+ "%s.%d.tmp"
+ "(%d) %s"
+ "-corruption-log.plist"
+ "-wal"
+ "0.4.0.194112.1.4"
+ "0.4.0.194112.1.5"
+ ":memory:"
+ "B16@?0^{__OpaqueSecDbConnection={__CFRuntimeBase=QAQ}^{__OpaqueSecDb}BBQBiB^{__CFError}{?=CCCCBBiiiiiCI[4[160c]][128c][256c][192c]}^{sqlite3}i^{__CFArray}}8"
+ "CAIssuerSSRFBadPortAlt"
+ "CAIssuerSSRFBadPortSvc"
+ "OCSPExtraSingleResponses"
+ "OCSPResponse: duplicate certID, preferring revoked"
+ "OCSPResponse: more than %d certificates in the response"
+ "OCSPResponse: no request to scope the validity interval to"
+ "OCSPSSRFBadPortAlt"
+ "OCSPSSRFBadPortSvc"
+ "SELECT count(*) FROM cert"
+ "SELECT count(*) FROM genp"
+ "SELECT count(*) FROM inet"
+ "SELECT count(*) FROM keys"
+ "SecDBCheckCorrupted integrity_check returned %{public}s"
+ "SecDbCorruptionLog: close failed (%{darwin.errno}d)"
+ "SecDbCorruptionLog: log at %{public}@ was unusable, starting over"
+ "SecDbCorruptionLog: path too long: %{public}@"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to create %s"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to rename into place"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to set protection class"
+ "SecDbCorruptionLog: unable to serialize log for %{public}@"
+ "SecDbCorruptionLog: write failed (%{darwin.errno}d)"
+ "SecDbHandleCorrupt: Tried to write corruption marker %{public}s but one already exists"
+ "SecDbSecDbProcessCorruptionMarker: found corruption marker %{public}s"
+ "TB,V_responseTooLarge"
+ "Unable to get data from \"%s\": %@"
+ "UseSSRFLiteralEnforcement"
+ "UseSSRFPortEnforcement"
+ "_responseTooLarge"
+ "_setPrivacyProxyFailClosedForUnreachableHosts:"
+ "appendFormat:"
+ "bytesRead"
+ "cancel"
+ "com.apple.trustd.analytics"
+ "completed"
+ "corruptionError"
+ "couldNotRun"
+ "dataWithContentsOfFile:options:error:"
+ "dataWithContentsOfURL:options:error:"
+ "dbDeleted"
+ "dbMtime"
+ "dbSize"
+ "dbUnlinkFailed"
+ "detectedAt"
+ "entries"
+ "episode"
+ "failingSQL"
+ "file:"
+ "fileChangeCounter"
+ "fileExistsAtPath:"
+ "fileHeader"
+ "fileURLWithPath:"
+ "filesAtDetection"
+ "genp"
+ "hadPriorIOFailure"
+ "headerFirst32Hex"
+ "immutable=1"
+ "inet"
+ "integerValue"
+ "integrityCheck"
+ "integrityCheckRowsTotal"
+ "integrityCheckStatus"
+ "kern.osversion"
+ "keys"
+ "lastWriterSqliteVersion"
+ "magicValid"
+ "markerAgeSeconds"
+ "markerOutcome"
+ "migrationFailure"
+ "noSuccessor"
+ "ocspcache"
+ "ocspcache: no request to scope the cache write to, not caching"
+ "openErrmsg"
+ "openFailed"
+ "openResultCode"
+ "origin"
+ "osVersion"
+ "pageSize"
+ "postMortem"
+ "preexisted"
+ "priorLogUnreadable"
+ "ranAndFailed"
+ "readErrno"
+ "remediation"
+ "removeObjectsInRange:"
+ "resetOnly"
+ "response does not answer the request, not caching"
+ "response for taskId %@ from %@ passed %d bytes, cancelling"
+ "responseTooLarge"
+ "schemaVersionNew"
+ "schemaVersionOld"
+ "sec_count_all_with_access_groups_id"
+ "setQuery:"
+ "setResponseTooLarge:"
+ "sizeInPages"
+ "skipping SSRF-denied destination for %@ (buckets 0x%x)"
+ "sqlite3: (%d) %{public}s"
+ "sqliteCorrupt"
+ "sqliteErrmsg"
+ "sqliteExtendedCode"
+ "sqliteLog"
+ "sqliteNotADb"
+ "sqliteSystemErrno"
+ "staleWalLeftBehind"
+ "stringByAppendingString:"
+ "stringWithCapacity:"
+ "tableRowCounts"
+ "totalEpisodes"
+ "unknown"
+ "uptimeAtDetection"
+ "versionValidFor"
+ "volumeFreeBytes"
+ "volumeReadOnly"
+ "walBytesNotCounted"
+ "walSize"
+ "writeFailed"
+ "written"
- "B16@?0^{__OpaqueSecDbConnection={__CFRuntimeBase=QAQ}^{__OpaqueSecDb}BBQBiB^{__CFError}^{sqlite3}i^{__CFArray}}8"
- "SecDBCheckCorrupted integrity_check returned %s"
- "SecDbHandleCorrupt: Tried to write corruption marker %s but one already exists"
- "SecDbSecDbProcessCorruptionMarker: found corruption marker %s"
- "Unable to get data from \"%s\": error %ld"
```
