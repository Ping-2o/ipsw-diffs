## SoftwareUpdateServices

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices`

```diff

-1112.0.3.0.0
-  __TEXT.__text: 0x6aae8
+1114.40.10.0.0
+  __TEXT.__text: 0x6ae20
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0x7064
+  __TEXT.__objc_methlist: 0x708c
   __TEXT.__const: 0x5aa
   __TEXT.__gcc_except_tab: 0xc34
-  __TEXT.__cstring: 0x15491
+  __TEXT.__cstring: 0x154f1
   __TEXT.__oslogstring: 0x93c
   __TEXT.__swift5_typeref: 0x205
   __TEXT.__swift5_capture: 0x124

   __TEXT.__swift_as_entry: 0x58
   __TEXT.__swift_as_ret: 0x84
   __TEXT.__swift_as_cont: 0xa0
-  __TEXT.__unwind_info: 0x1f10
+  __TEXT.__unwind_info: 0x1f20
   __TEXT.__eh_frame: 0xc18
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4038
+  __DATA_CONST.__objc_selrefs: 0x4050
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x260
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x7c8
   __AUTH_CONST.__const: 0x990
-  __AUTH_CONST.__cfstring: 0xdf60
-  __AUTH_CONST.__objc_const: 0xdf18
+  __AUTH_CONST.__cfstring: 0xdfe0
+  __AUTH_CONST.__objc_const: 0xdf58
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x8b0
   __AUTH.__objc_data: 0xfd0
   __AUTH.__data: 0x128
-  __DATA.__objc_ivar: 0x6cc
+  __DATA.__objc_ivar: 0x6d0
   __DATA.__data: 0xa14
   __DATA.__bss: 0x350
   __DATA.__common: 0x8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2907
-  Symbols:   4796
-  CStrings:  2222
+  Functions: 2912
+  Symbols:   4802
+  CStrings:  2227
 
