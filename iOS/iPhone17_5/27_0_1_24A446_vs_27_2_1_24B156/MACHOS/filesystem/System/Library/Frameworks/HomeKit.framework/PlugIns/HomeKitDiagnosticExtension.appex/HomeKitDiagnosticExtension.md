## HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1493.1.5.1.1
-  __TEXT.__text: 0x2473c
-  __TEXT.__auth_stubs: 0x990
-  __TEXT.__objc_stubs: 0x3aa0
-  __TEXT.__objc_methlist: 0x1f9c
+1520.2.7.1.3
+  __TEXT.__text: 0x27e70
+  __TEXT.__auth_stubs: 0x9b0
+  __TEXT.__objc_stubs: 0x3dc0
+  __TEXT.__objc_methlist: 0x1fac
   __TEXT.__const: 0xe0
-  __TEXT.__gcc_except_tab: 0x8fc
-  __TEXT.__cstring: 0x1bec
-  __TEXT.__oslogstring: 0x4cd3
-  __TEXT.__objc_methname: 0x3ed3
+  __TEXT.__gcc_except_tab: 0x900
+  __TEXT.__cstring: 0x232d
+  __TEXT.__oslogstring: 0x54d7
+  __TEXT.__objc_methname: 0x4037
   __TEXT.__objc_classname: 0x891
-  __TEXT.__objc_methtype: 0x63e
-  __TEXT.__unwind_info: 0x748
-  __DATA_CONST.__const: 0x838
-  __DATA_CONST.__cfstring: 0x23a0
+  __TEXT.__objc_methtype: 0x68a
+  __TEXT.__ustring: 0x168
+  __TEXT.__unwind_info: 0x768
+  __DATA_CONST.__const: 0x8a0
+  __DATA_CONST.__cfstring: 0x2fc0
   __DATA_CONST.__objc_classlist: 0x200
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x68

   __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__objc_arrayobj: 0x30
-  __DATA_CONST.__auth_got: 0x4d8
-  __DATA_CONST.__got: 0x448
-  __DATA.__objc_const: 0x4598
-  __DATA.__objc_selrefs: 0x12f8
-  __DATA.__objc_ivar: 0x118
+  __DATA_CONST.__auth_got: 0x4e8
+  __DATA_CONST.__got: 0x460
+  __DATA.__objc_const: 0x45c8
+  __DATA.__objc_selrefs: 0x13c8
+  __DATA.__objc_ivar: 0x11c
   __DATA.__objc_data: 0x1400
   __DATA.__data: 0x4e0
   __DATA.__bss: 0x168

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 628
-  Symbols:   301
-  CStrings:  1598
+  Functions: 639
+  Symbols:   306
+  CStrings:  1758
 
