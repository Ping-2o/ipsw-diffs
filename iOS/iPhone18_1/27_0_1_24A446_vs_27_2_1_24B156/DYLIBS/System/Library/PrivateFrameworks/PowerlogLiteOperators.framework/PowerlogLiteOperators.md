## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

```diff

-3486.2.4.0.0
-  __TEXT.__text: 0x4f65e8
-  __TEXT.__objc_methlist: 0x2f71c
-  __TEXT.__const: 0x2cb0
+3486.42.1.0.0
+  __TEXT.__text: 0x4f8f78
+  __TEXT.__objc_methlist: 0x2f854
+  __TEXT.__const: 0x2cc0
   __TEXT.__swift5_typeref: 0x710
   __TEXT.__constg_swiftt: 0x544
   __TEXT.__swift5_reflstr: 0x4de

   __TEXT.__swift5_types: 0x54
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__cstring: 0x60733
+  __TEXT.__cstring: 0x60bab
   __TEXT.__swift5_capture: 0x73c
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift_as_entry: 0x64
   __TEXT.__swift_as_ret: 0x6c
   __TEXT.__swift_as_cont: 0xd0
-  __TEXT.__oslogstring: 0x167b9
+  __TEXT.__oslogstring: 0x16b24
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__gcc_except_tab: 0x2d68
+  __TEXT.__gcc_except_tab: 0x2d90
   __TEXT.__ustring: 0x22
-  __TEXT.__unwind_info: 0x8478
+  __TEXT.__unwind_info: 0x8490
   __TEXT.__eh_frame: 0x16d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9730
-  __DATA_CONST.__objc_classlist: 0xa70
+  __DATA_CONST.__const: 0x9740
+  __DATA_CONST.__objc_classlist: 0xa78
   __DATA_CONST.__objc_nlclslist: 0x268
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x14da8
+  __DATA_CONST.__objc_selrefs: 0x14e70
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0xb48
-  __DATA_CONST.__objc_arraydata: 0x16d00
+  __DATA_CONST.__objc_superrefs: 0xb50
+  __DATA_CONST.__objc_arraydata: 0x16da0
   __DATA_CONST.__got: 0x1b78
-  __AUTH_CONST.__const: 0x2a58
-  __AUTH_CONST.__cfstring: 0x781a0
-  __AUTH_CONST.__objc_const: 0x38a50
+  __AUTH_CONST.__const: 0x2a98
+  __AUTH_CONST.__cfstring: 0x78600
+  __AUTH_CONST.__objc_const: 0x38c70
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_intobj: 0x6e70
-  __AUTH_CONST.__objc_arrayobj: 0x30d8
-  __AUTH_CONST.__objc_dictobj: 0x50c8
-  __AUTH_CONST.__objc_doubleobj: 0x1310
-  __AUTH_CONST.__auth_got: 0x1958
+  __AUTH_CONST.__objc_intobj: 0x6ea0
+  __AUTH_CONST.__objc_arrayobj: 0x3180
+  __AUTH_CONST.__objc_dictobj: 0x5140
+  __AUTH_CONST.__objc_doubleobj: 0x1320
+  __AUTH_CONST.__auth_got: 0x1960
   __AUTH.__objc_data: 0x2c10
   __AUTH.__data: 0x668
-  __DATA.__objc_ivar: 0x1f94
+  __DATA.__objc_ivar: 0x1fac
   __DATA.__data: 0x10f8
   __DATA.__common: 0x1f8
   __DATA.__bss: 0x26f0
-  __DATA_DIRTY.__objc_ivar: 0x1388
-  __DATA_DIRTY.__objc_data: 0x3f08
+  __DATA_DIRTY.__objc_ivar: 0x1390
+  __DATA_DIRTY.__objc_data: 0x3f58
   __DATA_DIRTY.__data: 0x728
-  __DATA_DIRTY.__bss: 0x4778
+  __DATA_DIRTY.__bss: 0x4798
   __DATA_DIRTY.__common: 0xb8
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CloudKit.framework/CloudKit

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 19875
-  Symbols:   25867
-  CStrings:  19863
+  Functions: 19904
+  Symbols:   25910
+  CStrings:  19924
 
Symbols:
+ +[PLAppTimeService entryAggregateDefinitionDisplayUsage]
+ +[PLUrsaUtilities diagnosticExtensionIDsForProcess:]
+ +[PLUrsaUtilities generateTTRURLWithRadarParams:context:metadataPath:]
+ +[PLUrsaUtilities remoteDiagnosticParamsForProcess:]
+ +[PLUrsaUtilities writeMetadata:toDirectory:]
+ -[PLAppTimeService aggregateEntryKeyForDisplayUsage]
+ -[PLAppTimeService setAggregateEntryKeyForDisplayUsage:]
+ -[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]
+ -[PLBatteryAgent batteryPackCount]
+ -[PLBatteryAgent setBatteryPackCount:]
+ -[PLCoalitionAgent buildPLEntryDiffForObject:withNewUsage:hasPrevSample:withStartDate:withEndDate:]
+ -[PLCoalitionAgent logOSMetrics:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldLogCoalitionObject:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldProcessCoalitionID:seenCoalitionIDs:]
+ -[PLSleepWakeAgent kaIDMax]
+ -[PLSleepWakeAgent kaIDMin]
+ -[PLSleepWakeAgent setKaIDMax:]
+ -[PLSleepWakeAgent setKaIDMin:]
+ -[PLUrsaViolationContext .cxx_destruct]
+ -[PLUrsaViolationContext init]
+ -[PLUrsaViolationContext internalOnlyRule]
+ -[PLUrsaViolationContext issueType]
+ -[PLUrsaViolationContext mitigationsEnabled]
+ -[PLUrsaViolationContext procName]
+ -[PLUrsaViolationContext ruleID]
+ -[PLUrsaViolationContext setInternalOnlyRule:]
+ -[PLUrsaViolationContext setIssueType:]
+ -[PLUrsaViolationContext setMitigationsEnabled:]
+ -[PLUrsaViolationContext setProcName:]
+ -[PLUrsaViolationContext setRuleID:]
+ -[PLUrsaViolationContext setViolationTime:]
+ -[PLUrsaViolationContext violationTime]
+ GCC_except_table171
+ GCC_except_table216
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_PLUrsaViolationContext
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMax
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMin
+ _OBJC_IVAR_$_PLUrsaViolationContext._internalOnlyRule
+ _OBJC_IVAR_$_PLUrsaViolationContext._issueType
+ _OBJC_IVAR_$_PLUrsaViolationContext._mitigationsEnabled
+ _OBJC_IVAR_$_PLUrsaViolationContext._procName
+ _OBJC_IVAR_$_PLUrsaViolationContext._ruleID
+ _OBJC_IVAR_$_PLUrsaViolationContext._violationTime
+ _OBJC_METACLASS_$_PLUrsaViolationContext
+ __OBJC_$_INSTANCE_METHODS_PLUrsaViolationContext
+ __OBJC_$_INSTANCE_VARIABLES_PLUrsaViolationContext
+ __OBJC_$_PROP_LIST_PLUrsaViolationContext
+ __OBJC_CLASS_RO_$_PLUrsaViolationContext
+ __OBJC_METACLASS_RO_$_PLUrsaViolationContext
+ ___52+[PLUrsaUtilities diagnosticExtensionIDsForProcess:]_block_invoke
+ ___52+[PLUrsaUtilities remoteDiagnosticParamsForProcess:]_block_invoke
+ ___83-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8s48l8
+ _kPLAppTimeServiceAggregateNameDisplayID
+ _kPLAppTimeServiceAggregateNameDisplayUsage
+ _normalizedProcessName
- +[PLUrsaUtilities generateTTRURLWithRadarParams:procName:mitigationsEnabled:violationTime:metadataPath:issueType:]
- -[PLCoalitionAgent buildPLEntryDiffForObject:withStartDate:withEndDate:]
- -[PLCoalitionAgent logCoalitionObjectDifference]
- -[PLCoalitionAgent logOSMetrics:]
- -[PLCoalitionAgent shouldLogCoalitionObject:]
- -[PLCoalitionDataObject hasPrevSample]
- -[PLCoalitionDataObject prevCoalResourceUsage]
- GCC_except_table173
- GCC_except_table219
- GCC_except_table35
- _OBJC_IVAR_$_PLCoalitionDataObject._hasPrevSample
- _OBJC_IVAR_$_PLCoalitionDataObject._prevCoalResourceUsage
- ___48-[PLCoalitionAgent logCoalitionObjectDifference]_block_invoke
- ___block_descriptor_49_e8_32s40s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8
CStrings:
+ "\n\nNOTE: This issue was caught by a detection rule that is enabled on internal builds only. Mitigations for this rule are not applied on customer devices."
+ "$rulePolicy"
+ "%@: rail is OFF, timestamp=%u, entry=%d"
+ "%@: reached end of buffer, timestamp=%u, entry=%d"
+ "-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]"
+ "2033894"
+ "AccumSystemEffectiveTotalLoad"
+ "AccumSystemEffectiveTotalLoadCount"
+ "AccumulatedBatteryPower"
+ "BatteryPowerAccumulatorCount"
+ "ComponentID"
+ "ComponentName"
+ "ComponentVersion"
+ "DeviceClasses"
+ "DisplayID"
+ "DisplayUsage"
+ "Drop Box (Multi-device)"
+ "ExtensionIdentifiers"
+ "Feature disabled int=%d adg=%d forceDisable=%d"
+ "For bundleID '%@' and display ID %@, added foreground %@"
+ "HomeKitPrimaryResident"
+ "InternalOnlyRule"
+ "J775d"
+ "Kernel assertions entry: kaID=%llu, duration=%f, count=%zu"
+ "Log Power Delivery Keys to CA, payload=%@"
+ "Nearby"
+ "OpenBandExtraSensesOnLastWLPerMode"
+ "OpenBandExtraSensesPerMode"
+ "OpenBandReadsPerMode"
+ "PLUrsaUtilities: %{public}@ exists but is not a directory"
+ "PLUrsaUtilities: could not remove existing metadata at %{public}@, overwriting in place: %{public}@"
+ "PLUrsaUtilities: could not set permissions on %{public}@, continuing: %{public}@"
+ "PLUrsaUtilities: could not write metadata to %{public}@, falling back to %{public}@"
+ "PLUrsaUtilities: created directory at: %{public}@"
+ "PLUrsaUtilities: failed to create directory %{public}@: errno=%d (%{public}s) error=%{public}@"
+ "PLUrsaUtilities: failed to create metadata file URL in %{public}@"
+ "PLUrsaUtilities: failed to write metadata to %{public}@: errno=%d (%{public}s) error=%{public}@"
+ "PLUrsaUtilities: failed to write metadata to both %{public}@ and %{public}@"
+ "PLUrsaUtilities: invalid metadata directory"
+ "PLUrsaUtilities: nil violation context"
+ "PLUrsaUtilities: requesting diagnostic extensions %{public}@ for %{public}@"
+ "PLUrsaUtilities: requesting remote device diagnostics for %{public}@: %{public}@ (component %{public}@ -> %{public}@)"
+ "RemoteDeviceSelections"
+ "RuleID"
+ "SystemEffectiveTotalLoad"
+ "UrsaForceDisable"
+ "Watch"
+ "Watch,Mac,iPad"
+ "adding timeDifference=%f for bundleID=%@ and displayID=%lu"
+ "com.apple.DiagnosticExtensions.IMDiagnosticExtension"
+ "com.apple.PhotoLibraryServices.PhotosDiagnostics"
+ "com.apple.power.powerDeliveryKeys"
+ "debugDataCompressionFailed"
+ "debugDataDumpSuccess"
+ "debugDataGetFail"
+ "debugDataGetSuccess"
+ "debugDataHandoffToRxBurn"
+ "debugDataRequestDropped"
+ "debugDataRequestDump"
+ "debugDataTrimCalled"
+ "deferredmediad"
+ "devicesharingd"
+ "generateTTRURL: called with issueType = %d, ruleID = %d, internalOnlyRule = %d"
+ "idleStackFlowVCurveCDPAtSlowGC"
+ "imagent"
+ "imdpersistence.imdpersistenceagent"
+ "imdpersistenceagent"
+ "internalOnlyRule"
+ "rail = %@, payload = %@"
+ "ruleID"
+ "sanitizeDoneTime"
+ "sanitizeReject"
+ "sanitizeStartTime"
+ "sanitizeStatus"
+ "timer_read64_synced"
- "%@: manually increment timestamp %u at entry %d"
- "%@: reached the end of buffer at entry %d"
- "%@: reached the end of buffer at entry %d due to timestamp jump %u"
- "-[PLCoalitionAgent logCoalitionObjectDifference]"
- "Feature disabled int=%d adg=%d"
- "Kernel assertions entry: paID=%llu, duration=%f, count=%zu"
- "PLUrsaUtilities: created Ursa directory at: %{public}@"
- "PLUrsaUtilities: failed to create Ursa directory: %{public}@"
- "PLUrsaUtilities: failed to create metadata file URL"
- "PLUrsaUtilities: failed to create metadata file with permissions"
- "PMUMetricsStatic: rail = %@, payload = %@"
- "generateTTRURL: called with issueType = %d"
- "idleStackPurgeableValidityCurveAtSlowGC"
- "self.lastCoalitionObjectDictionary=%@"
```
