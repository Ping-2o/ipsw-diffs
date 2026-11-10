## eligibilityd

> `/usr/libexec/eligibilityd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`

```diff

-446.2.4.0.0
-  __TEXT.__text: 0x43ab4
-  __TEXT.__auth_stubs: 0x1a50
-  __TEXT.__objc_stubs: 0x2a40
-  __TEXT.__objc_methlist: 0x1f34
-  __TEXT.__const: 0x2720
-  __TEXT.__cstring: 0x7054
-  __TEXT.__swift5_typeref: 0x928
-  __TEXT.__oslogstring: 0x2768
-  __TEXT.__constg_swiftt: 0x804
-  __TEXT.__swift5_reflstr: 0x6b3
-  __TEXT.__swift5_fieldmd: 0x6cc
+446.42.1.0.0
+  __TEXT.__text: 0x45f18
+  __TEXT.__auth_stubs: 0x1a60
+  __TEXT.__objc_stubs: 0x2b80
+  __TEXT.__objc_methlist: 0x2084
+  __TEXT.__const: 0x2780
+  __TEXT.__cstring: 0x748e
+  __TEXT.__swift5_typeref: 0x962
+  __TEXT.__oslogstring: 0x28e6
+  __TEXT.__constg_swiftt: 0x860
+  __TEXT.__swift5_reflstr: 0x6d3
+  __TEXT.__swift5_fieldmd: 0x6f8
   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_assocty: 0x150
-  __TEXT.__swift5_proto: 0x220
-  __TEXT.__swift5_types: 0xe4
-  __TEXT.__objc_classname: 0x57e
-  __TEXT.__objc_methname: 0x32bf
-  __TEXT.__swift5_protos: 0x14
-  __TEXT.__objc_methtype: 0x78b
+  __TEXT.__swift5_proto: 0x224
+  __TEXT.__swift5_types: 0xe8
+  __TEXT.__objc_methname: 0x344f
+  __TEXT.__objc_classname: 0x5ce
+  __TEXT.__objc_methtype: 0x7da
+  __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_capture: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x1d8
-  __TEXT.__unwind_info: 0x1058
-  __TEXT.__eh_frame: 0xab0
-  __DATA_CONST.__const: 0x29c8
-  __DATA_CONST.__cfstring: 0x55c0
-  __DATA_CONST.__objc_classlist: 0x158
+  __TEXT.__gcc_except_tab: 0x24c
+  __TEXT.__unwind_info: 0x1110
+  __TEXT.__eh_frame: 0xad8
+  __DATA_CONST.__const: 0x2a88
+  __DATA_CONST.__cfstring: 0x5860
+  __DATA_CONST.__objc_classlist: 0x168
   __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0xc0
-  __DATA_CONST.__objc_intobj: 0x2e8
-  __DATA_CONST.__objc_arraydata: 0xc4e8
-  __DATA_CONST.__objc_arrayobj: 0x2fb8
-  __DATA_CONST.__objc_dictobj: 0xb270
-  __DATA_CONST.__auth_got: 0xd38
+  __DATA_CONST.__objc_intobj: 0x318
+  __DATA_CONST.__objc_arraydata: 0xc998
+  __DATA_CONST.__objc_arrayobj: 0x3060
+  __DATA_CONST.__objc_dictobj: 0xb630
+  __DATA_CONST.__auth_got: 0xd40
   __DATA_CONST.__got: 0x3a8
-  __DATA_CONST.__auth_ptr: 0x368
-  __DATA.__objc_const: 0x3760
-  __DATA.__objc_selrefs: 0xc00
-  __DATA.__objc_ivar: 0xcc
-  __DATA.__objc_data: 0xe20
-  __DATA.__data: 0x1300
-  __DATA.__bss: 0x2df0
+  __DATA_CONST.__auth_ptr: 0x378
+  __DATA.__objc_const: 0x3940
+  __DATA.__objc_selrefs: 0xc60
+  __DATA.__objc_ivar: 0xd0
+  __DATA.__objc_data: 0xe90
+  __DATA.__data: 0x13d0
+  __DATA.__bss: 0x2e00
   __DATA.__common: 0x30
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1402
-  Symbols:   643
-  CStrings:  2017
+  Functions: 1447
+  Symbols:   644
+  CStrings:  2079
 
Symbols:
+ _$s3XPC0A10_TYPE_BOOLs13OpaquePointerVvg
+ _MobileGestalt_get_containsCellularRadioCapability
- _swift_retain_x22
CStrings:
+ " (OVERRIDDEN)"
+ "$Actinium Countries"
+ "$Harpalus Countries"
+ "$Infinite"
+ "%s: Failed to copy input overrides plist path"
+ "%s: Failed to copy input plist path"
+ "%s: Input plist %@ doesn't exist yet: %@"
+ "%s: No forced input overrides loaded from disk: %@"
+ "%s: Process %@ not entitled to send reset all inputs message"
+ "%s: Process %@ not entitled to send reset input message"
+ "%s: Process %@ not entitled to send setInput with forced Input message"
+ "-[EligibilityEngine setInput:to:status:forced:fromProcess:withError:]"
+ "-[EligibilityEngine setInput:to:status:forced:fromProcess:withError:]_block_invoke"
+ "-[InputManager _loadInputsAtPath:withError:]"
+ "-[InputManager _loadOverridesWithError:]"
+ "-[InputManager _onQueue_saveInputs:atPath:withError:]"
+ "-[InputManager _onQueue_saveOverridesWithError:]"
+ "-[InputManager resetInput:withError:]"
+ "-[InputManager setInput:forced:withError:]"
+ "/private/var/db/eligibilityd/eligibility_input_overrides.plist"
+ "21:16:39"
+ "446.42.1"
+ "@32@0:8*16^@24"
+ "Actinium Countries"
+ "B36@0:8@\"EligibilityInput\"16B24^@28"
+ "B36@0:8@16B24^@28"
+ "B40@0:8@16*24^@32"
+ "B60@0:8Q16@24Q32B40@44^@52"
+ "CA-BC"
+ "CA-PE"
+ "CA-SK"
+ "CellularCapableDevice input is wrong data type: %s"
+ "CellularCapableDeviceInput"
+ "CellularCapableDeviceOrWatchOnChinaSKU"
+ "ChinaIneligibleBilling"
+ "ChinaSKU"
+ "Harpalus Countries"
+ "HomeAccessory"
+ "InEURegionBillingFallbackToLocationWithShortGracePeriod"
+ "Infinite"
+ "LocationInActiniumJurisdiction"
+ "LocationInEUShort"
+ "OS_ELIGIBILITY_INPUT_CELLULAR_CAPABLE_DEVICE"
+ "OS_ELIGIBILITY_STATE_DUMP_INPUT_OVERRIDES"
+ "Oct  6 2026"
+ "T@\"NSDictionary\",C,N,V_inputOverrides"
+ "TB,N,R,VcellularCapableDevice"
+ "TinLocation"
+ "[CellularCapableDeviceInput cellularCapableDevice="
+ "_TtC12eligibilityd23SystemLanguagesProvider"
+ "__ObjC.CellularCapableDeviceInput"
+ "_inputOverrides"
+ "_loadInputsAtPath:withError:"
+ "_onQueue_saveInputs:atPath:withError:"
+ "_onQueue_saveOverridesWithError:"
+ "cellularCapableDevice"
+ "com.apple.private.eligibilityd.resetAllInputs"
+ "com.apple.private.eligibilityd.resetInput"
+ "copy_eligibility_domain_input_overrides_plist_path"
+ "forced"
+ "iOSInEURegionBillingFallbackToLocationWithShortGracePeriod"
+ "iPhoneIneligibleInEUFallbackToLocation"
+ "initWithBool:status:process:"
+ "inputOverrides"
+ "overridesDebugDictionary"
+ "q"
+ "resetAllInputsWithError:"
+ "resetInput:withError:"
+ "setInput:forced:withError:"
+ "setInput:to:status:forced:fromProcess:withError:"
+ "setInputOverrides:"
+ "stringByAppendingString:"
- "%s: Failed to copy input manager plist path"
- "-[EligibilityEngine setInput:to:status:fromProcess:withError:]"
- "-[EligibilityEngine setInput:to:status:fromProcess:withError:]_block_invoke"
- "-[InputManager setInput:withError:]"
- "21:45:36"
- "446.2.4"
- "B56@0:8Q16@24Q32@40^@48"
- "CA-NS"
- "Sep 23 2026"
- "setInput:to:status:fromProcess:withError:"
```
