## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-3600.68.61.11.11
-  __TEXT.__text: 0x3f80
-  __TEXT.__auth_stubs: 0x470
-  __TEXT.__objc_stubs: 0xbc0
-  __TEXT.__objc_methlist: 0x1d0
+3605.31.1.11.2
+  __TEXT.__text: 0x4734
+  __TEXT.__auth_stubs: 0x4c0
+  __TEXT.__objc_stubs: 0xc60
+  __TEXT.__objc_methlist: 0x218
   __TEXT.__const: 0x34
-  __TEXT.__cstring: 0x90c
-  __TEXT.__oslogstring: 0xa79
+  __TEXT.__cstring: 0xa14
+  __TEXT.__oslogstring: 0xf28
   __TEXT.__objc_classname: 0xd
-  __TEXT.__objc_methname: 0x9d3
-  __TEXT.__objc_methtype: 0x47
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__objc_methname: 0xbc6
+  __TEXT.__objc_methtype: 0x90
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__const: 0x10
-  __DATA_CONST.__cfstring: 0x680
+  __DATA_CONST.__cfstring: 0x740
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x240
-  __DATA_CONST.__got: 0x130
+  __DATA_CONST.__auth_got: 0x268
+  __DATA_CONST.__got: 0x138
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x318
+  __DATA.__objc_selrefs: 0x340
   __DATA.__objc_data: 0x50
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 40
-  Symbols:   121
-  CStrings:  234
+  Functions: 46
+  Symbols:   126
+  CStrings:  262
 
Symbols:
+ _AFIsHomePod
+ _AFIsLinwoodEnabled
+ _TCCAccessReset
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x27
+ _objc_retain_x5
- _AFIsHorseman
- _objc_release_x25
- _objc_retain_x25
CStrings:
+ "%s App Access exclusion list migration has already been performed (isRestorePass=%{BOOL}d). Skipping."
+ "%s App Clips: \"Learn from App Clips\" is OFF — adding com.apple.app-clips to deny set."
+ "%s App Clips: \"Learn from App Clips\" is ON (or unset/default) — not adding from this signal."
+ "%s Failed to reset kTCCServiceSiriAccess entries. Proceeding with migration anyway (writes are idempotent)."
+ "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
+ "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
+ "%s Marking restore-pass App Access exclusion list migration as complete."
+ "%s Not recording the backed-up App Access exclusion list marker (disposition=0x%lx, alreadyPresent=%{BOOL}d)."
+ "%s Pre-migration reset check: hasV1Flag=%{BOOL}d, isLinwoodEnabled=%{BOOL}d, isRestorePass=%{BOOL}d"
+ "%s Recording the backed-up App Access exclusion list marker so a restore from this device skips re-derivation."
+ "%s Resetting all kTCCServiceSiriAccess entries."
+ "%s Restore-from-backup pass (restoredBackupBuildVersion=%@, backedUpMigratedMarker=%{BOOL}d) — the backup already carries a curated exclusion list. Leaving the restored kTCCServiceSiriAccess records alone."
+ "%s Restore-from-backup pass (restoredBackupBuildVersion=%@, backedUpMigratedMarker=%{BOOL}d) — the backup predates the exclusion list. Re-deriving even though the standard one-shot flag may be set."
+ "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, Locked (excluded): %lu, AppClips-Learn-off: %@, union to migrate: %lu."
+ "%s Successfully reset kTCCServiceSiriAccess entries."
+ "(unknown)"
+ "-[SiriMigrator _markAppAccessExclusionListMigratedInBackedUpDomainForDisposition:]"
+ "AppAccessExclusionListMigrated"
+ "AppAccessExclusionListMigrationPerformedV2"
+ "AppAccessExclusionListRestoreMigrationPerformed"
+ "B24@0:8@16"
+ "B24@0:8I16B20"
+ "B28@0:8@16B24"
+ "SuggestionsLearnFromAppClips"
+ "_appAccessExclusionListMigrationActionForRestorePass:restoreMigrationAlreadyPerformed:migrationAlreadyPerformed:restoredBackupBuildVersion:hasBackedUpMigratedMarker:"
+ "_backupBuildVersionPredatesAppAccessExclusionList:"
+ "_markAppAccessExclusionListMigratedInBackedUpDomain"
+ "_markAppAccessExclusionListMigratedInBackedUpDomainForDisposition:"
+ "_markAppAccessExclusionListRestoreMigrationPerformed"
+ "_shouldRederiveAppAccessExclusionListForRestoredBackupBuildVersion:hasBackedUpMigratedMarker:"
+ "_shouldWriteBackedUpAppAccessExclusionListMarkerForDisposition:markerAlreadyPresent:"
+ "characterAtIndex:"
+ "com.apple.app-clips"
+ "isEnabledForDataclass:"
+ "length"
+ "q40@0:8B16B20B24@28B36"
+ "uppercaseString"
+ "v20@0:8I16"
- "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@, Locked=%@]"
- "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@, Locked=%@]"
- "%s One-time App Access exclusion list migration has already been performed. Skipping."
- "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, Locked: %lu, Hidden (excluded): %lu, union to migrate: %lu."
- "_bundleIdsWithHiddenApps"
- "cloudSyncEnabled"
- "hiddenAppBundleIdentifiers"
- "saveAccount:withCompletionHandler:"
- "set"
- "setEnabled:forDataclass:"
```
