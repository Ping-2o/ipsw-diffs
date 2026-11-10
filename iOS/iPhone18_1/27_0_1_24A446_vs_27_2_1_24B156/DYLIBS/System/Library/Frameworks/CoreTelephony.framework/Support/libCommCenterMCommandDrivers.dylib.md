## libCommCenterMCommandDrivers.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterMCommandDrivers.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-13487.7.0.0.0
-  __TEXT.__text: 0x214c98
+13499.0.0.0.0
+  __TEXT.__text: 0x214d70
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1cc
   __TEXT.__const: 0x26a78
   __TEXT.__cstring: 0xcbd0
-  __TEXT.__gcc_except_tab: 0x1e168
+  __TEXT.__gcc_except_tab: 0x1e184
   __TEXT.__oslogstring: 0x1841a
   __TEXT.__unwind_info: 0xf400
   __TEXT.__objc_stubs: 0x0

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xb428
+  __DATA_CONST.__const: 0xb408
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
   __DATA_CONST.__objc_selrefs: 0xe8
   __DATA_CONST.__got: 0x510
-  __AUTH_CONST.__const: 0x21910
+  __AUTH_CONST.__const: 0x21940
   __AUTH_CONST.__cfstring: 0x240
   __AUTH_CONST.__objc_const: 0x798
   __AUTH_CONST.__weak_auth_got: 0x18
Symbols:
+ __ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEbNS2_8functionIFvbEEE
+ __ZN33DataSubscriptionBaseCommandDriver20configureUsableIccidEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEbNS2_8functionIFvbEEE
+ ____ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEbNS2_8functionIFvbEEE_block_invoke
- __ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEb
- __ZN33DataSubscriptionBaseCommandDriver20configureUsableIccidEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEb
- ____ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEb_block_invoke
Functions:
~ __ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEb -> __ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEbNS2_8functionIFvbEEE : 1020 -> 1200
~ ____ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEb_block_invoke -> ____ZN32QMIDataSubscriptionCommandDriver31handleConfigureUsableIccid_syncEN10subscriber15HardwareSimSlotERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEbNS2_8functionIFvbEEE_block_invoke : 132 -> 168
~ __ZNSt3__124__put_character_sequenceB9foe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m -> ____ZNO3qmi12ClientRouter9SendProxy8callbackINSt3__18functionIFvRKNS_12ResponseBaseEEEEEEOS1_OT__block_invoke : 420 -> 68
~ __ZNSt3__116__pad_and_outputB9foe220106IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_ -> __ZNSt3__124__put_character_sequenceB9foe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m : 396 -> 420
~ ____ZNO3qmi12ClientRouter9SendProxy8callbackINSt3__18functionIFvRKNS_12ResponseBaseEEEEEEOS1_OT__block_invoke -> __ZNSt3__116__pad_and_outputB9foe220106IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_ : 68 -> 396
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
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__bit_reference:113: libc++ Hardening assertion __ctz + __clz < sizeof(_StorageType) * 8 failed: __fill_masked_range called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/array:279: libc++ Hardening assertion __n < _Size failed: out-of-bounds access in std::array<T, N>\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/deque:1565: libc++ Hardening assertion !empty() failed: deque::front called on an empty deque\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/deque:2199: libc++ Hardening assertion !empty() failed: deque::pop_front called on an empty deque\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/deque:2213: libc++ Hardening assertion !empty() failed: deque::pop_back called on an empty deque\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/optional:1121: libc++ Hardening assertion this->has_value() failed: optional operator-> called on a disengaged value\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/optional:1130: libc++ Hardening assertion this->has_value() failed: optional operator* called on a disengaged value\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/optional:1139: libc++ Hardening assertion this->has_value() failed: optional operator* called on a disengaged value\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:1362: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:1371: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:1502: libc++ Hardening assertion !empty() failed: string::back(): string is empty\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:3374: libc++ Hardening assertion __pos != end() failed: string::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:3384: libc++ Hardening assertion __first <= __last failed: string::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:3393: libc++ Hardening assertion !empty() failed: string::pop_back(): string is already empty\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string_view:343: libc++ Hardening assertion (__end - __begin) >= 0 failed: std::string_view::string_view(iterator, sentinel) received invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:293: libc++ Hardening assertion __k != __leftmost failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:603: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:615: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:633: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:638: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:669: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:682: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:692: libc++ Hardening assertion __first != __end failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__algorithm/sort.h:697: libc++ Hardening assertion __last != __begin failed: Would read out of bounds, does your comparator satisfy the strict-weak ordering requirement?\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__bit_reference:113: libc++ Hardening assertion __ctz + __clz < sizeof(_StorageType) * 8 failed: __fill_masked_range called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/array:279: libc++ Hardening assertion __n < _Size failed: out-of-bounds access in std::array<T, N>\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/deque:1565: libc++ Hardening assertion !empty() failed: deque::front called on an empty deque\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/deque:2199: libc++ Hardening assertion !empty() failed: deque::pop_front called on an empty deque\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/deque:2213: libc++ Hardening assertion !empty() failed: deque::pop_back called on an empty deque\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/optional:1121: libc++ Hardening assertion this->has_value() failed: optional operator-> called on a disengaged value\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/optional:1130: libc++ Hardening assertion this->has_value() failed: optional operator* called on a disengaged value\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/optional:1139: libc++ Hardening assertion this->has_value() failed: optional operator* called on a disengaged value\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1362: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1371: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1502: libc++ Hardening assertion !empty() failed: string::back(): string is empty\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:3374: libc++ Hardening assertion __pos != end() failed: string::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:3384: libc++ Hardening assertion __first <= __last failed: string::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:3393: libc++ Hardening assertion !empty() failed: string::pop_back(): string is already empty\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string_view:343: libc++ Hardening assertion (__end - __begin) >= 0 failed: std::string_view::string_view(iterator, sentinel) received invalid range\n"
```
