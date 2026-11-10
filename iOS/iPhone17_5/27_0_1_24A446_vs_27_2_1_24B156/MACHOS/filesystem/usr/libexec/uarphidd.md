## uarphidd

> `/usr/libexec/uarphidd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1587.2.3.0.0
-  __TEXT.__text: 0x5230
-  __TEXT.__auth_stubs: 0x570
-  __TEXT.__objc_stubs: 0xc20
-  __TEXT.__objc_methlist: 0x3dc
+1587.40.33.0.0
+  __TEXT.__text: 0x5bb0
+  __TEXT.__auth_stubs: 0x5d0
+  __TEXT.__objc_stubs: 0xda0
+  __TEXT.__objc_methlist: 0x424
   __TEXT.__const: 0x50
-  __TEXT.__cstring: 0x7e8
-  __TEXT.__objc_methname: 0xe1b
-  __TEXT.__oslogstring: 0x8be
-  __TEXT.__objc_classname: 0x6f
-  __TEXT.__objc_methtype: 0x259
-  __TEXT.__unwind_info: 0x188
-  __DATA_CONST.__const: 0x178
+  __TEXT.__gcc_except_tab: 0x9c
+  __TEXT.__cstring: 0x846
+  __TEXT.__objc_methname: 0xf00
+  __TEXT.__oslogstring: 0x96c
+  __TEXT.__objc_classname: 0x74
+  __TEXT.__objc_methtype: 0x26a
+  __TEXT.__unwind_info: 0x1a0
+  __DATA_CONST.__const: 0x1a0
   __DATA_CONST.__cfstring: 0x7e0
   __DATA_CONST.__objc_classlist: 0x18
+  __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
-  __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x2c0
+  __DATA_CONST.__objc_intobj: 0x90
+  __DATA_CONST.__auth_got: 0x2f8
   __DATA_CONST.__got: 0xc0
-  __DATA.__objc_const: 0x9a8
-  __DATA.__objc_selrefs: 0x3b0
-  __DATA.__objc_ivar: 0xc0
+  __DATA.__objc_const: 0xa08
+  __DATA.__objc_selrefs: 0x420
+  __DATA.__objc_ivar: 0xc4
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x180
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /System/Library/PrivateFrameworks/UARPKit.framework/UARPKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 148
-  Symbols:   118
-  CStrings:  373
+  Functions: 157
+  Symbols:   126
+  CStrings:  392
 
Symbols:
+ _OBJC_CLASS_$_UARPDeviceProperties
+ __Unwind_Resume
+ ___objc_personality_v0
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_retain_x25
CStrings:
+ "%s: Allow VID=0x%04x PID=0x%04x"
+ "%s: Ignore VID=0x%04x PID=0x%04x"
+ "%s: Report length %lu is too small from UARP HID Device %@"
+ "%s: VID=0x%04x PID=0x%04x has no serial number is ioreg ?!?"
+ "%s: entry has nil serial number ?! %@"
+ "%s: known entry matching dict %@"
+ "-[UARPHIDDevice deviceInactivityTimeout:]"
+ "-[UARPHIDDevice deviceNoFirmwareUpdateAvailable:]"
+ "@\"UARPDeviceProperties\""
+ "@32@0:8@16@24"
+ "@44@0:8I16@20@28@36"
+ "UARP"
+ "_deviceProperties"
+ "_uarpProperties"
+ "deviceAvailable"
+ "deviceInactivityTimeout:"
+ "deviceNoFirmwareUpdateAvailable:"
+ "deviceTransportAvailable"
+ "initWithService:hidManager:uuid:deviceProperties:"
+ "initWithTempFolder:deviceProperties:"
+ "initWithUUID:delegate:delegateQueue:deviceProperties:"
+ "noSleepWhileStaging"
+ "numPacketRetries"
+ "removeObjectsInArray:"
+ "setAppleModelNumber:"
+ "setNoSleepWhileStaging:"
+ "setNumPacketRetries:"
+ "setPowerAssertion"
+ "setProductGroup:"
+ "setProductNumber:"
+ "setSupportsCharging"
+ "setSupportsCharging:"
+ "setTimeoutActivity:"
+ "setTimeoutPacketRetry:"
+ "setTransportDomain:"
+ "setTransportForStagingOnly:"
+ "timeoutActivity"
+ "timeoutPacketRetry"
+ "transportForStagingOnly"
+ "weak self was nil"
- "%s: Allow PID=0x%04x PID=0x%04x"
- "%s: Ignore PID=0x%04x PID=0x%04x"
- "%s: known entrey matching dict %@"
- "@32@0:8@16q24"
- "@36@0:8I16@20@28"
- "Tq,R,V_transportReleasePolicy"
- "_supportsChargingChimeDebounce"
- "_transportReleasePolicy"
- "deviceAvailable:"
- "deviceTransportAvailable:"
- "initWithService:hidManager:uuid:"
- "initWithTempFolder:transportReleasePolicy:"
- "initWithUUID:delegate:delegateQueue:"
- "q"
- "q16@0:8"
- "setDeviceAppleModelNumber:"
- "setDeviceProductGroup:productNumber:"
- "setDeviceSupportsCharging:"
- "setDeviceTransportDomain:"
- "setSupportsChargingChimeDebounce"
- "transportReleasePolicy"
```
