## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

```diff

-980.77.1.2.0
-  __TEXT.__text: 0x244090
-  __TEXT.__objc_methlist: 0x7ec
-  __TEXT.__cstring: 0x8ec83
-  __TEXT.__const: 0x61f0
-  __TEXT.__gcc_except_tab: 0xa88
-  __TEXT.__dlopen_cstrs: 0x5c1
+1005.13.1.2.0
+  __TEXT.__text: 0x248874
+  __TEXT.__objc_methlist: 0x81c
+  __TEXT.__cstring: 0x90206
+  __TEXT.__const: 0x6190
+  __TEXT.__gcc_except_tab: 0xaf4
+  __TEXT.__dlopen_cstrs: 0x61a
   __TEXT.__oslogstring: 0x1009
-  __TEXT.__unwind_info: 0x58c0
+  __TEXT.__unwind_info: 0x5988
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x76a8
+  __DATA_CONST.__const: 0x77f8
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb08
+  __DATA_CONST.__objc_selrefs: 0xb78
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__objc_arraydata: 0x170
-  __DATA_CONST.__got: 0x2388
-  __AUTH_CONST.__const: 0x7780
-  __AUTH_CONST.__cfstring: 0x148e0
+  __DATA_CONST.__got: 0x23d8
+  __AUTH_CONST.__const: 0x77d0
+  __AUTH_CONST.__cfstring: 0x14ac0
   __AUTH_CONST.__objc_const: 0xed0
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_intobj: 0x150

   __AUTH.__objc_data: 0x190
   __AUTH.__data: 0x878
   __DATA.__objc_ivar: 0x88
-  __DATA.__data: 0x18690
-  __DATA.__bss: 0x608
+  __DATA.__data: 0x18620
+  __DATA.__bss: 0x618
   __DATA.__common: 0xa04
   __DATA_DIRTY.__objc_data: 0xa0
-  __DATA_DIRTY.__data: 0xf78
+  __DATA_DIRTY.__data: 0xfe8
   __DATA_DIRTY.__bss: 0x788
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
   - /System/Library/Frameworks/CoreAudio.framework/CoreAudio

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 11443
-  Symbols:   8664
-  CStrings:  11583
+  Functions: 11505
+  Symbols:   8723
+  CStrings:  11690
 
Symbols:
+ -[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]
+ -[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeer:groupID:]
+ -[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeersForGroup:peers:]
+ -[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]
+ GCC_except_table131
+ GCC_except_table26
+ GCC_except_table31
+ GCC_except_table33
+ GCC_except_table50
+ _APCarPlayCarNeedsVTAlwaysActive
+ _APEndpointCopyAudioOutputLatencyMsForStream
+ _APEndpointPayloadRequiresCompositionRefresh
+ _APPairingClientCoreUtilsCopyMigratableUngroupedPeers
+ _APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo
+ _APPairingClientCoreUtilsMigrateUngroupedPeers
+ _APPairingClientCoreUtilsPatchUnpairedPeerWithGroupID
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
+ _APSCMTimeMakeWithRTPTimestamp
+ _APSGetSurroundRoleFromClusterMemberID
+ _APSIsHomeAccessory
+ _APSIsHomeTheaterSurroundEnabled
+ _APSIsUpdateInfoForwardingEnabled
+ _APSenderSessionGetFallbackToInfraReasonForUnselectedTransport
+ _APTDiagnosticSendStreamInfo
+ _APTNANDataSessionGetDatapathRSSI
+ _APTransportConnectionQoSFromSocketQoS
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _APTransportTrafficCapturePrepareForCollection
+ _FigCFNumberGetCFIndex
+ _FigCFSetGetCount
+ _FigEndpointSetProperty
+ _OBJC_CLASS_$_CUSystemMonitor
+ ___60-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]_block_invoke
+ ___63-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]_block_invoke
+ ___APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo_block_invoke
+ ___APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo_block_invoke_2
+ ___APPairingClientCoreUtilsMigrateUngroupedPeers_block_invoke
+ ___block_descriptor_40_e8_32o_e15_v24?0r^v8r^v16ls32l8
+ ___block_descriptor_48_e8_32o40o_e29_v32?0"CUPairedPeer"8Q16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32o40r_e29_v24?0"NSArray"8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32o40r_e34_v32?0"NSString"8"NSArray"16^B24ls32l8r40l8
+ ___block_descriptor_56_e15_v24?0r^v8r^v16l
+ ___carEndpoint_handleVideoPlayerBackButtonEvent_block_invoke
+ ___coreUtilsPairing_updatePairingGroupInfoIfNeeded_block_invoke_2
+ ___endpointCluster_reconcileResponsiveAudioTransports_block_invoke
+ ___endpoint_performRemoteTeardown_block_invoke
+ ___endpoint_performRemoteTeardown_block_invoke_2
+ ___endpoint_performRemoteTeardown_block_invoke_3
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_2
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_3
+ ___manager_create_block_invoke_6
+ _airPlayDescription_isAppleHomeAccessory
+ _bufferedAudioEngine_isHoseClusterBuddy
+ _carManager_reportBonjourEventToCarKit
+ _carManager_reportBonjourSuccessIfNeeded
+ _emp_demoteEndpoint
+ _endpointAggregate_handleAudioStreamResumed
+ _endpointCluster_activateSubEndpointForcingTransportIfNeeded
+ _endpointCluster_copyActivatedSubEndpointsByTransportType
+ _endpointCluster_copyActivationOptionsForcingTransportType
+ _endpointCluster_copyForcedTransportForResponsiveAudio
+ _endpointCluster_failDelayMSecsForFailureCount.kFailDelayLadderPercent
+ _endpointCluster_failureCountForSubEndpoint
+ _endpoint_forwardUpdateInfo
+ _endpoint_handleAudioStreamResumed
+ _endpoint_startPowerSourceMonitorIfNeeded
+ _endpoint_stopPowerSourceMonitor
+ _endpoint_updateInactivityTimer
+ _kAPEndpointAggregateCreationOptionKey_ClusterType
+ _kAPEndpointCommandForwardToVideoPlayback_Params
+ _kAPEndpointCommandForwardToVideoPlayback_ParamsKey_Action
+ _kAPEndpointCommandForwardToVideoPlayback_ParamsVal_FadeOut
+ _kAPEndpointCoreAnalyticsDictionaryKey_IsWireless
+ _kAPEndpointDescriptionProperty_SurroundRole
+ _kAPEndpointProperty_AudioOutputLatencyMs
+ _kAPEndpointProperty_SurroundRole
+ _kAPEndpointStreamBufferedAudioEngineCreationOption_ForceFirstRemoteMediaTime
+ _kAPEndpointStreamConnectionKey_QoS
+ _kAPSDynamicLatencyManagerVariantIdentifier_B525
+ _kAPSEndpointStreamAudioHoseRegistrarRegistrationOption_SurroundRole
+ _kFigEndpointActivateOptionKey_ForcedTransportType
+ _kFigEndpointCarPlayVideoPlaybackButton_BackButton
+ _kFigEndpointCarPlayVideoPlaybackButton_HideVideoButton
+ _kFigEndpointCarPlayVideoPlaybackPlayerEvent_ButtonTapped
+ _kFigEndpointForcedTransportType_Infra
+ _kFigEndpointNotification_CarPlayVideoPlaybackPlayerEvent
+ _kFigEndpointProperty_CarPlayScreenFadeDurationInSeconds
+ _kFigEndpointSubType_HomeAccessory
+ _objc_release_x26
+ _objc_release_x27
+ _objc_retain_x8
+ _sessionfactory_RemoveAirPlaySession
+ _sessionfactory_RemoveSessionClient
- GCC_except_table127
- GCC_except_table48
- _APSEndpointStreamAudioHoseRegistrarRegisterProtocolDriverHoseLegacy
- _APSKeyHolderCreateEncryptionKeysForStream
- _APTDiagnosticMulticastDataToAllHosts
- _APTransportTrafficCaptureFlushForSysdiagnose
- _OUTLINED_FUNCTION_272
- _OUTLINED_FUNCTION_273
- _OUTLINED_FUNCTION_274
- _OUTLINED_FUNCTION_275
- _OUTLINED_FUNCTION_276
- _OUTLINED_FUNCTION_277
- _OUTLINED_FUNCTION_278
- _OUTLINED_FUNCTION_279
- _OUTLINED_FUNCTION_280
- ___block_descriptor_48_e15_v24?0r^v8r^v16l
- ___endpoint_prepareLocalTeardown_block_invoke
- ___endpoint_prepareLocalTeardown_block_invoke_2
- ___endpoint_prepareLocalTeardown_block_invoke_3
- ___epp_EnsureAuthorizedWithCompletionCallback_block_invoke_2
- _apsession_getNANRSSI
- _audioStream_preWarmNANDataSession
- _bufferedAudioEngine_isHoseInStereoPair
- _carManager_isDisconnectCausedBySignalInterference
- _carManager_reportBonjourFailureToCarKit
- _endpointCluster_getNumSubEndpointsActivated
- _endpoint_startInactivityTimer
- _kAPCarPlayCarServicesInterface_FailureInfoConnectionPhase_Discovery
- _kAPCarPlayCarServicesInterface_FailureInfoConnectionPhase_Running
- _kAPCarPlayCarServicesInterface_FailureInfoDiscoveryType_Bonjour
- _kAPCarPlayCarServicesInterface_FailureInfoKey_TransportType
- _kAPCarPlayCarServicesInterface_FailureInfoReason_ConnectionReset
- _kAPCarPlayCarServicesInterface_FailureInfoReason_NoBonjourRecord
- _kAPCarPlayCarServicesInterface_FailureInfoReason_NoConnectCmd
- _kAPCarPlayCarServicesInterface_FailureInfoReason_WiFiLinkUnusable
CStrings:
+ "\t[indexed] identifier: %@ infoKeys: %@\n"
+ "\t[ungrouped] identifier: %@  publicKey: %@\n"
+ "%@ms"
+ "-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]"
+ "-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]_block_invoke"
+ "-[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeer:groupID:]"
+ "-[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeersForGroup:peers:]"
+ "-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]"
+ "-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]_block_invoke"
+ "1005.13.1.2"
+ "5f07515b9cc54c47"
+ "<ProactiveNANPairing> [%{ptr}] Feature disabled from prefs"
+ "APEndpointCreateDecoratedName"
+ "APEndpointInactivityTimeoutType endpoint_determineInactivityTimeoutBehavior(FigEndpointRef, FigEndpointFeatures, CFDictionaryRef)"
+ "APPairingClientCoreUtilsPatchUnpairedPeerWithGroupID"
+ "AudioAccessory11"
+ "AudioOutputLatencyMs"
+ "BAE [%{ptr}] %s(startup) maxWaitPhaseTwoClusterBuddyMs set to %d (%lld ticks)\n"
+ "BAE [%{ptr}] %s(test) Forcing firstRemoteMediaTime to %1.6f (%lld/%d)\n"
+ "BAE [%{ptr}] %s[0x%04X] (startup) Cluster Member hose [%{ptr}] (%@) Primed -> Ready %s (clusterUUID %@)\n"
+ "BackButton"
+ "Boolean APCarPlayCarNeedsVTAlwaysActive(void)"
+ "Boolean APPairingClientCoreUtilsMigrateUngroupedPeers(void)"
+ "Eligible for fast reactivate"
+ "Failed to get all paired peers: %#m\n"
+ "Failed to get all paired peers; migration aborted\n"
+ "Failed to patch ungrouped peer %@ for migration\n"
+ "Failed to remove paired peer [%{ptr}]: %#m\n"
+ "Failed to save migrated peer %@ — migration skipped: %#m\n"
+ "Getting all paired peers\n"
+ "Got %d paired peers\n"
+ "HideVideoButton"
+ "HomeAccessory"
+ "Ignoring voice trigger since VT is actually disabled"
+ "Local HT first loss"
+ "Matched target PPID %@ for %@\n"
+ "Migrated ungrouped peer %@ to group-indexed entry\n"
+ "No group-indexed peers found; nothing to migrate\n"
+ "NoIdleTimeout activation option"
+ "OSStatus bufferedAudioEngine_createLatencyManagerEndpointOptions(FigEndpointStreamAudioEngineRef, APSAudioProtocolDriverHoseControlRef, APSSurroundRole, CFDictionaryRef *)"
+ "OSStatus carEndpoint_prepareFadeOutVideoPlaybackCommand(FigEndpointRef, CFDictionaryRef *)"
+ "OSStatus carEndpoint_sendVideoPlaybackParams(FigEndpointRef, CFDictionaryRef)"
+ "OSStatus carEndpoint_setupSenderSession(FigEndpointRef, APEndpointDescriptionRef, CFDictionaryRef)"
+ "OSStatus coreUtilsPairing_createAirPlayPairingSession(APPairingClientRef, PairingSessionType, Boolean, Boolean, Boolean, PairingSessionRef *)"
+ "OSStatus coreUtilsPairing_performSetupInternal(APPairingClientRef, const CFStringRef, APPairingType, Boolean, Boolean, Boolean, CFStringRef, CFStringRef *, CFDataRef *, CFDataRef *, CFTypeRef *, CFDictionaryRef *)"
+ "OSStatus endpointCluster_activateSubEndpointForcingTransportIfNeeded(FigEndpointRef, FigEndpointRef)"
+ "OSStatus epp_Dissociate(FigEndpointRef)_block_invoke"
+ "OSStatus manager_create(CFDictionaryRef, FigEndpointManagerRef *)_block_invoke"
+ "OSStatus manager_create(CFDictionaryRef, FigEndpointManagerRef *)_block_invoke_3"
+ "OSStatus manager_create(CFDictionaryRef, FigEndpointManagerRef *)_block_invoke_6"
+ "OSStatus sessionfactory_RemoveAirPlaySession(APSenderSessionFactoryRef, CFStringRef)"
+ "Override voiceTriggerMode to Voice Activity"
+ "P2POnly"
+ "P2POnlyOnBattery"
+ "Removed paired peer [%{ptr}]: %@\n"
+ "Removing paired peer [%{ptr}]: %@\n"
+ "Scheduling kFigEndpointManagerNotification_AvailableEndpointsChanged in %lld ns with %llu ns leeway\n"
+ "SnoopCollectionPath"
+ "SurroundRole"
+ "Ungrouped peer migration %s\n"
+ "Ungrouped peer migration already done; skipping\n"
+ "Ungrouped peer migration started\n"
+ "[%{ptr}] %@ is%s recommended%?{end} with err=%#m"
+ "[%{ptr}] Activation callback %@ for [%{ptr}]"
+ "[%{ptr}] Authorization request callback %@ for [%{ptr}] result %#m"
+ "[%{ptr}] Bonjour events monitoring: sending Bonjour info to CarKit: %@"
+ "[%{ptr}] COLLISION %@ clusterPlus [%{ptr}] subEndpointPlus [%{ptr}] has inner [%{ptr}] but found real [%{ptr}]"
+ "[%{ptr}] COLLISION %@ plus [%{ptr}] has inner [%{ptr}] but found real [%{ptr}]"
+ "[%{ptr}] Checking if need to report failure for disconnect reason: %d"
+ "[%{ptr}] Completion callback %@ for [%{ptr}]"
+ "[%{ptr}] Dissociating inner [%{ptr}]"
+ "[%{ptr}] Duplicate activate in stage %d; keeping current activation\n"
+ "[%{ptr}] Ensure Authorized with inner [%{ptr}] proxyID %@"
+ "[%{ptr}] Fail delay timer already running, discarding requested delay of %llu ms for subEndpoint [%{ptr}]%?{end}, failure count %ld"
+ "[%{ptr}] Failed to remove session for deviceID %@: %#m\n"
+ "[%{ptr}] Forcing %@ transport for activating subEndpoint [%{ptr}]"
+ "[%{ptr}] Ignoring subEndpoint [%{ptr}] failure, cluster is deactivated"
+ "[%{ptr}] Immediately triggering lost cluster buddy reconnect logic for [%{ptr}] (session state: %s, reason: %s)"
+ "[%{ptr}] Inactivity timeout type: %s%?{end} (%s)\n"
+ "[%{ptr}] Monitoring power source for inactivity timer\n"
+ "[%{ptr}] NAN RSSI sample failed: %#m\n"
+ "[%{ptr}] Power source changed: now on %s power\n"
+ "[%{ptr}] Power source monitor creation fail"
+ "[%{ptr}] RA Reconcile: Migrating subEndpoint [%{ptr}] from NAN to Infra"
+ "[%{ptr}] RA Reconcile: Reactivate subEndpoint [%{ptr}] error: %m"
+ "[%{ptr}] RA Reconcile: all subEndpoints already using %@"
+ "[%{ptr}] Removing orphaned pairing group peer [%{ptr}] with identifier %@\n"
+ "[%{ptr}] Removing session client for %@ endpoint [%{ptr}] due to failure in upgrade session path.\n"
+ "[%{ptr}] Removing session for %@ due to failure in new session path.\n"
+ "[%{ptr}] Send Command callback %@ for [%{ptr}] forward? %s"
+ "[%{ptr}] Set up %@ stream and useRealtimeAPAT=%s (localDeviceType=%d receiverSupportsRealtimeAPAT=%s isScreenMirroringUsage=%s engineType=%@"
+ "[%{ptr}] Snoop collection path pattern requested, responding with %@ (err: %#m)\n"
+ "[%{ptr}] Starting fail delay timer for seed %llu, subEndpoint [%{ptr}], with delay of %llu ms%?{end}, failure count %ld"
+ "[%{ptr}] Stopped monitoring power source\n"
+ "[%{ptr}] SubEndpointStream(%{ptr}) is dissociated, excluding it from aggregate capabilities"
+ "[%{ptr}] Using inactivity timeout? %s%?{end} (type: %s)\n"
+ "[%{ptr}] audio output latency: %@ms\n"
+ "[%{ptr}] carEndpoint_prepareFadeOutVideoPlayback videoPlayback not in session"
+ "[%{ptr}] carEndpoint_prepareFadeOutVideoPlayback videoPlayback not supported"
+ "[%{ptr}] carEndpoint_prepareFadeOutVideoPlayback: %@"
+ "[%{ptr}] sending %@: %@ to HU"
+ "[%{ptr}] unrecognized button %@"
+ "action"
+ "aggregateClusterType"
+ "battery"
+ "because peer was primed or better"
+ "bufferedAudioEngine_isHoseClusterBuddy"
+ "c2cf40f3e8894bef"
+ "carEndpoint_activateInternal_block_invoke_4"
+ "carEndpoint_handleVideoPlayerBackButtonEvent"
+ "carEndpoint_prepareFadeOutVideoPlaybackCommand"
+ "carEndpoint_sendVideoPlaybackParams"
+ "carManager_reportBonjourEventToCarKit"
+ "com.apple.airplay.demo"
+ "com.apple.airplay.pairing-migration"
+ "com.apple.private.restrict-post.AirPlay.DACP.mutetoggle"
+ "com.apple.private.restrict-post.AirPlay.DACP.volumedown"
+ "com.apple.private.restrict-post.AirPlay.DACP.volumeup"
+ "due to timeout"
+ "endpointCluster_copyActivatedSubEndpointsByTransportType"
+ "endpointCluster_copyActivationOptionsForcingTransportType"
+ "endpointCluster_reconcileResponsiveAudioTransports"
+ "endpointCluster_reconcileResponsiveAudioTransports_block_invoke"
+ "endpoint_forwardUpdateInfo"
+ "fadeOut"
+ "forceFirstRemoteMediaTime"
+ "forwardToVideoPlayback"
+ "group info member count: %lu\n"
+ "group-indexed peers: %lu\n"
+ "manager_create_block_invoke_6"
+ "maxWaitPhaseTwoClusterBuddyMs"
+ "no platform-specific policy"
+ "origin"
+ "senderClusterType"
+ "senderOSVersion"
+ "sessionfactory_RemoveAirPlaySession"
+ "setVideoPlaybackParameters"
+ "streamConnectionKeyQoS"
+ "ungrouped peers to migrate: %lu\n"
+ "ungroupedPeersMigrationDone"
+ "v32@?0@\"NSString\"8@\"NSArray\"16^B24"
+ "videoPlaybackFadeOut"
+ "void bufferedAudioEngine_updateHosesPrimed(FigEndpointStreamAudioEngineRef, uint64_t, uint64_t, Boolean, APAudioEngineBufferedPrimingStats *)"
+ "void carManager_collectAnalyticsIfNeeded(FigEndpointManagerRef, FigEndpointRef, FigEndpointRef, int32_t, APCarPlayFailureInfoReason, CarManagerSessionResetMitigations)"
+ "void carManager_reportBonjourEventToCarKit(FigEndpointManagerRef, Boolean, APCarPlayFailureInfoReason)"
+ "void coreUtilsPairing_updatePairingGroupInfoIfNeeded(APPairingClientRef, CFDictionaryRef, CUPairedPeer *)_block_invoke_2"
+ "void endpointAggregate_handleAudioStreamResumed(CMNotificationCenterRef, const void *, CFStringRef, const void *, CFTypeRef)"
+ "void endpointCluster_CallActivationCompletionCallback(FigEndpointRef, uint64_t, FigEndpointFeatures, OSStatus, FigEndpointActivationCompletionCallback, void *)"
+ "void endpointCluster_reconcileResponsiveAudioTransports(FigEndpointRef, CFDictionaryRef *)"
+ "void endpointCluster_reconcileResponsiveAudioTransports(FigEndpointRef, CFDictionaryRef *)_block_invoke"
+ "void endpointCluster_startFailDelayTimerIfNeeded(FigEndpointRef, FigEndpointRef)"
+ "void endpoint_handleAudioStreamResumed(CMNotificationCenterRef, const void *, CFStringRef, const void *, CFTypeRef)"
+ "void endpoint_handlePowerSourceChanged(FigEndpointRef)"
+ "void endpoint_performRemoteTeardown(void *)_block_invoke"
+ "void endpoint_startPowerSourceMonitorIfNeeded(FigEndpointRef)"
+ "void endpoint_stopPowerSourceMonitor(FigEndpointRef)"
+ "void endpoint_updateInactivityTimer(FigEndpointRef, Boolean)"
+ "wall"
- "980.77.1.2"
- "APCarPlay_transportType"
- "BAE [%{ptr}] %s[0x%04X] (startup) Stereo Pair Hoses [%{ptr}] (%@) Primed -> Ready due to timeout\n"
- "BAE [%{ptr}] %s[0x%04X] (startup) Stereo Pair hose (peer) [%{ptr}] (%@) Primed -> Ready because peer was primed or better\n"
- "BAE [%{ptr}] %s[0x%04X] (startup) Stereo Pair hose [%{ptr}] (%@) Primed -> Ready because peer was primed or better\n"
- "OSStatus bufferedAudioEngine_createLatencyManagerEndpointOptions(FigEndpointStreamAudioEngineRef, APSAudioProtocolDriverHoseControlRef, CFDictionaryRef *)"
- "OSStatus carEndpoint_setupSenderSession(FigEndpointRef, APEndpointDescriptionRef)"
- "OSStatus coreUtilsPairing_createAirPlayPairingSession(APPairingClientRef, PairingSessionType, Boolean, Boolean, PairingSessionRef *)"
- "OSStatus coreUtilsPairing_performSetupInternal(APPairingClientRef, const CFStringRef, APPairingType, Boolean, Boolean, CFStringRef, CFStringRef *, CFDataRef *, CFDataRef *, CFTypeRef *, CFDictionaryRef *)"
- "OSStatus manager_create(CFDictionaryRef, FigEndpointManagerRef *)_block_invoke_2"
- "OSStatus manager_create(CFDictionaryRef, FigEndpointManagerRef *)_block_invoke_4"
- "Scheduling kFigEndpointManagerNotification_AvailableEndpointsChanged in %lld ns\n"
- "Terminus_MeshRegistration"
- "WiFiLinkUnusable"
- "[%{ptr}] %@ is%s recommended?{end} with err=%#m"
- "[%{ptr}] Activate SubEndpoint [%{ptr}] on reconcile transports failed %m"
- "[%{ptr}] Activation callback with inner [%{ptr}] context %@ forward? %s"
- "[%{ptr}] Authorization request completion callback for inner %s [%{ptr}] result %#m"
- "[%{ptr}] Bonjour events monitoring: sending Bonjour failure info to CarKit: %@"
- "[%{ptr}] Checking if need to report failure for disconnect reason: %@"
- "[%{ptr}] Completion callback with inner [%{ptr}] context %@ forward? %s"
- "[%{ptr}] Dissociating"
- "[%{ptr}] Ensure Authorized with inner [%{ptr}] context %@"
- "[%{ptr}] Immediately triggering lost cluster buddy reconnect logic for [%{ptr}] during startup\n"
- "[%{ptr}] RA stereo pair transport mismatch detected, [%{ptr}] on %@, [%{ptr}] on %@, forcing [%{ptr}] to Infra"
- "[%{ptr}] RA stereo pair, no transport mismatch [%{ptr}] on %@, [%{ptr}] on %@"
- "[%{ptr}] Send Command callback with inner [%{ptr}] context %@ forward? %s"
- "[%{ptr}] Set up %@ stream and useRealtimeAPAT=%s (localDeviceType=%d receiverSupportsRealtimeAPAT=%s isScreenMirroringUsage=%s"
- "[%{ptr}] Starting fail delay timer for seed %llu with delay of %llu seconds.\n"
- "[%{ptr}] Using inactivity timeout? %d\n"
- "bonjour"
- "bufferedAudioEngine_isHoseInStereoPair"
- "carEndpoint_activateInternal_block_invoke_3"
- "carManager_reportBonjourFailureToCarKit"
- "com.apple.AirTunes.DACP.mutetoggle"
- "com.apple.AirTunes.DACP.volumedown"
- "com.apple.AirTunes.DACP.volumeup"
- "connectionReset"
- "discovery"
- "endpointCluster_reconcileSubEndpointTransportsIfNeeded"
- "manager_create_block_invoke_5"
- "noBonjourRecord"
- "noConnectCmd"
- "running"
- "void bufferedAudioEngine_updateHosesPrimed(FigEndpointStreamAudioEngineRef, uint64_t, Boolean, APAudioEngineBufferedPrimingStats *)"
- "void carManager_collectAnalyticsIfNeeded(FigEndpointManagerRef, FigEndpointRef, FigEndpointRef, int32_t, CFStringRef, CarManagerSessionResetMitigations)"
- "void carManager_reportBonjourFailureToCarKit(FigEndpointManagerRef, CFStringRef, CFStringRef)"
- "void endpointCluster_reconcileSubEndpointTransportsIfNeeded(FigEndpointRef, FigEndpointRef)"
- "void endpointCluster_startFailDelayTimerIfNeeded(FigEndpointRef)"
- "void endpoint_prepareLocalTeardown(APEndpointDeactivationContext *)_block_invoke"
- "void endpoint_startInactivityTimer(FigEndpointRef)"
```
