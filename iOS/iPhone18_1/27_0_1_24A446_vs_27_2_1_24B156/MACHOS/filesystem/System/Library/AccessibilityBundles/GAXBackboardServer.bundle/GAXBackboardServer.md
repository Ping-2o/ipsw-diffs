## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1064.0.0.0.0
-  __TEXT.__text: 0x2b720
+1067.3.4.0.0
+  __TEXT.__text: 0x2c3a0
   __TEXT.__auth_stubs: 0xc40
-  __TEXT.__objc_stubs: 0x6980
-  __TEXT.__objc_methlist: 0x28ac
-  __TEXT.__const: 0x188
-  __TEXT.__gcc_except_tab: 0x84c
-  __TEXT.__objc_methname: 0x8d7a
-  __TEXT.__cstring: 0x4737
-  __TEXT.__oslogstring: 0x41e2
+  __TEXT.__objc_stubs: 0x6b20
+  __TEXT.__objc_methlist: 0x293c
+  __TEXT.__const: 0x190
+  __TEXT.__gcc_except_tab: 0x898
+  __TEXT.__objc_methname: 0x8ffc
+  __TEXT.__cstring: 0x4835
+  __TEXT.__oslogstring: 0x44e5
   __TEXT.__objc_classname: 0x2ed
-  __TEXT.__objc_methtype: 0x18ca
-  __TEXT.__unwind_info: 0xaa0
-  __DATA_CONST.__const: 0x16b8
-  __DATA_CONST.__cfstring: 0x3720
+  __TEXT.__objc_methtype: 0x1919
+  __TEXT.__unwind_info: 0xac0
+  __DATA_CONST.__const: 0x1708
+  __DATA_CONST.__cfstring: 0x37c0
   __DATA_CONST.__objc_classlist: 0x90
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x60

   __DATA_CONST.__auth_got: 0x630
   __DATA_CONST.__got: 0x350
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x2a30
-  __DATA.__objc_selrefs: 0x1ed8
-  __DATA.__objc_ivar: 0x1a8
+  __DATA.__objc_const: 0x2aa0
+  __DATA.__objc_selrefs: 0x1f40
+  __DATA.__objc_ivar: 0x1b0
   __DATA.__objc_data: 0x5a0
   __DATA.__data: 0x588
   __DATA.__bss: 0xa8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 967
-  Symbols:   583
-  CStrings:  2262
+  Functions: 985
+  Symbols:   588
+  CStrings:  2294
 
Symbols:
+ _GAXBackboardStateAllowsAllTouchByOverride
+ _GAXBackboardStateAllowsAllTouchForTransientSystemUI
+ _GAXIPCPayloadKeyHostedApplicationCornerRadii
+ _GAXUIMessageKeyHostedApplicationCornerRadii
+ _deserializeGAXBackboardState
CStrings:
+ "  overrideAllowsAllTouchAuthenticatingWithBiometrics: %ld\n"
+ "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:]"
+ "Active interface orientation still unknown after %lu retries. Exiting the workspace."
+ "Active interface orientation was unknown. Retrying transition to mode %lu in %g seconds (attempt %lu of %lu)."
+ "Active interface orientation was unknown; resolved it to %ld from SpringBoard."
+ "App layout has %d app elements of %d total, from same app %i: %{public}@"
+ "Authenticating with biometrics"
+ "B44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
+ "B52@0:8@16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24"
+ "B56@0:8@16I24{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}28"
+ "Begin allowing all touch for biometric authentication"
+ "Disabling GAX because the session app is restricted by Partner Financing."
+ "Dropping superseded orientation retry %lu."
+ "End allowing all touch for biometric authentication"
+ "Error - Session app is restricted by Partner Financing"
+ "GAXIPCPayloadKeyHostedApplicationCornerRadii"
+ "Reconciling implicit GAX client check-in for still-frontmost session app %@ (pid:%@). Its one-shot check-in ping was lost, not absent"
+ "Session app %{public}@ is restricted. Reason: %lu"
+ "Session app is still frontmost but its GAX client never checked in; reconciling the lost check-in"
+ "Starting biometric authentication. Touch is restricted: %{public}d"
+ "TB,N,V_cachedIsLostModeActive"
+ "TB,N,V_didReadLostModeState"
+ "TQ,N,V_unknownOrientationRetryCount"
+ "_beginAllowingAllTouchForBiometricAuthentication"
+ "_cachedIsLostModeActive"
+ "_didReadLostModeState"
+ "_endAllowingAllTouchForBiometricAuthentication"
+ "_isAllowingAllTouchForTransientSystemUI"
+ "_unknownOrientationRetryCount"
+ "applicationState"
+ "cachedIsLostModeActive"
+ "didReadLostModeState"
+ "didReconcileCheckInForEffectiveSessionApp"
+ "didReconcileSessionAppCheckInForIntegrityVerifier:"
+ "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:"
+ "hosted application corner radii"
+ "initWithBundleIdentifier:allowPlaceholder:error:"
+ "restrictionReason"
+ "sessionAppIsRestrictedByPartnerFinancingForIntegrityVerifier:"
+ "setCachedIsLostModeActive:"
+ "setDidReadLostModeState:"
+ "setUnknownOrientationRetryCount:"
+ "unknownOrientationRetryCount"
+ "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
+ "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
+ "v56@0:8@16@24@32@40@48"
+ "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
+ "v60@0:8Q16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@?52"
+ "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideAllowsAllTouchAuthenticatingWithBiometrics\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1\"allowsLayoutTransitions\"b1\"allowsDisplayChanges\"b1}"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@0:8"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXEventProcessor\"16"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXVerifier\"16"
+ "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@16"
- "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:]"
- "Active interface orientation was unknown. trying to transition gax again in .25. %{public}@"
- "App layout has %d elements from same app %i: %{public}@"
- "B44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
- "B52@0:8@16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24"
- "B56@0:8@16I24{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}28"
- "TB,N,V_isLostModeActive"
- "_isAllowingAllTouchByOverride"
- "_isLostModeActive"
- "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:"
- "setIsLostModeActive:"
- "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
- "v48@0:8@16@24@32@40"
- "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
- "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
- "v60@0:8Q16{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@?52"
- "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1\"allowsLayoutTransitions\"b1\"allowsDisplayChanges\"b1}"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@0:8"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXEventProcessor\"16"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@\"GAXVerifier\"16"
- "{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24@0:8@16"
```
