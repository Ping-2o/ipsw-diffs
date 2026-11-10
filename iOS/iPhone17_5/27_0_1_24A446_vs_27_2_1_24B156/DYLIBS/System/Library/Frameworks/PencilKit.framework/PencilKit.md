## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/PencilKit`

```diff

-616.100.0.0.0
-  __TEXT.__text: 0x355d24
-  __TEXT.__objc_methlist: 0x26074
-  __TEXT.__const: 0x8ef4
+622.1.2.0.0
+  __TEXT.__text: 0x357494
+  __TEXT.__objc_methlist: 0x261bc
+  __TEXT.__const: 0x8f84
   __TEXT.__dlopen_cstrs: 0x563
   __TEXT.__constg_swiftt: 0x1f2c
   __TEXT.__swift5_typeref: 0x1f06

   __TEXT.__swift5_assocty: 0x728
   __TEXT.__swift5_proto: 0x398
   __TEXT.__swift5_types: 0x1dc
-  __TEXT.__swift5_capture: 0xa9c
-  __TEXT.__cstring: 0xf962
-  __TEXT.__oslogstring: 0xed2f
+  __TEXT.__swift5_capture: 0xacc
+  __TEXT.__cstring: 0xf96b
+  __TEXT.__oslogstring: 0xedff
   __TEXT.__swift_as_entry: 0xf0
   __TEXT.__swift_as_cont: 0x218
   __TEXT.__swift_as_ret: 0xac
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x254b8
+  __TEXT.__gcc_except_tab: 0x25584
   __TEXT.__ustring: 0x23a
-  __TEXT.__unwind_info: 0x10770
+  __TEXT.__unwind_info: 0x107d0
   __TEXT.__eh_frame: 0x2ae8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7010
-  __DATA_CONST.__objc_classlist: 0x1180
+  __DATA_CONST.__const: 0x6fe8
+  __DATA_CONST.__objc_classlist: 0x1188
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x7e8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x135b0
+  __DATA_CONST.__objc_selrefs: 0x13650
   __DATA_CONST.__objc_protorefs: 0x118
-  __DATA_CONST.__objc_superrefs: 0xda8
-  __DATA_CONST.__objc_arraydata: 0x920
-  __DATA_CONST.__got: 0x22c8
-  __AUTH_CONST.__const: 0x85d0
-  __AUTH_CONST.__cfstring: 0xe780
-  __AUTH_CONST.__objc_const: 0x48df0
+  __DATA_CONST.__objc_superrefs: 0xdb0
+  __DATA_CONST.__objc_arraydata: 0x958
+  __DATA_CONST.__got: 0x22d0
+  __AUTH_CONST.__const: 0x8688
+  __AUTH_CONST.__cfstring: 0xe7c0
+  __AUTH_CONST.__objc_const: 0x491d8
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_intobj: 0x918
-  __AUTH_CONST.__objc_arrayobj: 0x6c0
-  __AUTH_CONST.__objc_dictobj: 0x460
+  __AUTH_CONST.__objc_arrayobj: 0x6d8
+  __AUTH_CONST.__objc_dictobj: 0x488
   __AUTH_CONST.__objc_doubleobj: 0xb0
-  __AUTH_CONST.__auth_got: 0x1e28
-  __AUTH.__objc_data: 0xa698
-  __AUTH.__data: 0xc20
-  __DATA.__objc_ivar: 0x2cb8
-  __DATA.__data: 0x6d68
+  __AUTH_CONST.__auth_got: 0x1e30
+  __AUTH.__objc_data: 0xa680
+  __AUTH.__data: 0xbf8
+  __DATA.__objc_ivar: 0x2cdc
+  __DATA.__data: 0x6da0
   __DATA.__bss: 0x7030
   __DATA.__common: 0x160
-  __DATA_DIRTY.__objc_ivar: 0x115c
-  __DATA_DIRTY.__objc_data: 0x1810
-  __DATA_DIRTY.__data: 0x50
-  __DATA_DIRTY.__bss: 0x7c0
+  __DATA_DIRTY.__objc_ivar: 0x1178
+  __DATA_DIRTY.__objc_data: 0x1878
+  __DATA_DIRTY.__data: 0x78
+  __DATA_DIRTY.__bss: 0x7f0
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 18461
-  Symbols:   33099
-  CStrings:  3595
+  Functions: 18494
+  Symbols:   33152
+  CStrings:  3599
 
Symbols:
+ +[PKInkingTool _convertColorFromLight:toAppearance:]
+ +[PKInkingTool _isPureBlackOrWhite:]
+ +[PKTextInputLanguageSelectionController _scriptQualifiedLocaleIdentifiers]
+ +[PKTextInputLanguageSelectionController _transliterationInputModeRules]
+ -[PKColorMatrixView colorAppearance]
+ -[PKColorMatrixView setColorAppearance:]
+ -[PKColorPicker colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[PKColorPicker setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[PKDeviceLockStateObserver dealloc]
+ -[PKDrawingPaletteView _contentViewForTesting]
+ -[PKDrawingPaletteView _toolPickerViewForTesting]
+ -[PKDrawingPaletteView colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[PKDrawingPaletteView setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[PKInkAttributesPicker colorAppearance]
+ -[PKInkAttributesPicker setColorAppearance:]
+ -[PKMetalRenderer newComputeVertexBufferWithLength:outOffset:commandBuffer:]
+ -[PKMetalResourceHandlerBuffer deallocateReusableBuffers]
+ -[PKMetalResourceHandlerBuffer initWithSize:options:device:purgeable:initialReusableBufferCount:]
+ -[PKPaletteBaseColorPickerController colorAppearance]
+ -[PKPaletteBaseColorPickerController setColorAppearance:]
+ -[PKPaletteColorPickerView colorAppearance]
+ -[PKPaletteColorPickerView setColorAppearance:]
+ -[PKPaletteColorSwatch setColorAppearance:]
+ -[PKPaletteHostView _setPaletteDockedToHorizontalEdge:]
+ -[PKPaletteHostView _updateContextMenuAvoidanceRect]
+ -[PKPaletteHostView _usesCompactPaletteWidth]
+ -[PKPaletteHostView compactPaletteAvailableWidth]
+ -[PKPaletteMoreOptionsViewController cornerLocation]
+ -[PKPaletteMoreOptionsViewController edgeLocation]
+ -[PKPaletteMoreOptionsViewController preferredContentSize]
+ -[PKPaletteMoreOptionsViewController setCornerLocation:]
+ -[PKPaletteMoreOptionsViewController setEdgeLocation:]
+ -[PKPaletteStandardColorPickerController colorAppearance]
+ -[PKPaletteSystemColorPickerController _shouldConvertColorPickerColorFromDarkToLight:]
+ -[PKPaletteSystemColorPickerController colorAppearance]
+ -[PKPaletteSystemColorPickerController setColorAppearance:]
+ -[PKPaletteToolPickerAndColorPickerView compactPaletteWidth]
+ -[PKPaletteToolPickerAndColorPickerView setCompactPaletteWidth:]
+ -[PKPaletteToolPickerView _ensureFirstToolVisibleForRTLIfNeeded]
+ -[PKPaletteToolPickerView _isAllToolsColorAppearanceEqualsTo:]
+ -[PKPaletteToolPickerView colorAppearance]
+ -[PKPaletteToolPickerView setColorAppearance:]
+ -[PKPaletteToolPreview colorAppearance]
+ -[PKPaletteToolPreview setColorAppearance:]
+ -[PKPaletteToolView colorAppearance]
+ -[PKPaletteToolView setColorAppearance:]
+ -[PKPaletteView compactPaletteWidth]
+ -[PKPaletteView minimizedPaletteSizeScaleFactor]
+ -[PKSqueezePaletteView setColorAppearance:]
+ -[PKSqueezePaletteViewExpandedColorsLayout colorAppearanceDidChange]
+ -[PKSqueezePaletteViewExpandedInkingToolLayout colorAppearanceDidChange]
+ -[PKSqueezePaletteViewExpandedToolsLayout colorAppearanceDidChange]
+ -[PKSqueezePaletteViewMiniPaletteLayout colorAppearanceDidChange]
+ -[PKTextInputLanguageSelectionController ensureKeyboardLanguageConsistencyIfNeededWhileWriting:]
+ -[PKToolPicker _colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[PKToolPicker _setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[_PKColorAlphaSliderIOS colorUserInterfaceStyleOnlyConvertsBlackAndWhite]
+ -[_PKColorAlphaSliderIOS setColorUserInterfaceStyleOnlyConvertsBlackAndWhite:]
+ -[_PKInkAttributesPickerView colorAppearance]
+ -[_PKInkAttributesPickerView setColorAppearance:]
+ _$s7SwiftUI25_AppearanceActionModifierVAA04ViewE0AAMc
+ _$s7SwiftUI25_AppearanceActionModifierVAcA04ViewE0AAWL
+ _$s7SwiftUI25_AppearanceActionModifierVAcA04ViewE0AAWl
+ _$s7SwiftUI25_AppearanceActionModifierVN
+ _$s7SwiftUI5ColorVAA4ViewAAMc
+ _$s7SwiftUI5ColorVAcA4ViewAAWL
+ _$s7SwiftUI5ColorVAcA4ViewAAWl
+ _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyF
+ _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyyXEfU_
+ _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyyXEfU_TA
+ _$sIg_Ieg_TR
+ _$ss5NeverO7SwiftUI4ViewACMc
+ _$ss5NeverOAB7SwiftUI4ViewACWL
+ _$ss5NeverOAB7SwiftUI4ViewACWl
+ _OBJC_CLASS_$_PKDeviceLockStateObserver
+ _OBJC_IVAR_$_PKColorMatrixView._colorAppearance
+ _OBJC_IVAR_$_PKDeviceLockStateObserver._notifyToken
+ _OBJC_IVAR_$_PKMetalRenderer._computeVertexBuffer
+ _OBJC_IVAR_$_PKMetalRendererController._updateCycleRendererReadySemaphore
+ _OBJC_IVAR_$_PKMetalResourceHandlerBuffer._lock
+ _OBJC_IVAR_$_PKPaletteBaseColorPickerController._colorAppearance
+ _OBJC_IVAR_$_PKPaletteColorPickerView._colorAppearance
+ _OBJC_IVAR_$_PKPaletteColorSwatch._colorAppearance
+ _OBJC_IVAR_$_PKPaletteMoreOptionsViewController._cornerLocation
+ _OBJC_IVAR_$_PKPaletteMoreOptionsViewController._edgeLocation
+ _OBJC_IVAR_$_PKPaletteSystemColorPickerController._onlyConvertsBlackAndWhiteInDark
+ _OBJC_IVAR_$_PKPaletteToolPickerAndColorPickerView._compactPaletteWidth
+ _OBJC_IVAR_$_PKPaletteToolPickerView._colorAppearance
+ _OBJC_IVAR_$_PKPaletteToolPreview._colorAppearance
+ _OBJC_IVAR_$_PKPaletteToolView._colorAppearance
+ _OBJC_IVAR_$_PKSelectionInteraction._keyboardSuppressionPolicyDelegate
+ _OBJC_IVAR_$_PKSqueezePaletteColorSwatchButton._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteDrawingTool._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteMulticolorSwatchButton._colorAppearance
+ _OBJC_IVAR_$_PKSqueezePaletteView._colorAppearance
+ _OBJC_IVAR_$_PKToolPicker.__colorUserInterfaceStyleOnlyConvertsBlackAndWhite
+ _OBJC_METACLASS_$_PKDeviceLockStateObserver
+ _PKPaletteCompactCornerRadius
+ _PKPaletteCompactToolPickerTopMargin
+ _PKPaletteDragHandleTopMargin
+ _PKPaletteStatusBarEdgeMargin
+ _PKPaletteVerticalBarEdgeMargin
+ _PKPaletteVerticalBarEdgeMarginInHorizontal
+ _PKSmallButtonImageSymbolConfiguration
+ __OBJC_$_INSTANCE_METHODS_PKDeviceLockStateObserver
+ __OBJC_$_INSTANCE_VARIABLES_PKDeviceLockStateObserver
+ __OBJC_CLASS_PROTOCOLS_$_PKPaletteMoreOptionsViewController
+ __OBJC_CLASS_RO_$_PKDeviceLockStateObserver
+ __OBJC_METACLASS_RO_$_PKDeviceLockStateObserver
+ ___62-[PKMetalRendererController updateCyclePreCACommit:isDrawing:]_block_invoke_5
+ ___72+[PKTextInputLanguageSelectionController _transliterationInputModeRules]_block_invoke
+ ___75+[PKTextInputLanguageSelectionController _scriptQualifiedLocaleIdentifiers]_block_invoke
+ ___76-[PKMetalRenderer newComputeVertexBufferWithLength:outOffset:commandBuffer:]_block_invoke
+ ___PKBodyRegularFontSizeInPoints_block_invoke
+ ___block_descriptor_48_ea8_32s40s_e28_v16?0"<MTLCommandBuffer>"8ls32l8s40l8
+ _notify_cancel
- -[PKColorMatrixView _uiColorUserInterfaceStyle]
- -[PKColorMatrixView colorUserInterfaceStyle]
- -[PKColorMatrixView setColorUserInterfaceStyle:]
- -[PKDrawingPaletteView bottomLineDividerView]
- -[PKDrawingPaletteView setBottomLineDividerView:]
- -[PKInkAttributesPicker colorUserInterfaceStyle]
- -[PKInkAttributesPicker setColorUserInterfaceStyle:]
- -[PKMetalResourceHandler deallocateReusableBuffers]
- -[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]
- -[PKPaletteBaseColorPickerController colorUserInterfaceStyle]
- -[PKPaletteBaseColorPickerController setColorUserInterfaceStyle:]
- -[PKPaletteColorPickerView colorUserInterfaceStyle]
- -[PKPaletteColorPickerView setColorUserInterfaceStyle:]
- -[PKPaletteColorSwatch setColorUserInterfaceStyle:]
- -[PKPaletteInkingToolView _uiColorUserInterfaceStyle]
- -[PKPaletteStandardColorPickerController colorUserInterfaceStyle]
- -[PKPaletteSystemColorPickerController colorUserInterfaceStyle]
- -[PKPaletteSystemColorPickerController setColorUserInterfaceStyle:]
- -[PKPaletteToolPickerAndColorPickerView didMoveToWindow]
- -[PKPaletteToolPickerAndColorPickerView safeAreaInsetsDidChange]
- -[PKPaletteToolPickerView _ensureCorrectToolSelectionForRTLIfNeeded]
- -[PKPaletteToolPickerView _isAllToolsColorUserInterfaceStyleEqualsTo:]
- -[PKPaletteToolPickerView colorUserInterfaceStyle]
- -[PKPaletteToolPickerView setColorUserInterfaceStyle:]
- -[PKPaletteToolPreview colorUserInterfaceStyle]
- -[PKPaletteToolPreview setColorUserInterfaceStyle:]
- -[PKPaletteToolView colorUserInterfaceStyle]
- -[PKPaletteToolView setColorUserInterfaceStyle:]
- -[PKSqueezePaletteView setColorUserInterfaceStyle:]
- -[PKSqueezePaletteViewExpandedColorsLayout colorUserInterfaceStyleDidChange]
- -[PKSqueezePaletteViewExpandedInkingToolLayout colorUserInterfaceStyleDidChange]
- -[PKSqueezePaletteViewExpandedToolsLayout colorUserInterfaceStyleDidChange]
- -[PKSqueezePaletteViewMiniPaletteLayout colorUserInterfaceStyleDidChange]
- -[PKTextInputLanguageSelectionController ensureKeyboardLanguageConsistencyIfNeeded]
- -[_PKInkAttributesPickerView colorUserInterfaceStyle]
- -[_PKInkAttributesPickerView setColorUserInterfaceStyle:]
- _$s7SwiftUI25_AppearanceActionModifierVAA04ViewE0AAWP
- _$s7SwiftUI5ColorVAA4ViewAAWP
- _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC13isHighlightedSbvs
- _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyycfU_
- _$s9PencilKit33PKSqueezeVisualIntelligenceButton33_37F59D7289F7B321309FA7D662ED2685LLC22updateInteractionStateyyFyycfU_TA
- _$ss5NeverO7SwiftUI4ViewACWP
- _OBJC_IVAR_$_PKColorMatrixView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKMetalResourceHandler._gpuResourceBuffer
- _OBJC_IVAR_$_PKPaletteBaseColorPickerController._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteColorPickerView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteColorSwatch._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteToolPickerView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteToolPreview._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKPaletteToolView._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteColorSwatchButton._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteDrawingTool._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteMulticolorSwatchButton._colorUserInterfaceStyle
- _OBJC_IVAR_$_PKSqueezePaletteView._colorUserInterfaceStyle
- _PKPaletteCompactHardwareRatio
- _PKToolPickerCompactPillLayoutEnabled
- ___51-[PKMetalResourceHandler deallocateReusableBuffers]_block_invoke
- ___68-[PKPaletteToolPickerView _ensureCorrectToolSelectionForRTLIfNeeded]_block_invoke
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke_2
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke_3
- ___block_descriptor_48_ea8_32s40w_e28_v16?0"<MTLCommandBuffer>"8lw40l8s32l8
- ___block_descriptor_72_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:293: libc++ Hardening assertion __k != __leftmost failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:603: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:615: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:633: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:638: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:669: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:682: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:692: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:697: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__utility/is_pointer_in_range.h:38: libc++ Hardening assertion std::__is_valid_range(__begin, __end) failed: [__begin, __end) is not a valid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/list:1500: libc++ Hardening assertion this != std::addressof(__c) failed: list::splice(iterator, list) called with this == &list\n"
+ "Campo not supported on phone"
+ "LanguageController: Skipping keyboard language propagation while writing."
+ "Skip updating opacity label constraints, vertical offset: %{private}.2f, scaling factor: %{private}.2f"
+ "Update palette UI style: %{private}ld, color appearance: %{private}ld"
+ "mr-Translit"
+ "mr_Latn"
+ "\xf0q"
+ "\xf0\x911"
+ "\xf0\xe2\x81"
+ "\xf0\xf0\xf0\xf0\x81\x92"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:293: libc++ Hardening assertion __k != __leftmost failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:603: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:615: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:633: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:638: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:669: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:682: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:692: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:697: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__utility/is_pointer_in_range.h:38: libc++ Hardening assertion std::__is_valid_range(__begin, __end) failed: [__begin, __end) is not a valid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/list:1500: libc++ Hardening assertion this != std::addressof(__c) failed: list::splice(iterator, list) called with this == &list\n"
- "Graphing"
- "Notes"
- "Update palette UI style: %{private}ld, color UI style: %{private}ld"
- "\xf0\xa11"
- "\xf0ҁ"
- "\xf0\xf0\xf0\xf0q\x92"
```
