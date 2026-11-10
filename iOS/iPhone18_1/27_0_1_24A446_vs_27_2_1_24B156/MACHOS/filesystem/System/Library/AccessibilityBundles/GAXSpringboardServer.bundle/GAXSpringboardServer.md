## GAXSpringboardServer

> `/System/Library/AccessibilityBundles/GAXSpringboardServer.bundle/GAXSpringboardServer`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1064.0.0.0.0
-  __TEXT.__text: 0x15dac
-  __TEXT.__auth_stubs: 0x6c0
-  __TEXT.__objc_stubs: 0x2f00
-  __TEXT.__objc_methlist: 0x1edc
+1067.3.4.0.0
+  __TEXT.__text: 0x162dc
+  __TEXT.__auth_stubs: 0x6e0
+  __TEXT.__objc_stubs: 0x2f60
+  __TEXT.__objc_methlist: 0x1efc
   __TEXT.__const: 0xb8
-  __TEXT.__gcc_except_tab: 0x46c
-  __TEXT.__cstring: 0x5055
-  __TEXT.__objc_methname: 0x5938
-  __TEXT.__oslogstring: 0x1ac0
+  __TEXT.__gcc_except_tab: 0x464
+  __TEXT.__cstring: 0x5111
+  __TEXT.__objc_methname: 0x5a2c
+  __TEXT.__oslogstring: 0x1c59
   __TEXT.__objc_classname: 0xcff
-  __TEXT.__objc_methtype: 0xfbd
-  __TEXT.__unwind_info: 0x6e8
-  __DATA_CONST.__const: 0x1228
-  __DATA_CONST.__cfstring: 0x4ca0
+  __TEXT.__objc_methtype: 0x1078
+  __TEXT.__unwind_info: 0x6f0
+  __DATA_CONST.__const: 0x1238
+  __DATA_CONST.__cfstring: 0x4d20
   __DATA_CONST.__objc_classlist: 0x2b8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x20

   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_doubleobj: 0x30
   __DATA_CONST.__objc_intobj: 0xc0
-  __DATA_CONST.__auth_got: 0x370
-  __DATA_CONST.__got: 0x248
-  __DATA.__objc_const: 0x3d00
-  __DATA.__objc_selrefs: 0x14d0
+  __DATA_CONST.__auth_got: 0x380
+  __DATA_CONST.__got: 0x260
+  __DATA.__objc_const: 0x3d18
+  __DATA.__objc_selrefs: 0x1500
   __DATA.__objc_ivar: 0x5c
   __DATA.__objc_data: 0x1b30
   __DATA.__data: 0x188

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 547
-  Symbols:   545
-  CStrings:  1591
+  Functions: 554
+  Symbols:   559
+  CStrings:  1608
 
Symbols:
+ _CACornerRadiiEqualToRadii
+ _CACornerRadiiZero
+ _GAXBackboardStateAllowsAllTouchByOverride
+ _GAXBackboardStateAllowsAllTouchForTransientSystemUI
+ _GAXCornerRadiiFromRectCornerRadii
+ _GAXDisplayCornerRadiiForWindow
+ _GAXFixedSpaceCornerRadiiFromInterfaceCornerRadii
+ _GAXIPCPayloadKeyHostedApplicationCornerRadii
+ _GAXRectCornerRadiiFromCornerRadii
+ _GAXUIMessageKeyHostedApplicationCornerRadii
+ _UIRectCornerRadiiFromString
+ __UITraitCollectionDisplayCornerRadiusUnspecified
+ _deserializeGAXBackboardState
+ _kCACornerCurveContinuous
+ _objc_retain_x28
- _objc_retain_x27
CStrings:
+ "  overrideAllowsAllTouchAuthenticatingWithBiometrics: %ld\n"
+ "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:]"
+ "@\"NSDictionary\"16@0:8"
+ "GAXIPCPayloadKeyHostedApplicationCornerRadii"
+ "Guided Access is trying to make the system aperture inert, but we already have an assertion."
+ "Home grabber still suppressed with no active Guided Access session; clearing stale suppression and applying mode %ld."
+ "Ignoring request for system aperture to become inert, Guided Access is not running."
+ "No system aperture inert assertion held, nothing to invalidate."
+ "SpringBoard wants to update Home Grabber display mode but Guided Access is suppressing it. Will apply when Guided Access ends."
+ "_handleUpdateHostedApplicationState: app=%{public}@ scaleFactor=%.3f center={%.1f,%.1f} cornerRadii=%{public}@ duration=%.2f"
+ "_updateStateOfHostedApplicationWithIdentifier:scaleFactor:center:cornerRadii:animationDuration:"
+ "appmanagedfeaturesd"
+ "effectiveRadiusForCorner:"
+ "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:"
+ "hosted application corner radii"
+ "nativeFocusedApplicationSceneInfo"
+ "setCornerCurve:"
+ "setCornerRadii:"
+ "switchNativeFocusedApplicationToProcessIdentifier:sceneIdentifier:"
+ "toggleLiveRecognitionWithServerInstance:"
+ "v120@0:8@16d24{CGPoint=dd}32{CACornerRadii={CGSize=dd}{CGSize=dd}{CGSize=dd}{CGSize=dd}}48d112"
+ "v28@0:8i16@\"NSString\"20"
+ "v28@0:8i16@20"
+ "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
+ "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
+ "v56@0:8@16@24@32@40@48"
+ "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
+ "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideAllowsAllTouchAuthenticatingWithBiometrics\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1\"allowsLayoutTransitions\"b1\"allowsDisplayChanges\"b1}"
- "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:]"
- "Unexpectedly tried to update home grabber display mode change for a floating window after creation."
- "_handleUpdateHostedApplicationState: app=%{public}@ scaleFactor=%.3f center={%.1f,%.1f} duration=%.2f"
- "_updateStateOfHostedApplicationWithIdentifier:scaleFactor:center:animationDuration:"
- "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:"
- "v44@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16"
- "v48@0:8@16@24@32@40"
- "v52@0:8{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}16@?44"
- "v56@0:8@16d24{CGPoint=dd}32d48"
- "v60@0:8I16B20{?=IIIIIIb1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}24q52"
- "{?=\"mode\"I\"passcodeWindowContextID\"I\"voiceOverItemChooserWindowContextID\"I\"tripleClickSheetWindowContextID\"I\"assistiveTouchPort\"I\"profileConfiguration\"I\"shouldBlockAllEvents\"b1\"restartingAndWasActiveBeforeRestart\"b1\"verifyingDeviceUnlockInSAM\"b1\"isPasscodeViewVisible\"b1\"isRestricted\"b1\"overrideAllowsAllTouchSBMiniAlertIsShowing\"b1\"overrideAllowsAllTouchCallStateIsChanging\"b1\"overrideAllowsAllTouchMakingEmergencyCall\"b1\"overrideIgnoresAllTouchAllowedAppNotFound\"b1\"overrideIgnoresAllTouchVerifyingIntegrity\"b1\"allowsTouch\"b1\"allowsLockButton\"b1\"allowsAppExit\"b1\"allowsHomeButton\"b1\"allowsVolumeButtons\"b1\"allowsRingerSwitch\"b1\"allowsMotion\"b1\"allowsAutolock\"b1\"allowsKeyboardTextInput\"b1\"allowsProximity\"b1\"allowsLayoutTransitions\"b1\"allowsDisplayChanges\"b1}"
```