Symbols:
+ _HMAccessoryTransportTypesToString
+ _HMResidentDeviceStatusDescription
+ _HomeUtilAggregateRoomsKey
+ _HomeUtilAggregateThermostatsKey
+ _OBJC_CLASS_$_NSLock
CStrings:
+ "\nNo homes found.\n"
+ "          Humidities: %@\n"
+ "          Temperatures: %@\n"
+ "        %@ (%@)\n"
+ "      - \"%@\" [%@] %@%@\n"
+ "      Aggregated Humidity:        %.2f%%\n"
+ "      Aggregated Humidity: %.2f%%\n"
+ "      Aggregated Temperature:     %.2f°C\n"
+ "      Aggregated Temperature: %.2f°C\n"
+ "      Humidity Sensor Priority: %@\n"
+ "      Last Published Humidity:    %.2f%%\n"
+ "      Last Published Humidity:    null\n"
+ "      Last Published Temperature: %.2f°C\n"
+ "      Last Published Temperature: null\n"
+ "      Monitored Rooms (%lu):\n"
+ "      Monitors All Rooms: %@\n"
+ "      Sensors:\n"
+ "      Service Rooms (%lu):\n"
+ "      Service Rooms: (none)\n"
+ "      Temperature Sensor Priority: %@\n"
+ "      Use Service Rooms: %@\n"
+ "    %@ (%@)\n"
+ "    - \"%@\" %@%@ status=%@ enabled=%@\n"
+ "    Blocked: %@\n"
+ "    Bridged: %@\n"
+ "    Category: %@ (%@)\n"
+ "    Device ID: %@\n"
+ "    Firmware: %@\n"
+ "    Identifier: %@\n"
+ "    Manufacturer: %@\n"
+ "    Matter Node ID: %@\n"
+ "    Model: %@\n"
+ "    Reachable Transports: %@ (0x%lX)\n"
+ "    Reachable: %@\n"
+ "    Room: %@\n"
+ "    Serial: %@\n"
+ "    Services (%lu):\n"
+ "    Transport Types: %@ (0x%lX)\n"
+ "  (not primary resident for this home or no data)\n\n"
+ "  Accessories: %lu\n"
+ "  Accessory: \"%@\"\n"
+ "  Hub State: %@\n"
+ "  Identifier: %@\n"
+ "  Primary: %@\n"
+ "  Residents (%lu):\n"
+ "  Rooms:\n"
+ "  Rooms: %lu\n"
+ "  Thermostats:\n"
+ "  → Aggregate climate data not available or device is not primary resident"
+ "  → Fetching aggregate climate data for home %{public}@"
+ "  → No aggregate climate data available"
+ "  → No aggregate climate data to write"
+ "  → Skipping: device is not the primary resident"
+ "  ✓ Aggregate climate data collected"
+ "  ✓ Home app Spotlight donations collected"
+ "  ✓ homed Spotlight donations collected"
+ "  ✓ homeutil mini dump collected"
+ "  ✗ Failed to collect Home app Spotlight donations"
+ "  ✗ Failed to collect homed Spotlight donations"
+ "  ✗ Failed to fetch aggregate climate data for home %{public}@: %@"
+ "  ✗ Failed to write aggregate climate data: %@"
+ "  ✗ Timed out waiting for aggregate climate data"
+ " (primary)"
+ "%@ / 0x%llX"
+ "%@-spotlight-donations.txt"
+ "(unknown)"
+ "<private>"
+ "AirPlay"
+ "BLE"
+ "Connected"
+ "Disconnected"
+ "Failed to write homeutil mini dump: %@"
+ "Generated: %@\n"
+ "Home App Spotlight Donation"
+ "Home: \"%@\"\n"
+ "Home: %@\n\n"
+ "HomeUtil accessory climate fetch-aggregate-data"
+ "IP"
+ "Not Available"
+ "Refusing homeutil mini dump on non-customer/SEED build"
+ "Refusing homeutil mini dump without user consent"
+ "Resident"
+ "STEP %lu/%lu: Collecting Aggregate Climate Data"
+ "STEP %lu/%lu: Collecting Home app Spotlight Donations"
+ "STEP %lu/%lu: Collecting homed Spotlight Donations"
+ "Unknown (%lu)"
+ "[%{public}@]   → Aggregate climate data not available or device is not primary resident"
+ "[%{public}@]   → Fetching aggregate climate data for home %{public}@"
+ "[%{public}@]   → No aggregate climate data available"
+ "[%{public}@]   → No aggregate climate data to write"
+ "[%{public}@]   → Skipping: device is not the primary resident"
+ "[%{public}@]   ✓ Aggregate climate data collected"
+ "[%{public}@]   ✓ Home app Spotlight donations collected"
+ "[%{public}@]   ✓ homed Spotlight donations collected"
+ "[%{public}@]   ✓ homeutil mini dump collected"
+ "[%{public}@]   ✗ Failed to collect Home app Spotlight donations"
+ "[%{public}@]   ✗ Failed to collect homed Spotlight donations"
+ "[%{public}@]   ✗ Failed to fetch aggregate climate data for home %{public}@: %@"
+ "[%{public}@]   ✗ Failed to write aggregate climate data: %@"
+ "[%{public}@]   ✗ Timed out waiting for aggregate climate data"
+ "[%{public}@] Failed to write homeutil mini dump: %@"
+ "[%{public}@] Refusing homeutil mini dump on non-customer/SEED build"
+ "[%{public}@] Refusing homeutil mini dump without user consent"
+ "[%{public}@] STEP %lu/%lu: Collecting Aggregate Climate Data"
+ "[%{public}@] STEP %lu/%lu: Collecting Home app Spotlight Donations"
+ "[%{public}@] STEP %lu/%lu: Collecting homed Spotlight Donations"
+ "[%{public}@] customerOS / SEED build: consent=%@"
+ "[CURRENT] "
+ "[PRIMARY] "
+ "accessories"
+ "accessoryName"
+ "accessoryUUID"
+ "aggregatedHumidity"
+ "aggregatedTemperature"
+ "category"
+ "categoryType"
+ "char %@: %.2f%%"
+ "char %@: %.2f°C"
+ "customerOS / SEED build: consent=%@"
+ "false"
+ "fetchAggregateClimateDataForDiagnosticsWithCompletion:"
+ "firmwareVersion"
+ "homeHubState"
+ "homed Spotlight Donation"
+ "homeutil Mini Dump"
+ "homeutil Mini Dump\n"
+ "homeutil-aggregate-climate-data.txt"
+ "homeutil-mini-dump.txt"
+ "humidities"
+ "humiditySensorPriorityState"
+ "isBlocked"
+ "isBridged"
+ "isEnabled"
+ "isPrimary"
+ "isPrimaryService"
+ "isReachable"
+ "lastPublishedHumidity"
+ "lastPublishedTemperature"
+ "localizedDescription"
+ "lock"
+ "manufacturer"
+ "matterNodeID"
+ "model"
+ "monitoredRoomUUIDs"
+ "monitorsAllRooms"
+ "reachableTransports"
+ "roomName"
+ "roomUUID"
+ "rooms"
+ "search -b com.apple.%@ -A"
+ "sensors"
+ "serialNumber"
+ "serviceRoomUUIDs"
+ "serviceType"
+ "services"
+ "temperatureSensorPriorityState"
+ "temperatures"
+ "thermostatName"
+ "thermostatUUID"
+ "transportTypes"
+ "true"
+ "uniqueIdentifier"
+ "unlock"
+ "useServiceRooms"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
+ "version14_1"
+ "{hmf_unfair_data_lock_s=\"lock\"{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}}"
+ "|"
+ "════════════════════════════════════════\n"
- "  ✓ Spotlight donations collected"
- "  ✗ Failed to collect Spotlight donations"
- "STEP %lu/%lu: Collecting Spotlight Donations"
- "Spotlight Donation"
- "[%{public}@]   ✓ Spotlight donations collected"
- "[%{public}@]   ✗ Failed to collect Spotlight donations"
- "[%{public}@] STEP %lu/%lu: Collecting Spotlight Donations"
- "homed-spotlight-donations.txt"
- "search -b com.apple.homed -A"
```
