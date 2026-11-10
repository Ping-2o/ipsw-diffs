## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_reflstr`

```diff

-2300.2.9.0.0
-  __TEXT.__text: 0x17b78c
-  __TEXT.__objc_methlist: 0xdc6c
-  __TEXT.__cstring: 0xd2f5
-  __TEXT.__oslogstring: 0x1ad8d
-  __TEXT.__const: 0x1b6b8
-  __TEXT.__gcc_except_tab: 0x28d4
+2300.42.3.0.0
+  __TEXT.__text: 0x17ffdc
+  __TEXT.__objc_methlist: 0xdfb8
+  __TEXT.__cstring: 0xd475
+  __TEXT.__const: 0x1b788
+  __TEXT.__oslogstring: 0x1b5dd
+  __TEXT.__gcc_except_tab: 0x2a54
   __TEXT.__dlopen_cstrs: 0x218
   __TEXT.__swift5_typeref: 0xf3b
   __TEXT.__constg_swiftt: 0xd64
   __TEXT.__swift5_builtin: 0x118
   __TEXT.__swift5_reflstr: 0xade
-  __TEXT.__swift5_fieldmd: 0x10e8
+  __TEXT.__swift5_fieldmd: 0x10f4
   __TEXT.__swift5_assocty: 0x288
   __TEXT.__swift5_proto: 0x328
   __TEXT.__swift5_types: 0x138
+  __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_capture: 0x3d0
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x58f0
+  __TEXT.__unwind_info: 0x59e8
   __TEXT.__eh_frame: 0xb90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x31b8
-  __DATA_CONST.__objc_classlist: 0x790
-  __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x398
+  __DATA_CONST.__const: 0x32d8
+  __DATA_CONST.__objc_classlist: 0x7a0
+  __DATA_CONST.__objc_catlist: 0x20
+  __DATA_CONST.__objc_protolist: 0x3a0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x5c80
+  __DATA_CONST.__objc_selrefs: 0x5e28
   __DATA_CONST.__objc_protorefs: 0x158
-  __DATA_CONST.__objc_superrefs: 0x638
-  __DATA_CONST.__objc_arraydata: 0xcf8
-  __DATA_CONST.__got: 0x7e8
-  __AUTH_CONST.__const: 0x3fa0
-  __AUTH_CONST.__cfstring: 0xed00
-  __AUTH_CONST.__objc_const: 0x38c38
+  __DATA_CONST.__objc_superrefs: 0x640
+  __DATA_CONST.__objc_arraydata: 0xda8
+  __DATA_CONST.__got: 0x800
+  __AUTH_CONST.__const: 0x3fc8
+  __AUTH_CONST.__cfstring: 0xeec0
+  __AUTH_CONST.__objc_const: 0x39520
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x80
-  __AUTH_CONST.__objc_intobj: 0xd98
-  __AUTH_CONST.__objc_arrayobj: 0x420
-  __AUTH_CONST.__objc_dictobj: 0x550
+  __AUTH_CONST.__objc_intobj: 0xdc8
+  __AUTH_CONST.__objc_arrayobj: 0x450
   __AUTH_CONST.__objc_floatobj: 0x1b0
+  __AUTH_CONST.__objc_dictobj: 0x5f0
   __AUTH_CONST.__auth_got: 0x13b0
-  __AUTH.__objc_data: 0x2c90
+  __AUTH.__objc_data: 0x2d30
   __AUTH.__data: 0x788
-  __DATA.__objc_ivar: 0x1860
-  __DATA.__data: 0x35160
-  __DATA.__bss: 0x6b40
+  __DATA.__objc_ivar: 0x18c0
+  __DATA.__data: 0x351c0
+  __DATA.__bss: 0x6b50
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x2238
   __DATA_DIRTY.__data: 0x4e8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9043
-  Symbols:   10659
-  CStrings:  4865
+  Functions: 9152
+  Symbols:   10797
+  CStrings:  4925
 
Symbols:
+ +[CBDisplayBrightnessClient copyNSNumberForKey:client:handle:andError:]
+ +[CBRampProfileSpring defaultSpringProfile]
+ -[BrightnessSystemClient observerSlug:]
+ -[BrightnessSystemClient refreshKeys]
+ -[CBCEModule copyCachedInferenceForEvent:]
+ -[CBCEModule invalidateInferenceCache]
+ -[CBCEModule shouldRunInferenceAtTime:]
+ -[CBColorModuleShared CEModulePropertyHandler:key:]
+ -[CBColorPolicyFilter colorAdaptationActive]
+ -[CBColorPolicyFilter setColorAdaptationActive:]
+ -[CBDisplayBrightnessClient currentSDRNitsWithError:]
+ -[CBDisplayBrightnessClient description]
+ -[CBDisplayBrightnessClient maxSDRDisplayNitsWithError:]
+ -[CBDisplayClient description]
+ -[CBDisplayTransitionPolicy isDeviceStableOpen]
+ -[CBDisplayTransitionPolicy isSourceSettled:target:]
+ -[CBDisplayTransitionPolicy isTopToBottomHandoffFromSource:toTarget:]
+ -[CBDisplayTransitionPolicy panelPlacementForContainer:]
+ -[CBDisplayTransitionPolicy updateAngle:]
+ -[CBHIDEventManager addUnfilteredClient:]
+ -[CBIndicatorBrightnessModule canJumpToTargetIndicatorBrightness]
+ -[CBIndicatorBrightnessModule isPipelineStalled]
+ -[CBIndicatorBrightnessModule isThermalPressureCritical]
+ -[CBIndicatorBrightnessModule jumpTo:forReason:withForce:]
+ -[CBIndicatorBrightnessModule recordSwapStall:]
+ -[CBIndicatorBrightnessModule registerForThermalPressureNotifications]
+ -[CBIndicatorBrightnessModule setThermalPressure:]
+ -[CBIndicatorBrightnessModule startMonitoringForSwapStalls]
+ -[CBIndicatorBrightnessModule stopMonitoringForSwapStalls]
+ -[CBIndicatorBrightnessModule thermalPressureNotificationHandler:]
+ -[CBPreset alwaysRequestMaxHeadroom]
+ -[CBPreset maxPotentialEDRHeadroom]
+ -[CBPresetsParser alwaysRequestMaxHeadroom:]
+ -[CBPresetsParser maxPotentialEDRHeadroomForDisplay:]
+ -[CBRampManager insertNewRampOrigin:target:length:frequency:identifier:profile:]
+ -[CBRampManager insertNewRampOrigin:target:length:frequency:startRamp:identifier:profile:]
+ -[CBRampProfileLinear normalizedOutputForProgress:]
+ -[CBRampProfileSpring _cacheNormalizer]
+ -[CBRampProfileSpring _springValAtT:]
+ -[CBRampProfileSpring damping]
+ -[CBRampProfileSpring init]
+ -[CBRampProfileSpring initialVelocity]
+ -[CBRampProfileSpring mass]
+ -[CBRampProfileSpring normalizedOutputForProgress:]
+ -[CBRampProfileSpring setDamping:]
+ -[CBRampProfileSpring setInitialVelocity:]
+ -[CBRampProfileSpring setMass:]
+ -[CBRampProfileSpring setStiffness:]
+ -[CBRampProfileSpring stiffness]
+ -[CBRingLight resetUserAdjustmentState]
+ -[CBRingLight statusInfo]
+ -[CBSystemContext frameInfoProvider]
+ -[CBSystemContext setFrameInfoProvider:]
+ -[NSArray(PrimitiveDataProvider) copyFloatVector]
+ -[NSSet(PrettyDescription) prettyDescription]
+ -[NightModeControl stop]
+ -[VMBLControl addDisplayModuleForBrightnessControlProxy:]
+ -[VMBLControl findDisplays]
+ -[VMBLControl handleCAWindowServerDisplay:]
+ -[VMBLControl sendBrightnessTransactionRequestForDisplayUUID:builtIn:]
+ -[VMBLControl sendBrightnessTransactionRequestOnQueueForDisplayUUID:builtIn:]
+ -[VMBLControl sendHeadroomRequestOnQueue:forDisplayUUID:builtIn:]
+ -[VMDisplayModule setPropertyOnQueue:forKey:]
+ GCC_except_table101
+ GCC_except_table111
+ GCC_except_table120
+ GCC_except_table140
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table153
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table169
+ GCC_except_table198
+ GCC_except_table41
+ GCC_except_table42
+ GCC_except_table48
+ GCC_except_table74
+ GCC_except_table84
+ _OBJC_CLASS_$_CBRampProfileLinear
+ _OBJC_CLASS_$_CBRampProfileSpring
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_IVAR_$_BLControl._transitionPolicy
+ _OBJC_IVAR_$_BrightnessSystemClient._observedKeys
+ _OBJC_IVAR_$_BrightnessSystemClient._observersCount
+ _OBJC_IVAR_$_CBAODModule._alsNodes
+ _OBJC_IVAR_$_CBCEModule._cachedResult
+ _OBJC_IVAR_$_CBCEModule._cadenceSeconds
+ _OBJC_IVAR_$_CBCEModule._lastInferenceTime
+ _OBJC_IVAR_$_CBCPMSModule._currentHDRNits
+ _OBJC_IVAR_$_CBColorPolicyFilter._ceModelID
+ _OBJC_IVAR_$_CBColorPolicyFilter._colorAdaptationActive
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._currentAngleDegrees
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._hasAngleSample
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._lastAngleBelowCriticalThresholdTime
+ _OBJC_IVAR_$_CBHIDEventManager._unfilteredClients
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._consecutiveSwapStalledCount
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._swapStallObserverToken
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._thermalPressure
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._thermalPressureNotificationToken
+ _OBJC_IVAR_$_CBPreset._alwaysRequestMaxHeadroom
+ _OBJC_IVAR_$_CBPreset._maxPotentialEDRHeadroom
+ _OBJC_IVAR_$_CBRampProfileSpring._damping
+ _OBJC_IVAR_$_CBRampProfileSpring._initialVelocity
+ _OBJC_IVAR_$_CBRampProfileSpring._mass
+ _OBJC_IVAR_$_CBRampProfileSpring._normalizer
+ _OBJC_IVAR_$_CBRampProfileSpring._stiffness
+ _OBJC_IVAR_$_CBRingLight._overriddenByUser
+ _OBJC_IVAR_$_CBSystemContext._frameInfoProvider
+ _OBJC_METACLASS_$_CBRampProfileLinear
+ _OBJC_METACLASS_$_CBRampProfileSpring
+ _OUTLINED_FUNCTION_35
+ _OUTLINED_FUNCTION_36
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSSet_$_PrettyDescription
+ __OBJC_$_CATEGORY_NSSet_$_PrettyDescription
+ __OBJC_$_CLASS_METHODS_CBRampProfileSpring
+ __OBJC_$_INSTANCE_METHODS_CBRampProfileLinear
+ __OBJC_$_INSTANCE_METHODS_CBRampProfileSpring
+ __OBJC_$_INSTANCE_VARIABLES_CBRampProfileSpring
+ __OBJC_$_PROP_LIST_CBRampProfileLinear
+ __OBJC_$_PROP_LIST_CBRampProfileSpring
+ __OBJC_$_PROP_LIST_NSSet_$_PrettyDescription
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBRampProfile
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBRampProfile
+ __OBJC_$_PROTOCOL_REFS_CBRampProfile
+ __OBJC_CLASS_PROTOCOLS_$_CBRampProfileLinear
+ __OBJC_CLASS_PROTOCOLS_$_CBRampProfileSpring
+ __OBJC_CLASS_RO_$_CBRampProfileLinear
+ __OBJC_CLASS_RO_$_CBRampProfileSpring
+ __OBJC_LABEL_PROTOCOL_$_CBRampProfile
+ __OBJC_METACLASS_RO_$_CBRampProfileLinear
+ __OBJC_METACLASS_RO_$_CBRampProfileSpring
+ __OBJC_PROTOCOL_$_CBRampProfile
+ __ZN14CoreBrightness19lookupValueWithAxisIfEET_NSt3__16vectorIS1_NS2_9allocatorIS1_EEEES6_S1_
+ __ZN4AABC22BrightnessRestrictionsD2Ev
+ __ZN4AABC39BrightnessRestrictionMultiPointValues_saSERKS0_
+ ___29-[VMDisplayModule invalidate]_block_invoke
+ ___35-[CBHIDEventManager addHIDService:]_block_invoke_3
+ ___38-[CBHIDEventManager removeHIDService:]_block_invoke_2
+ ___41-[CBHIDEventManager addUnfilteredClient:]_block_invoke
+ ___45-[VMDisplayModule setPropertyOnQueue:forKey:]_block_invoke
+ ___47-[CBIndicatorBrightnessModule recordSwapStall:]_block_invoke
+ ___52-[CBHIDEventManager hidEventCallbackWithEvent:from:]_block_invoke_2
+ ___58-[VMBLControl sendHeadroomRequest:forDisplayUUID:builtIn:]_block_invoke
+ ___59-[CBIndicatorBrightnessModule startMonitoringForSwapStalls]_block_invoke
+ ___70-[CBIndicatorBrightnessModule registerForThermalPressureNotifications]_block_invoke
+ ___70-[VMBLControl sendBrightnessTransactionRequestForDisplayUUID:builtIn:]_block_invoke
+ ___90-[CBRampManager insertNewRampOrigin:target:length:frequency:startRamp:identifier:profile:]_block_invoke
+ _____DisplayReportCommit_block_invoke_2
+ ___block_descriptor_108_e8_32o40r_e23_v24?0"CBALSNode"8^B16ls32l8r40l8
+ ___block_descriptor_40_e8_32b_e33_v16?0r^{?=IIQQQQIBBBfffQIBQQfB}8ls32l8
+ ___block_descriptor_40_e8_32o_e20_v40?0{?=QIBBBffff}8ls32l8
+ ___block_descriptor_40_e8_32o_e36_v24?0"<CBHIDServiceProtocol>"8^B16ls32l8
+ ___block_descriptor_40_e8_32r_e20_v40?0{?=QIBBBffff}8lr32l8
+ ___block_descriptor_40_e8_32r_e8_v12?0i8lr32l8
+ ___block_descriptor_49_e8_32o40o_e15_v32?08Q16^B24ls32l8s40l8
+ ___block_descriptor_49_e8_32o40o_e5_v8?0ls32l8s40l8
+ ___block_descriptor_57_e8_32o40o48o_e5_v8?0ls32l8s40l8s48l8
+ _interpolate_value_in_table
+ _kCBSPIBrightnessCommitUpdate
+ _kCBSPIBrightnessCommitUpdateNitsFinal
+ _kCBSPIBrightnessCommitUpdateNitsInitial
+ _kOSThermalNotificationPressureLevelName
+ _load_mapping_table_from_defaults
+ _mapping_table_is_valid
+ _save_mapping_table_to_defaults
- -[CBColorModuleShared CEOverridePropertyHandler:key:]
- -[CBDisplayTransitionPolicy isSourceSettled:]
- -[CBIndicatorBrightnessModule jumpTo:]
- -[CBRingLight getStatusInfo]
- -[VMBLControl requestBrightnessTransactionForDisplayUUID:builtIn:]
- GCC_except_table110
- GCC_except_table119
- GCC_except_table134
- GCC_except_table139
- GCC_except_table141
- GCC_except_table142
- GCC_except_table149
- GCC_except_table154
- GCC_except_table155
- GCC_except_table194
- GCC_except_table39
- GCC_except_table62
- GCC_except_table67
- GCC_except_table70
- GCC_except_table83
- _OBJC_IVAR_$_CBAODModule._alsServiceClients
- _OBJC_IVAR_$_CBCPMSModule._currentSDRNits
- _OBJC_IVAR_$_CBRingLight._overridenByUser
- ___18-[BLControl start]_block_invoke_7
- ___83-[VMDisplayModule initWithBrightnessControl:displayUUID:builtIn:delegate:andQueue:]_block_invoke_2
- ___block_descriptor_108_e8_32o40r_e33_v32?0"HIDServiceClient"8Q16^B24ls32l8r40l8
- ___block_descriptor_40_e8_32b_e32_v16?0r^{?=IIQQQQIBBBfffQIBQQf}8ls32l8
- ___block_descriptor_40_e8_32o_e19_v40?0{?=QIBBffff}8ls32l8
CStrings:
+ "%@<%@>"
+ "%@@%@ with %@"
+ "-[BrightnessSystemClient unregisterObserver:]"
+ "Add unfiltered client %@"
+ "Adding module for display with ID = %d uuid:%@ builtIn:%d"
+ "Angle=%f"
+ "Backboardd restarted"
+ "BrightnessCommitUpdate"
+ "CECadence"
+ "CPMSCurrentHDRNits"
+ "Display on seeded by handoff — skipping snap to own curve"
+ "DisplayIntegrated"
+ "DisplayPanelPlacement"
+ "EXBrightSILStateTrusted"
+ "Grimaldi lux cap = %.2f"
+ "HarmonyStrength"
+ "Ignoring %{public}@: expected %zu levels, got %lu"
+ "Ignoring %{public}@: not ascending: %{public}@"
+ "Ignoring negative CE cadence %f"
+ "IlluminanceToLuminanceAggregated_AOD: nits cap = %f, ceiling = %f, AOD L = %f >>> L %f"
+ "Initial thermal pressure level: %llu"
+ "Jumping to target indicator brightness: %f for reason: %s (forced=%d)"
+ "Loaded Restriction Dictionary (Dynamic Slider Configuration) from defaults (StoreDemoMode = %d): %@"
+ "OverriddenByUser"
+ "Overriding Boot-nits: %.2f -> %.2f nits"
+ "Presets(%lu): always request max headroom = %d"
+ "Presets(%lu): maxPotentialEDRHeadroom: %@"
+ "Ramp too long"
+ "Render pipeline stalled"
+ "Semantic ambient lux levels: %{public}@"
+ "Setting CE inference cadence to %f s"
+ "Swap stall state changed: stalled=%d (%u consecutive)"
+ "Thermal pressure critical"
+ "Thermal pressure level changed: %llu -> %llu"
+ "WSDisplays: %{public}@"
+ "[%@]"
+ "[%@]cached strength: %.2f, confidence: %f"
+ "[BRT update: %s]: Begin slider drag"
+ "[BRT update: %s]: begin ramp L: %0.2f -> %0.2f P: %0.2f -> %0.2f (hwMax-perceptual) t: %f rate: %0.2f nits/s %0.2fhz"
+ "[CPMS] Current HDR brightness updated: %f -> %f"
+ "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs start=%f"
+ "[CPMS] Using current HDR nits (%f) instead of cap (%f) for ramp duration calculation"
+ "[Color Mitigation] lux=%.1f nits=%.1f mitigated=%d ceEnabled=%d ttActive=%d ceAttempted=%d source=%s confidence=%.3f threshold=%.3f crossedThreshold=%d strength=%.3f"
+ "[Display Transition] ALS suppression OFF"
+ "[Display Transition] ALS suppression OFF - handling skipped"
+ "[Display Transition] ALS suppression ON"
+ "[Display] CPMS cap ramp: seeding origin %f -> %f (target %f, headroom %f)"
+ "[Display] CPMS ramp request: target=%f duration=%f start=%f"
+ "[Dynamic Slider] MAX - failed to convert thresholds or factors to a float vector"
+ "[Dynamic Slider] MAX - missing thresholds or factors"
+ "[Dynamic Slider] MAX - thresholds and factors differ in size (%zu vs %zu)"
+ "[Dynamic Slider] MAX - thresholds and factors need at least 1 entry"
+ "[Dynamic Slider] MAX - thresholds or factors are not arrays"
+ "[Dynamic Slider] MAX - thresholds or factors not sorted in ascending order"
+ "[Dynamic Slider] MIN - failed to convert thresholds or factors to a float vector"
+ "[Dynamic Slider] MIN - missing thresholds or factors"
+ "[Dynamic Slider] MIN - thresholds and factors differ in size (%zu vs %zu)"
+ "[Dynamic Slider] MIN - thresholds and factors need at least 1 entry"
+ "[Dynamic Slider] MIN - thresholds or factors are not arrays"
+ "[Dynamic Slider] MIN - thresholds or factors not sorted in ascending order"
+ "[Handoff] angle at %.0f degrees, no dip below %.0f degrees for %.1fs - not a hinge-open motion, skipping grace period, fast-ramping target instead"
+ "[Handoff] source is exiting AOD - skipping grace period, fast-ramping target instead"
+ "[Handoff] source is in fast ramp - skipping grace period, fast-ramping target instead"
+ "[Observer] Adding %@"
+ "[Observer] Not adding %@ - no observable properties"
+ "[Observer] Observed keys 🔑: %@ - %@ + %@ = %@"
+ "[Observer] Refreshing %@"
+ "[Observer] Removing %@ since the set of properties become empty."
+ "[Observer] Unregistering %@"
+ "[dcpRoleID=%d] [ReadBack] Couldn't fetch SIL state!"
+ "[dcpRoleID=%d] [ReadBack] SIL=%d"
+ "[dcpRoleID=%d] [ReadBack] SIL=%d, sessionID=%u"
+ "[dcpRoleID=%d] [WillSend] SIL=%d"
+ "[dcpRoleID=%d] [WillSend] SIL=%d failed!"
+ "_S=%f"
+ "com.apple.demo-settings"
+ "crgb lookup: found=%d parsed=%d value=%d"
+ "grimaldi-lux-cap"
+ "headroomRequestDelegate is nil, cannot request brightness transaction"
+ "initialNits"
+ "notify_get_state failed with %d for token %d"
+ "notify_register_dispatch failed with %d for %s"
+ "override-boot-brightness-nits"
+ "semantic-lux-levels"
+ "startNits"
+ "v16@?0r^{?=IIQQQQIBBBfffQIBQQfB}8"
+ "v24@?0@\"<CBHIDServiceProtocol>\"8^B16"
+ "v24@?0@\"CBALSNode\"8^B16"
+ "v40@?0{?=QIBBBffff}8"
- "/var/mobile/Library/Preferences/com.apple.demo-settings"
- "ALS transition suppression: %s"
- "BrightnessRestrictions were loaded from CFPreferences (StoreDemoMode = %s)"
- "CPMSCurrentSDRNits"
- "Failed to load BrightnessRestrictions from CFPreferences (StoreDemoMode = %s)"
- "IlluminanceToLuminanceAggregated_AOD: E(Lux) = %f | normal L(Nits) = %f | restricted normal L(Nits) = %f | AOD L(Nits) = %f >>> L %f"
- "Jumping to target indicator brightness: %f"
- "OverridenByUser"
- "Received angle %f"
- "Registered observer %@ with handle %@, properties %@. Subscribing to the following new keys: %@"
- "Removing observer %@ with handle %@. Unregistering the following keys: %@"
- "Setting PLT angle to %f"
- "Transitioning to Flipbook, forcing NaN IB to CA!"
- "[%x]: _S=%f"
- "[CPMS] Current SDR brightness updated: %f -> %f"
- "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs"
- "[CPMS] Using current SDR nits (%f) instead of cap (%f) for ramp duration calculation"
- "[Color Mitigation] lux=%.1f nits=%.1f mitigated=%d ceEnabled=%d ceAttempted=%d source=%s confidence=%.3f threshold=%.3f crossedThreshold=%d strength=%.3f"
- "[Display] CPMS ramp request: target=%f duration=%f"
- "[Handoff] source exiting AOD, not settled"
- "[Handoff] source in fast ramp, not settled"
- "[Handoff] source not settled - skip grace period"
- "[dcpRoleID=%d] SIL=%d, monotonicTimeUS=%llu. Sending to EXBright: %@."
- "error: unknown notification type (%@)"
- "key=%@ (type=%tu) value=%@  block=%p queue=%p"
- "key=%@ property=%@ queue=%p clientBlock=%p"
- "no callback or queue available - ignoring notification"
- "v16@?0r^{?=IIQQQQIBBBfffQIBQQf}8"
- "v40@?0{?=QIBBffff}8"
```
