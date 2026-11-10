## wifip2pd

> `/usr/libexec/wifip2pd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`

```diff

-885.85.4.1.0
-  __TEXT.__text: 0x5e52f8
-  __TEXT.__auth_stubs: 0x5240
-  __TEXT.__objc_stubs: 0x4720
-  __TEXT.__objc_methlist: 0x1bf4
-  __TEXT.__const: 0x404b0
-  __TEXT.__swift5_typeref: 0xd367
+887.9.0.0.0
+  __TEXT.__text: 0x5e74a0
+  __TEXT.__auth_stubs: 0x51d0
+  __TEXT.__objc_stubs: 0x4740
+  __TEXT.__objc_methlist: 0x1bfc
+  __TEXT.__const: 0x40510
+  __TEXT.__swift5_typeref: 0xd389
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__cstring: 0xfa28
-  __TEXT.__oslogstring: 0x226bc
-  __TEXT.__constg_swiftt: 0x103f4
-  __TEXT.__swift5_fieldmd: 0x169d8
+  __TEXT.__cstring: 0xfa2a
+  __TEXT.__oslogstring: 0x227ec
+  __TEXT.__constg_swiftt: 0x1041c
+  __TEXT.__swift5_fieldmd: 0x169f0
   __TEXT.__swift5_types: 0x12e0
   __TEXT.__swift5_builtin: 0x1748
-  __TEXT.__swift5_reflstr: 0x14bd9
+  __TEXT.__swift5_reflstr: 0x14be9
   __TEXT.__swift5_assocty: 0x2d78
   __TEXT.__swift5_proto: 0x3074
   __TEXT.__objc_classname: 0x10f7
   __TEXT.__objc_methtype: 0x2347
   __TEXT.__swift5_protos: 0x108
-  __TEXT.__swift5_capture: 0x7fc8
-  __TEXT.__objc_methname: 0xa305
+  __TEXT.__swift5_capture: 0x804c
+  __TEXT.__objc_methname: 0xa3a5
   __TEXT.__swift5_mpenum: 0x1a8
-  __TEXT.__swift_as_entry: 0x204
-  __TEXT.__swift_as_ret: 0x168
-  __TEXT.__swift_as_cont: 0x5f4
-  __TEXT.__unwind_info: 0x107e8
-  __TEXT.__eh_frame: 0x1e664
-  __DATA_CONST.__const: 0x39f28
+  __TEXT.__swift_as_entry: 0x20c
+  __TEXT.__swift_as_ret: 0x174
+  __TEXT.__swift_as_cont: 0x608
+  __TEXT.__unwind_info: 0x108a8
+  __TEXT.__eh_frame: 0x1e8cc
+  __DATA_CONST.__const: 0x3a048
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x178
-  __DATA_CONST.__auth_got: 0x2928
+  __DATA_CONST.__auth_got: 0x28f0
   __DATA_CONST.__got: 0x1030
   __DATA_CONST.__auth_ptr: 0x7950
-  __DATA.__objc_const: 0xac90
-  __DATA.__objc_selrefs: 0x16e0
+  __DATA.__objc_const: 0xacd8
+  __DATA.__objc_selrefs: 0x16e8
   __DATA.__objc_data: 0x1920
-  __DATA.__data: 0x15068
+  __DATA.__data: 0x150a8
   __DATA.__bss: 0x5e2d0
-  __DATA.__common: 0xb88
+  __DATA.__common: 0xba0
   - /System/Library/Frameworks/Combine.framework/Combine
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24922
-  Symbols:   2319
-  CStrings:  5523
+  Functions: 24977
+  Symbols:   2310
+  CStrings:  5533
 
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s7Network10NWEndpointO20customMetadataForKey3key10Foundation4DataVSgSS_tF
+ _$s7Network10NWEndpointO23setCustomMetadataForKey3key8metadataySS_10Foundation4DataVSgtF
- _$s7Network10NWEndpointO9txtRecordAA11NWTXTRecordVSgvg
- _$s7Network11NWTXTRecordV5EntryO4data10Foundation4DataVSgvg
- _$s7Network11NWTXTRecordV5EntryOMa
- _$s7Network11NWTXTRecordV5EntryOMn
- _$s7Network11NWTXTRecordV8getEntry3forAC0D0OSgSS_tF
- _$s7Network11NWTXTRecordVMa
- _$s7Network11NWTXTRecordVMn
- _nw_endpoint_copy_txt_record
- _nw_endpoint_set_txt_record
- _nw_txt_record_create_dictionary
- _nw_txt_record_remove_key
- _nw_txt_record_set_key
CStrings:
+ "%s APPLE80211_M_DRIVER_AVAILABLE available: %d reason: %d"
+ "%s APPLE80211_M_DRIVER_AVAILABLE with powerOn false"
+ "39560fb64ab1823caabcb302e047e336192172f1433a3c04366bcce83e7fac0c"
+ "4688814b00b466eed6007c60019ef308af473cc0b53b915a7c6ec4141d75d9f7"
+ "AWDL did wake"
+ "AWDL interface was re-created (system awake: %{bool}d)"
+ "AWDL will sleep"
+ "Infra did wake"
+ "Infra will sleep"
+ "NAN interface was re-created (system awake: %{bool}d)"
+ "Stamping system wake time during interface recovery (missed didWake)"
+ "WiFiP2P-887.9 Oct 08 2026 00:10:25"
+ "_inFlightDPSetupCount"
+ "com.apple.tvairplayd"
+ "dynamicSDB clearing switch on termination (%s)"
+ "updatedNANDPInProgress:"
+ "{\n  \"1eb7fed92efef1591ffc3b0637ac07172f2656f0a4e03dec82d3db2ea0640b1a\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"77970d61377215093dbf9e177ccbb6e8159dd020da675f134303d7cda4a5552b\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"efcedd6cc47f00088bd08dcb5337f91d51a0398fc20aeb3dd684054448504928\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"19647773753a9d89b325915d23398f050b26b01d76fc175a97c884d13833000a\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"f505a59fa1b99a40889373d89698865450ba8c32b8f0839a7b7b5ecc94523cb5\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Timeout\": 120,\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"eafb577cb967c4e68ea11e5285bb50dee2dbe29c84bfd95cea3e6ad6c67b0710\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"d41654545b3306ac74889d0716a0f9b001fa46b2599e69e446d193f8f4c2e9d4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"53defc80096c7800a883df4a15c606deba6f968d0f649e8d4b154d08a5ef44a3\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"9b33c6812b9b8045b6f593755fc816d359c1d411c2dabee3e534d081cbffe249\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"Timeout\": 120\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"ab3a7040828e3850b216a2a6c0d02095ecc483f8ba7df2d2c23317f3d5db269a\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"967bf1bd98570fbb7d4f4d791dc9baa737e7b310ba6ecbf1417df19df0d10b90\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"e960724cd4eef6411ee04b30c0d9f6bb7d6c844c9c87c00fcb5748c36f6c3cbd\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"271173fdb4aaecfcb459455cf2363d64a25d6ddce8222d79c5e2b99b5842d540\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
+ "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"3235ae7cf5a88344be687a44b789d56d69419c4f79fe1997f0a7497dd75669e5\": {\n      \"WiFiAwareServices\": {\n        \"8a4f65707e2a877535b92981e38ad25ff95a43b2119dec0f076ee648c37f01ad\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"90f205c543dde484824dde4d8b5cd5870abeb2b980f6ee11c0fc0da73e35440a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"cc565060e7df70f664598d784ebf6219bddd6aa7c7b2fc60c4cddb8da3c23eca\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e4d475602038a850b53089c269d7b55528261dc4dc0e138015b9cc7a35e343eb\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"d3d92a6cdd1a9af8c167c1b2d6a2416dec0afb70fb1a2cfac1e128b09b1824fe\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"95cfba45ac6220837118454b05635ac4afa9a2e37e34dc27d839802e59f87689\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"e05cb98d2188c447de56832bf94b1e5cefb93d28a23904d6ffe57e88dd6a5c98\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"ce39a3132b244feaef11b605fc4a31b4a809d31ce7eb1a495a9286d6e8c574d0\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"276ead32d494faab608a3d8dcbccf6afc58901d84064ff4098bd3a7bbac943d7\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"f29119d4688cd27df97ec0741f72652c8caa5f8efbc59851d87949ac8b51b6c5\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"b201198f6c51ce6e5532c9fc5737327eb6d90ca706770090718794f4fdcc5fb7\": {\n      \"WiFiAwareServices\": {\n        \"b06d70ec7f9a72ac29bcfb811950d3f5b2825e2c957ec8024202b88ceee1f3e7\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"1c267ac69ae67a5a8e610321eb6c56871260848762d2ff6ce59e0f8286503a9d\": {\n      \"WiFiAwareServices\": {\n        \"f8226b66f4994c02f8bf11c6b9e24dd322813596838951bd7c4de6cc4ba03b4f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"a42573134b9ef4d2fc28a1dd075db80fd42d563c68414c00f45a6f924c31f4c7\": {\n      \"WiFiAwareServices\": {\n        \"ef6aec73f14fb72a6831acee28e557e40ed14ae26c017d352b6fa73088df2185\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6370317363a3f87cea4ada93220125ade59ac1dd8787c0bf5b038fa4dcceabc1\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"a6d34a7dfde9f38254b1c904c31d8b2513e8e14f1f60c0506f00b16b4f6becb0\": {\n      \"WiFiAwareServices\": {\n        \"b06d70ec7f9a72ac29bcfb811950d3f5b2825e2c957ec8024202b88ceee1f3e7\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"438999a063de6b6e5c80ee485b1f4762b6dbd1e529f16895e40773725eb7fdc2\": {\n      \"WiFiAwareServices\": {\n        \"f8226b66f4994c02f8bf11c6b9e24dd322813596838951bd7c4de6cc4ba03b4f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
+ "ℹ️ No %s configured for %s policy: %s"
- "3bdd21e5283593aefb6605925afdc83dfd5b1b86494fe5595b25629f16bf114b"
- "Driver interface was re-created"
- "RSSI: %s"
- "WiFiP2P-885.85.4.1 Sep 18 2026 22:09:14"
- "a2d35bf8101ed72be57b26e20beada1f77f72fac75b8acf8fed3e6a78fe7db1d"
- "nan_event: %s APPLE80211_M_DRIVER_AVAILABLE with powerOn false %d"
- "setTXTRecordEntry failed: NWEndpoint(nw) returned nil, endpoint may be in inconsistent state"
- "{\n  \"6c3c55d5c3cbc7beef912af640ec26c0ff0e7ca1537b2884a2d36ae9f7d5ad64\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"23d79b2b14c5d7c164ab376c55dc74781fcdaa6f18adcac259491f5ff47726d1\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"8f2c214eb2c91b8e85f7944bb91f2e2273f6fc53b477f8a82385640c2be65a9c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"79179b50a1708698ce727049487d30e97b648d1e5147bcc6bb1449b5f663b1b4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"b2ddb00c18aaa1576a154184e0cae512c383a57f4e7188e624f3d067c68f81dd\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"c991fce9a203487b967289177e9f414e4f455617c03aa844def3d0e047dc14bb\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"8f9547ecc9cd27e39443a29bc9ba027a93d357e4a2fb12ece1642ff85b7cae8f\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"21e9279e206ccce2c5235a1ab2ad88ef45c662913af19e657f1c312869307a2d\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"62187df34191d9b44b8630cf3dd2d0318823a8a672628d337c880edeebef5233\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"cd7db2fc26f9d1f825b3763a131435bf4d2056f28e177d9ddc9443c3a258f15e\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"56ec178ffb9fe3da83b332e17bb5df97a99c3cb1e586afc6b0e853a11523324b\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"a07a62568168d811a9f74316d922f715dfa2ecfc9fdf0b4c0ff3d20c26940cef\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"47179cf9dc95ccaf274c6e5a9bf70e23d37d411e52c9150b0f5950f9cc57bb8c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
- "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"79eb1900e9034bfdca1042eaa7861c54bff4f2b3e1fae032d0969ff9052b3852\": {\n      \"WiFiAwareServices\": {\n        \"19fbbaf83462bd64ac78d3eabdff5f0a19bc515b789bc8d1a527e07e2a34c32a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"3a14143bd72674547e1b3bb43632a9836056dc8a0d57c0587356f00a96e25b4f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"a8378af38cec6de49457be39b57cb31abd034c882cd906f576b51ca32e58628a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"cb23e818e52c370b7b149d672708a3f10379a5d8e1baa2686d6a84796a6e3608\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6c68fed2056d97f3273bf8b7b1fd9ae7ed0f3af8fb507446d60ce003581bf5a3\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"188002802b007094ad3e15c13e6742101aafa3ea8feba49f2d18bad3ab390c0c\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"7ad7cf1f9066fdb09f73da2c1f8c32662e2670a2f6e83ca9551560cdd1c81348\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"0b13651e0aea4aa69ce89350378253bb603314eadbd35956a3a620949cebcaf3\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"ac4bc5449689c62096fca6f165611682e9b3b6972fe15902db3b6c4079abbe15\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e92d8b213635e2f7162460279b196e82450ac6fdd1538619c2f222e235ea5756\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"155f716be8a708513031f1364c4d8273727c1adb9ddf830948ac58522624680f\": {\n      \"WiFiAwareServices\": {\n        \"381c7d43f9a070771237c5abd2f082963747c262beaef9987e11b37e35c5be4f\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"f36dc0f71e5615bf4abf2a29cd20408d3d5bb0a72fc47ca9f5503c79d69aa3d9\": {\n      \"WiFiAwareServices\": {\n        \"3ea312a1fe319a22cff8b4846d8b5f83403090df00f17da1dfcaa8da5597838a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"210048c6fa7af27f73831ea6e1e5ebd3fc5c5bb6a9c8d2eca3a4beb5a2b108e2\": {\n      \"WiFiAwareServices\": {\n        \"f20ff891907cfcfe3505a12c7600d6ad6641cd8ab28dca7fd21b51326cd614ac\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"bf678a91199689052b08d303c699a42b27c8c1e55894edfaf8536a26ba1d4ab6\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"eb8cd1c93f30b2c637b979f0d2a0fb0dd2e17d6d1b4c048c466a9fcd03eaa6c9\": {\n      \"WiFiAwareServices\": {\n        \"381c7d43f9a070771237c5abd2f082963747c262beaef9987e11b37e35c5be4f\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"d65289bbf4d109eda2319a62894afc6aa4c2f3a55a8cd077f8e1e33f4dc7192c\": {\n      \"WiFiAwareServices\": {\n        \"3ea312a1fe319a22cff8b4846d8b5f83403090df00f17da1dfcaa8da5597838a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
```