Symbols:
+ -[SUDownloadOptions personalizationServerURL]
+ -[SUDownloadOptions setPersonalizationServerURL:]
+ -[SUPreferences overridePersonalizationURL]
+ _OBJC_IVAR_$_SUDownloadOptions._personalizationServerURL
+ ___45-[SUDownloadOptions personalizationServerURL]_block_invoke
+ ___49-[SUDownloadOptions setPersonalizationServerURL:]_block_invoke
CStrings:
+ "\n            ClientName: %@\n            downloadOnly: %@\n            autoDownload: %@\n            userUpdateTonight: %@\n            allowUnrestrictedCellularDownload: %@\n            downloadFeeAgreementStatus: %@\n            termsAndConditionsAgreementStatus: %@\n            activeDownloadPolicyType: %@\n            enabledForCellular: %@\n            enabledForWifi: %@\n            enabledOnBatteryPower: %@\n            enabledForCellularRoaming: %@\n            personalizationServerURL: %@\n            descriptor: %@\n"
+ "\n            Publisher: %@\n            HumanReadableUpdateName: %@\n            ProductSystemName: %@\n            ProductVersion: %@\n            ProductVersionExtra: %@\n            ProductBuildVersion: %@\n            PrerequisiteBuild: %@\n            PrerequisiteOS: %@\n            ReleaseType: %@\n            DownloadSize: %llu\n            UnarchiveSize: %llu\n            MSUPrepareSize: %llu\n            PreparationSize: %llu\n            InstallationSize: %llu\n            PreSUStagingRequiredSize: %llu\n            PreSUStagingOptionalSize: %llu\n            MinFreeSpacePostStageOptionalAssets: %llu\n            UnentitledReserveAmount: %llu\n            PreSUStagingCacheDeleteLevel: %d\n            UpdateType: %@\n            Downloadable: %@\n            DownloadableOverCellular: %@\n            AutoDownloadableOverCellular: %@\n            AutoUpdateEnabled: %@\n            StreamingZipCapable: %@\n            TotalRequiredFreeSpace: %llu\n            Documentation: %@\n            SiriVoiceDeletion: %d\n            CDLevel4DeletionDisabled: %d\n            CDCriticalModeDisabled: %d\n            appDemotionDisabled: %d\n            maSuspensionDisabled: %d\n            installTonightDisabled: %d\n            rampEnabled: %d\n            badgingEnabled: %d\n            granularlyRamped: %d\n            setupCritical: %@\n            criticalOutOfBoxOnly: %d\n            criticalDownloadPolicy: %@\n            releaseDate: %@\n            mdmDelayInterval: %llu\n            assetID: %@\n            hideInstallAlert: %@\n            audienceType: %@\n            preferenceType: %@\n            upgradeType: %@\n            promoteAlternateUpdate: %@\n            isSplatOnly: %@\n            mandatoryUpdateEligible: %@\n            mandatoryUpdateVersionMin: %@\n            mandatoryUpdateVersionMax: %@\n            mandatoryUpdateOptional: %@\n            mandatoryUpdateRestrictedToOutOfTheBox: %@\n            forcePasscodeRequired: %@\n            allowAutoDownloadOnBattery: %@\n            autoDownloadOnBatteryDelay: %u day(s)\n            autoDownloadOnBatteryMinBattery: %u%%\n            isSplombo: %@\n            splatComboBuildVersion: %@\n            splatInstallDate: %@\n            splatRollbackDate: %@\n"
+ "!$"
+ "%s: [PREFERENCES] override allowAutoDownloadOnBattery to %d"
+ "%s: [PREFERENCES] override autoDownloadOnBatteryDelay to %.0lf"
+ "%s: autoDownloadOnBatteryDelay = %.0lf sec (~ %.2lf days)"
+ "%s: fullyUnrampedDate = %@ for %@; timeElapsed = %.0lf sec (~ %.2lf days)"
+ "If set, control if the device allows auto-downloading on battery"
+ "Override Tatsu personalization URL; used when the client does not supply one"
+ "SUHasEnoughBatteryForAutoDownloadForDescriptor"
+ "SUHasEnoughBatteryForDownloadForDescriptor"
+ "SUOverridePersonalizationURL"
+ "SURequiredBatteryLevelForAutoDownloadForDescriptor"
+ "SURequiredBatteryLevelForDownloadForDescriptor"
+ "_requiredBatteryLevelToAutoDownload"
+ "getCurrentBatteryLevel"
+ "personalizationServerURL"
- "\n            ClientName: %@\n            downloadOnly: %@\n            autoDownload: %@\n            userUpdateTonight: %@\n            allowUnrestrictedCellularDownload: %@\n            downloadFeeAgreementStatus: %@\n            termsAndConditionsAgreementStatus: %@\n            activeDownloadPolicyType: %@\n            enabledForCellular: %@\n            enabledForWifi: %@\n            enabledOnBatteryPower: %@\n            enabledForCellularRoaming: %@\n            descriptor: %@\n"
- "\n            Publisher: %@\n            HumanReadableUpdateName: %@\n            ProductSystemName: %@\n            ProductVersion: %@\n            ProductVersionExtra: %@\n            ProductBuildVersion: %@\n            PrerequisiteBuild: %@\n            PrerequisiteOS: %@\n            ReleaseType: %@\n            DownloadSize: %llu\n            UnarchiveSize: %llu\n            MSUPrepareSize: %llu\n            PreparationSize: %llu\n            InstallationSize: %llu\n            PreSUStagingRequiredSize: %llu\n            PreSUStagingOptionalSize: %llu\n            MinFreeSpacePostStageOptionalAssets: %llu\n            UnentitledReserveAmount: %llu\n            PreSUStagingCacheDeleteLevel: %d\n            UpdateType: %@\n            Downloadable: %@\n            DownloadableOverCellular: %@\n            AutoDownloadableOverCellular: %@\n            AutoUpdateEnabled: %@\n            StreamingZipCapable: %@\n            TotalRequiredFreeSpace: %llu\n            Documentation: %@\n            SiriVoiceDeletion: %d\n            CDLevel4DeletionDisabled: %d\n            CDCriticalModeDisabled: %d\n            appDemotionDisabled: %d\n            maSuspensionDisabled: %d\n            installTonightDisabled: %d\n            rampEnabled: %d\n            badgingEnabled: %d\n            granularlyRamped: %d\n            setupCritical: %@\n            criticalOutOfBoxOnly: %d\n            criticalDownloadPolicy: %@\n            releaseDate: %@\n            mdmDelayInterval: %llu\n            assetID: %@\n            hideInstallAlert: %@\n            audienceType: %@\n            preferenceType: %@\n            upgradeType: %@\n            promoteAlternateUpdate: %@\n            isSplatOnly: %@\n            mandatoryUpdateEligible: %@\n            mandatoryUpdateVersionMin: %@\n            mandatoryUpdateVersionMax: %@\n            mandatoryUpdateOptional: %@\n            mandatoryUpdateRestrictedToOutOfTheBox: %@\n            forcePasscodeRequired: %@\n            allowAutoDownloadOnBattery: %@\n            autoDownloadOnBatteryDelay: %u\n            autoDownloadOnBatteryMinbattery: %u%%\n            isSplombo: %@\n            splatComboBuildVersion: %@\n            splatInstallDate: %@\n            splatRollbackDate: %@\n"
- "!#"
- "BOOL SUHasEnoughBatteryForAutoDownloadForDescriptor(SUDescriptor *__strong _Nonnull, NSDate *__strong _Nonnull)"
- "BOOL SUHasEnoughBatteryForDownloadForDescriptor(SUDescriptor *__strong _Nonnull)"
- "If set to true, allow auto-downloading on battery"
- "NSNumber * _Nonnull SURequiredBatteryLevelForDownloadForDescriptor(SUDescriptor *__strong _Nonnull)"
- "NSNumber *getCurrentBatteryLevel(void)"
- "autoDownloadOnBatteryDelay = %.0lf sec (~ %.2lf days)"
- "autoDownloadOnBatteryDelay is set to %.0lf sec by default"
- "fullyUnrampedDate = %@ for %@; timeElapsed = %.0lf sec (~ %.2lf days)"
- "unsigned int _requiredBatteryLevelToAutoDownload(SUDescriptor *__strong _Nonnull, BOOL, BOOL)"
```
