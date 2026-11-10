## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase`

```diff

-1291.0.0.0.0
-  __TEXT.__text: 0xdc2a0
-  __TEXT.__objc_methlist: 0x1f0c
-  __TEXT.__cstring: 0x1fa88
+1291.2.3.0.0
+  __TEXT.__text: 0xdc940
+  __TEXT.__objc_methlist: 0x1f24
+  __TEXT.__cstring: 0x1fb91
   __TEXT.__const: 0xaa4
-  __TEXT.__gcc_except_tab: 0x18dc
-  __TEXT.__oslogstring: 0xcbe7
+  __TEXT.__gcc_except_tab: 0x18f0
+  __TEXT.__oslogstring: 0xcdd0
   __TEXT.__dlopen_cstrs: 0x60
-  __TEXT.__unwind_info: 0x2d20
+  __TEXT.__unwind_info: 0x2d28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_arraydata: 0x38
   __DATA_CONST.__got: 0x9a0
   __AUTH_CONST.__const: 0x2150
-  __AUTH_CONST.__cfstring: 0xca80
+  __AUTH_CONST.__cfstring: 0xcb00
   __AUTH_CONST.__objc_const: 0x37d0
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH_CONST.__auth_got: 0xfe0
-  __AUTH.__objc_data: 0xa00
+  __AUTH_CONST.__auth_got: 0xfd8
+  __AUTH.__objc_data: 0x550
   __DATA.__objc_ivar: 0x1b4
   __DATA.__data: 0x1360
   __DATA.__bss: 0x330
   __DATA.__common: 0x20
-  __DATA_DIRTY.__objc_data: 0x320
+  __DATA_DIRTY.__objc_data: 0x7d0
   __DATA_DIRTY.__data: 0x1f8
   __DATA_DIRTY.__bss: 0xf0
   __DATA_DIRTY.__common: 0x28

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 4248
-  Symbols:   6556
-  CStrings:  3123
+  Functions: 4253
+  Symbols:   6562
+  CStrings:  3131
 
Symbols:
+ -[CalSingleDatabaseInMemoryChangeTimestamp hash]
+ -[CalSingleDatabaseInMemoryChangeTimestamp isEqual:]
+ GCC_except_table149
+ GCC_except_table30
+ GCC_except_table342
+ GCC_except_table345
+ GCC_except_table57
+ _CalDatabaseClearDefaultCalendarIfDefaultIsInAuxDatabaseWithID
+ _CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded
+ _CalDatabaseSaveWithOptionsAndOutSelfTimestamp
+ _CalPersonaUtilsErrorDomain
+ __CalAttachmentFileResolveLocalURLReArchivingIfNeeded
- GCC_except_table148
- GCC_except_table340
- GCC_except_table53
- GCC_except_table56
- _NSURLCreationDateKey
- _UnzipArchive
CStrings:
+ "%@.zip"
+ "AutoArchivedPathMigrationCompleted"
+ "Aux database containing the default calendar was deleted"
+ "CalCalendarRef CalDatabaseCopyDefaultOrAnyReadWriteCalendarForNewEvents(CalDatabaseRef, CalStoreRef, BOOL)"
+ "CalCalendarRef CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded(CalDatabaseRef, BOOL)"
+ "Could not get a container info for account ID %{public}@: %@"
+ "Could not get new calendar data container. store uuid = %{public}@: %@"
+ "Could not open %@: %s"
+ "Couldn't get container info for persona %{public}@. Using main database for this persona. error = %@"
+ "Couldn't look up persona %{public}@: %@"
+ "Couldn't look up persona ID %{public}@: %@"
+ "Failed to get URL for data container of account %{public}@: %@"
+ "Failed to get container info for account [%{public}@]: %@"
+ "Failed to get container info for persona %{public}@: %@"
+ "UPDATE AttachmentFile SET local_path = local_path || '.zip' WHERE (flags & %d) != 0 AND SUBSTR(local_path, -4) != '.zip';"
+ "UPDATE AttachmentFile SET local_path = local_path || '.zip' WHERE (flags & %d) != 0;"
+ "Unable to re-archive attachment data: %@"
+ "_CalAttachmentFileGetAttachmentContainerURLsForStoreProperties: Failed to get container for account %{public}@: %@"
+ "_CalAttachmentFileGetCalendarDataContainerForAttachmentFile: Failed to get container for account %{public}@: %@"
+ "_CalAttachmentFileMigrateAttachmentsInStoreFromOldPersistentIDToNewPersistentID: Failed to get container for account %{public}@: %@"
+ "commit at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4352"
+ "rollback at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalDatabase.m:5068"
+ "write at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4329"
- "Attachment cleanup: skipping removing file because it is archived and is too young: %@"
- "CalCalendarRef CalDatabaseCopyDefaultOrAnyReadWriteCalendarForNewEvents(CalDatabaseRef, CalStoreRef)"
- "CalCalendarRef CalDatabaseCopyOrCreateDefaultCalendarForNewEvents(CalDatabaseRef)"
- "Could not get new calendar data container. store uuid = %{public}@"
- "Couldn't get container info for persona %{public}@. Using main database for this persona."
- "Couldn't look up persona %{public}@"
- "Couldn't look up persona ID %{public}@"
- "Error checking creation date for %@: %@"
- "Failed to unzip attachment (error: %@)."
- "SiriCanLearnFromAppBlacklist"
- "Unable to archive data: %@"
- "com.apple.suggestions.settingsChanged"
- "commit at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4339"
- "rollback at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalDatabase.m:5055"
- "write at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4316"
```
