## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

```diff

-2235.63.1.2.0
-  __TEXT.__text: 0x7e0224
-  __TEXT.__objc_methlist: 0x3ac00
+2260.15.1.0.0
+  __TEXT.__text: 0x7e6df4
+  __TEXT.__objc_methlist: 0x3ad90
   __TEXT.__const: 0xc690
-  __TEXT.__cstring: 0x9f9f5
-  __TEXT.__oslogstring: 0x141d50
-  __TEXT.__gcc_except_tab: 0x2d04
+  __TEXT.__cstring: 0x9fe77
+  __TEXT.__oslogstring: 0x144e55
+  __TEXT.__gcc_except_tab: 0x2ddc
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x12608
+  __TEXT.__unwind_info: 0x12678
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x77e0
-  __DATA_CONST.__objc_classlist: 0x14b8
+  __DATA_CONST.__const: 0x77f8
+  __DATA_CONST.__objc_classlist: 0x14b0
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x510
+  __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18d98
+  __DATA_CONST.__objc_selrefs: 0x18ed0
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x1268
+  __DATA_CONST.__objc_superrefs: 0x1260
   __DATA_CONST.__objc_arraydata: 0x27d8
-  __DATA_CONST.__got: 0x1e40
-  __AUTH_CONST.__const: 0x4608
-  __AUTH_CONST.__cfstring: 0x29d00
-  __AUTH_CONST.__objc_const: 0x6d128
+  __DATA_CONST.__got: 0x1de0
+  __AUTH_CONST.__const: 0x4588
+  __AUTH_CONST.__cfstring: 0x29e80
+  __AUTH_CONST.__objc_const: 0x6d3b8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x52f8
   __AUTH_CONST.__objc_arrayobj: 0x1d88
+  __AUTH_CONST.__objc_doubleobj: 0x210
   __AUTH_CONST.__objc_floatobj: 0x30
-  __AUTH_CONST.__objc_doubleobj: 0x200
   __AUTH_CONST.__objc_dictobj: 0x2d0
-  __AUTH_CONST.__auth_got: 0x2c38
-  __AUTH.__data: 0xf8
-  __DATA.__objc_ivar: 0x7714
-  __DATA.__data: 0x7d48
-  __DATA.__bss: 0x950
+  __AUTH_CONST.__auth_got: 0x2c68
+  __DATA.__objc_ivar: 0x777c
+  __DATA.__data: 0x1c10
+  __DATA.__bss: 0xf10
   __DATA.__common: 0x55
-  __DATA_DIRTY.__objc_data: 0xcf30
-  __DATA_DIRTY.__data: 0x420
-  __DATA_DIRTY.__bss: 0xae0
+  __DATA_DIRTY.__objc_data: 0xcee0
+  __DATA_DIRTY.__data: 0x6570
+  __DATA_DIRTY.__bss: 0x4c0
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35502
-  Symbols:   42024
-  CStrings:  34072
+  Functions: 35560
+  Symbols:   42090
+  CStrings:  34195
 
Symbols:
+ +[VCAVFoundationCapture isZoomSupportedForCaptureDevice:captureSource:]
+ +[VCAudioToolboxAudioComponentMock activeInstanceCount]
+ +[VCAudioToolboxAudioComponentMock isMockingSessionActive]
+ +[VCHardwareSettings supportsClientPreviewPresentationOrientation]
+ +[VCMediaNegotiationBlobV2StreamGroup(Utils) homeKitCameraDefaultsForStreamGroupCamera:]
+ -[AVCPreviewCameraSession setPreviewPresentationOrientation:]
+ -[AVConferencePreview setPreviewPresentationOrientation:]
+ -[CannedEncodedVideoCapture reset]
+ -[CannedRawVideoCapture reset]
+ -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:]
+ -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:aspectRatio:]
+ -[VCAVFoundationCapture clearPreviewPresentationOrientation]
+ -[VCAVFoundationCapture clearRemotePresentationOrientation]
+ -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture isClientPreviewPresentationOrientationGoverning]
+ -[VCAVFoundationCapture secondaryCameraRequestSizeForAspectRatio:]
+ -[VCAVFoundationCapture setPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]
+ -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]
+ -[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]
+ -[VCAudioSessionAVAS dispatchedIsInputAvailable]
+ -[VCAudioStream reportingAudioJBRampStats]
+ -[VCAudioStreamSendGroupConfig enableSyncGroupReferenceTimestamp]
+ -[VCAudioStreamSendGroupConfig setEnableSyncGroupReferenceTimestamp:]
+ -[VCAudioToolboxAudioComponentMock autorelease]
+ -[VCAudioToolboxAudioComponentMock release]
+ -[VCAudioToolboxAudioComponentMock retainCount]
+ -[VCAudioToolboxAudioComponentMock retain]
+ -[VCAudioTransmitterConfig setShouldCapBitrateForWatchRelay:]
+ -[VCAudioTransmitterConfig shouldCapBitrateForWatchRelay]
+ -[VCCallSession isRemoteWatchRelayDeviceWithDeviceType:]
+ -[VCConnectionHealthMonitor resetStallDetectionStateAfterMonitoringResumed]
+ -[VCCoreAudio_AudioUnitMock autorelease]
+ -[VCCoreAudio_AudioUnitMock beginSession]
+ -[VCCoreAudio_AudioUnitMock endSession]
+ -[VCCoreAudio_AudioUnitMock isMockingEnabled]
+ -[VCCoreAudio_AudioUnitMock release]
+ -[VCCoreAudio_AudioUnitMock retainCount]
+ -[VCCoreAudio_AudioUnitMock retain]
+ -[VCMediaRecorder hasConfiguredWriter]
+ -[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]
+ -[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]
+ -[VCMockQRServer forwardOnePacketFromListenerSocket:listenerSourceIP:listenerSourcePort:forwarderSocketList:listenerParticipantID:]
+ -[VCMockQRServer stopPacketForwarders]
+ -[VCRTPHistory dealloc]
+ -[VCRemoteVideoState participantId]
+ -[VCRemoteVideoState setParticipantId:]
+ -[VCSession clearRemotePresentationOrientationOnCaptureServer]
+ -[VCSessionPowerPolicy hasPrimaryCameraFrameRateMitigation]
+ -[VCSessionPowerPolicy hasSecondaryCameraFrameRateMitigation]
+ -[VCTransportSessionMultiLink handleListenerEvents:error:result:]
+ -[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]
+ -[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]
+ -[VCVideoCaptureServer clearRemotePresentationOrientation]
+ -[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]
+ -[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedIsClientPreviewPresentationOrientationGoverning]
+ -[VCVideoCaptureServer handleClientPreviewPresentationOrientationMessage:]
+ -[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]
+ -[VCVideoCaptureServer publishCameraUIDChangedForCameraUID:cameraSessionType:]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]
+ -[VCVideoStream canReuseTransportsForStreamConfigs:]
+ -[VCVideoStream expectedTransportArrayCountForStreamConfigs:]
+ -[VCVideoStream supportsMaxKeyFrameIntervalDuration]
+ -[VCVideoStream transportArrayContainsRTXTransport]
+ -[VCVideoStream transportStreamCountForStreamConfig:]
+ -[VCVideoStream willCreateRTXTransportForStreamConfig:]
+ -[VCVideoStreamSendGroupConfig enableSyncGroupReferenceTimestamp]
+ -[VCVideoStreamSendGroupConfig setEnableSyncGroupReferenceTimestamp:]
+ -[VCVideoTransmitterConfig reinitEncoderOnFrameAspectRatioChangeEnabled]
+ -[VCVideoTransmitterConfig setReinitEncoderOnFrameAspectRatioChangeEnabled:]
+ -[VCVideoTransmitterConfig setVtLoggingIdentifier:]
+ -[VCVideoTransmitterConfig vtLoggingIdentifier]
+ GCC_except_table112
+ GCC_except_table164
+ GCC_except_table169
+ GCC_except_table213
+ GCC_except_table215
+ GCC_except_table217
+ GCC_except_table235
+ GCC_except_table269
+ GCC_except_table272
+ GCC_except_table275
+ GCC_except_table314
+ GCC_except_table318
+ GCC_except_table368
+ GCC_except_table38
+ GCC_except_table452
+ _AVErrorDeviceKey
+ _CVImageBufferGetColorSpace
+ _CVPixelBufferPoolFlush
+ _OBJC_IVAR_$_AVCPacketRelaySocketConnection._isMonitoring
+ _OBJC_IVAR_$_AVConferencePreview._preRegistrationCameraUIDToSession
+ _OBJC_IVAR_$_AVConferencePreview._setPrimarySecondaryInFlightCount
+ _OBJC_IVAR_$_VCAVFoundationCapture._dualCaptureRear1440x1080
+ _OBJC_IVAR_$_VCAVFoundationCapture._hasPreviewPresentationOrientation
+ _OBJC_IVAR_$_VCAVFoundationCapture._hasVideoPresentationOrientation
+ _OBJC_IVAR_$_VCAVFoundationCapture._lastAttachPerFrameAR
+ _OBJC_IVAR_$_VCAVFoundationCapture._previewPresentationOrientation
+ _OBJC_IVAR_$_VCAudioStreamSendGroup._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCAudioStreamSendGroupConfig._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCAudioToolboxAudioComponentMock._activeInstances
+ _OBJC_IVAR_$_VCAudioToolboxAudioComponentMock._instancesLock
+ _OBJC_IVAR_$_VCAudioTransmitter._shouldCapBitrateForWatchRelay
+ _OBJC_IVAR_$_VCAudioTransmitterConfig._shouldCapBitrateForWatchRelay
+ _OBJC_IVAR_$_VCCoreAudio_AudioUnitMock._isImplicitPreferenceSession
+ _OBJC_IVAR_$_VCMockIDSDatagramChannel._enqueueLock
+ _OBJC_IVAR_$_VCMockIDSDatagramChannel._queueLock
+ _OBJC_IVAR_$_VCMockQRServer._forwarderQueue
+ _OBJC_IVAR_$_VCMockQRServer._forwarderSources
+ _OBJC_IVAR_$_VCRedundancyControlAlgorithmVideo._congestionKeepHistoryRatio
+ _OBJC_IVAR_$_VCRedundancyControlAlgorithmVideo._feedbackHistoryMaxLength
+ _OBJC_IVAR_$_VCRedundancyControlAlgorithmVideo._freezeStartTime
+ _OBJC_IVAR_$_VCRemoteVideoState._participantId
+ _OBJC_IVAR_$_VCSession._remoteParticipantsMapLock
+ _OBJC_IVAR_$_VCVideoCaptureServer._hasPreviewPresentationOrientationRequest
+ _OBJC_IVAR_$_VCVideoCaptureServer._hasRemotePresentationOrientation
+ _OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequest
+ _OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequestPID
+ _OBJC_IVAR_$_VCVideoCaptureServer._remotePresentationOrientation
+ _OBJC_IVAR_$_VCVideoStream._didDetectSensitiveContentFired
+ _OBJC_IVAR_$_VCVideoStream._didFlushForInterruptedFrameRun
+ _OBJC_IVAR_$_VCVideoStreamRateAdaptationFeedbackOnly._rateControlFeedbackDrained
+ _OBJC_IVAR_$_VCVideoStreamReceiver._vtLoggingIdentifier
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._hasModulatedTimestampBaseline
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._lastModulatedTimestamp
+ _OBJC_IVAR_$_VCVideoStreamSendGroupConfig._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCVideoStreamTransmitter._vtLoggingIdentifier
+ _OBJC_IVAR_$_VCVideoTransmitterConfig._reinitEncoderOnFrameAspectRatioChangeEnabled
+ _OBJC_IVAR_$_VCVideoTransmitterConfig._vtLoggingIdentifier
+ _OUTLINED_FUNCTION_82
+ _OUTLINED_FUNCTION_83
+ _VCConnectionIDS_SetLocalLinkTechnology
+ _VCImageQueue_Flush
+ _VCJitterBuffer_GetInitialRampMetrics
+ _VCMediaQueue_RecyclePacket
+ _VCMediaRecorderHistory_HasConfiguredWriter
+ _VCRedundancyControllerVideoCongestionKeepHistoryRatio
+ _VCRemoteVideoManager_FlushQueuesExceptStreamToken
+ _VCRemoteVideoManager_SetParticipantIdForStreamToken
+ _VCStringUtils_AddVTLoggingIdentifier
+ _VCStringUtils_CFStringNotEqual
+ _VCStringUtils_SetVTLoggingIdentifier
+ _VCVideoCaptureServer_ClientPIDFromArguments
+ _VCVideoStreamConfig_SetVTLoggingIdentifier
+ _VTCompressionSessionCreateWithOptions
+ __OBJC_$_INSTANCE_VARIABLES_VCAudioToolboxAudioComponentMock
+ __VCMediaQueue_DrainPendingRecyclePackets
+ __VideoPacketBuffer_SetNeedRefresh
+ ___135-[VCMockQRServer startPacketForwarderWithListenerSocket:listenerSourceIP:listenerSourcePort:forwarderSocketList:listenerParticipantID:]_block_invoke
+ ___38-[VCAudioSessionAVAS isInputAvailable]_block_invoke
+ ___38-[VCAudioSessionAVAS isInputSupported]_block_invoke
+ ___38-[VCMockQRServer stopPacketForwarders]_block_invoke
+ ___44-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke
+ ___57-[AVConferencePreview setPreviewPresentationOrientation:]_block_invoke
+ ___58-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke
+ ___60-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke
+ ___61-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke
+ ___62-[VCVideoStreamRateAdaptationFeedbackOnly startFeedbackSource]_block_invoke_2
+ ___66+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke
+ ___76-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke
+ ___77-[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]_block_invoke
+ ___78-[VCVideoCaptureServer publishCameraUIDChangedForCameraUID:cameraSessionType:]_block_invoke
+ ___78-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]_block_invoke
+ ___80-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke
+ ___86-[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:aspectRatio:]_block_invoke
+ ___VCMediaRecorderHistory_HasConfiguredWriter_block_invoke
+ ___VCRemoteVideoManager_FlushQueuesExceptStreamToken_block_invoke
+ ___VCRemoteVideoManager_SetParticipantIdForStreamToken_block_invoke
+ ___block_descriptor_40_e8_32o_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12ls32l8
+ ___block_descriptor_61_e8_32o40o48o_e5_v8?0ls32l8s40l8s48l8
+ _kForwarderQueueSpecificKey
+ _kVCXPCConnectionTimeoutQueueSpecificKey
+ _kVTCompressionSessionOption_LoggingIdentifier
+ _kVTDecompressionSessionOption_LoggingIdentifier
+ _nw_error_get_error_domain
+ _objc_getAssociatedObject
+ _objc_setAssociatedObject
+ _supportsClientPreviewPresentationOrientation.onceToken
+ _supportsClientPreviewPresentationOrientation.resolved
+ _xpc_copy_description
- +[VCHardwareSettings supportsSquarePreviewCapture]
- -[AVCCaptionsClient initWithDelegate:translatorIdentifier:]
- -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:]
- -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:aspectRatio:]
- -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]
- -[VCAVFoundationCapture squarePreviewAdjustedRequestSizeForCaptureSize:]
- -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]
- -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]
- -[VCAudioCaptionsSpeechTranslator addToCaptionTasksWithError:]
- -[VCAudioCaptionsSpeechTranslator client:didReceiveTranscriptionResult:]
- -[VCAudioCaptionsSpeechTranslator client:didReceiveTranslationResult:]
- -[VCAudioCaptionsSpeechTranslator client:didStopTranslationWithError:]
- -[VCAudioCaptionsSpeechTranslator dealloc]
- -[VCAudioCaptionsSpeechTranslator destroyCaptions]
- -[VCAudioCaptionsSpeechTranslator finishCaptions]
- -[VCAudioCaptionsSpeechTranslator initWithDelegate:isLocal:taskIdentifier:reportingAgent:]
- -[VCAudioCaptionsSpeechTranslator initWithSpeechConfig:]
- -[VCAudioCaptionsSpeechTranslator packageAndSendTranscribedString:withTask:]
- -[VCAudioCaptionsSpeechTranslator packageAndSendTranslatedString:withTask:]
- -[VCAudioCaptionsSpeechTranslator pushSamples:numSamples:hostTime:]
- -[VCAudioCaptionsSpeechTranslator serverDidDisconnectForClient:]
- -[VCAudioCaptionsSpeechTranslator setUpCaptionsWithError:]
- -[VCAudioCaptionsSpeechTranslator setupTranslatorSharedWithError:]
- -[VCAudioCaptionsSpeechTranslator setupTranslatorStandaloneWithError:]
- -[VCAudioCaptionsSpeechTranslator shouldPushSamples]
- -[VCAudioCaptionsSpeechTranslator startCaptionsWithError:]
- -[VCAudioCaptionsSpeechTranslator stopCaptions]
- -[VCAudioCaptionsSpeechTranslator translationDidStartForClient:]
- -[VCAudioManager anyClientNeedsMicInputWithPreferredClient:]
- -[VCAudioManager updateMicAttributionForClient:shouldAdd:]
- -[VCAudioToolboxAudioComponentMock dealloc]
- -[VCCoreAudio_AudioUnitMock dealloc]
- -[VCTransportSessionMultiLink handleListenerEvents:error:]
- -[VCVideoCaptureServer copyLocalScreenAttributesForVideoAttributes:]
- -[VCVideoStreamReceiver gatherInterframeDelayStats:]
- GCC_except_table111
- GCC_except_table168
- GCC_except_table198
- GCC_except_table200
- GCC_except_table220
- GCC_except_table245
- GCC_except_table254
- GCC_except_table257
- GCC_except_table300
- GCC_except_table313
- GCC_except_table36
- GCC_except_table367
- GCC_except_table451
- _OBJC_CLASS_$_VCAudioCaptionsSpeechTranslator
- _OBJC_IVAR_$_VCAVFoundationCapture._clientRequestedSize
- _OBJC_IVAR_$_VCAVFoundationCapture._configuringForCapture
- _OBJC_IVAR_$_VCAVFoundationCapture._squarePreviewOverrideActive
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._currentSourceUpdateNumber
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._currentTranslatedUpdateNumber
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._isStarted
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._transcriptionTimes
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorClient
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorConfiguration
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorStartDuration
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorStartTime
- _OBJC_IVAR_$_VCAudioManager._hasActiveMicClients
- _OBJC_IVAR_$_VCPowerManager._forceDisableThermal
- _OBJC_IVAR_$_VCVideoStreamReceiver._interframeDelayMonitor
- _OBJC_METACLASS_$_VCAudioCaptionsSpeechTranslator
- _VCAudioUnit_BasebandInstance
- _VCAudioUnit_DefaultOutputInstance
- _VCAudioUnit_RemoteIOInstance
- _VCAudioUnit_SystemAudioInstance
- _VCAudioUnit_VoiceProcessorInstance
- _VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer
- _VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer.flag
- _VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer.onceToken
- _VCFeatureFlagManager_HostSpeechTranslationServer
- _VCFeatureFlagManager_HostSpeechTranslationServer.audioFlag
- _VCFeatureFlagManager_HostSpeechTranslationServer.onceToken
- _VCFeatureFlagManager_HostSpeechTranslationServer.videoFlag
- _VCSpeechTranslation_STSpeechTranslatorClientClass
- _VCSpeechTranslation_STSpeechTranslatorClientClass.onceToken
- _VCSpeechTranslation_STSpeechTranslatorClientClass.speechTranslatorClientClass
- _VCSpeechTranslation_STSpeechTranslatorConfigurationClass
- _VCSpeechTranslation_STSpeechTranslatorConfigurationClass.onceToken
- _VCSpeechTranslation_STSpeechTranslatorConfigurationClass.speechTranslatorConfigurationClass
- _VCSpeechTranslation_StartServer
- _VCVirtualAVCaptureDevice_OnMediaSample
- __OBJC_$_INSTANCE_METHODS_VCAudioCaptionsSpeechTranslator
- __OBJC_$_INSTANCE_VARIABLES_VCAudioCaptionsSpeechTranslator
- __OBJC_$_PROP_LIST_VCAudioCaptionsSpeechTranslator
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_STSpeechTranslatorClientDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_STSpeechTranslatorClientDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_STSpeechTranslatorClientDelegate
- __OBJC_$_PROTOCOL_REFS_STSpeechTranslatorClientDelegate
- __OBJC_CLASS_PROTOCOLS_$_VCAudioCaptionsSpeechTranslator
- __OBJC_CLASS_RO_$_VCAudioCaptionsSpeechTranslator
- __OBJC_LABEL_PROTOCOL_$_STSpeechTranslatorClientDelegate
- __OBJC_METACLASS_RO_$_VCAudioCaptionsSpeechTranslator
- __OBJC_PROTOCOL_$_STSpeechTranslatorClientDelegate
- __VCSpeechTranslation_LibraryHandle
- __VCSpeechTranslation_LibraryHandle.onceToken
- __VCVideoStreamSendGroup_SecondaryCameraTransfer
- ___30-[VCSession participantForID:]_block_invoke
- ___39-[VCMockQRServer startPacketForwarders]_block_invoke
- ___50+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke
- ___70-[VCAudioCaptionsSpeechTranslator client:didReceiveTranslationResult:]_block_invoke
- ___70-[VCAudioCaptionsSpeechTranslator setupTranslatorStandaloneWithError:]_block_invoke
- ___72-[VCAudioCaptionsSpeechTranslator client:didReceiveTranscriptionResult:]_block_invoke
- ___73-[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:aspectRatio:]_block_invoke
- ___78-[VCVideoCaptureServer dispatchedSetCaptureCameraWithToken:cameraSessionType:]_block_invoke_2
- ___VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer_block_invoke
- ___VCFeatureFlagManager_HostSpeechTranslationServer_block_invoke
- ___VCSpeechTranslation_STSpeechTranslatorClientClass_block_invoke
- ___VCSpeechTranslation_STSpeechTranslatorConfigurationClass_block_invoke
- ____VCSpeechTranslation_LibraryHandle_block_invoke
- ___block_descriptor_40_e8_32o_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12ls32l8
- __audioComponentMockLock
- __audioUnitMockLock
- __weakAudioComponentMockInstance
- __weakAudioUnitMockInstance
- _objc_loadWeakRetained
- _supportsSquarePreviewCapture.onceToken
- _supportsSquarePreviewCapture.resolved
CStrings:
+ " [%s] %s:%d %@(%p) Applying mute property for audioSessionId=%d, isMuted=%d"
+ " [%s] %s:%d %@(%p) Capturing first modulatedTimestamp=%u baseline, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d %@(%p) Failed to allocate forwarder sources"
+ " [%s] %s:%d %@(%p) Failed to allocate inter frame delay monitor"
+ " [%s] %s:%d %@(%p) Failed to allocate socket list"
+ " [%s] %s:%d %@(%p) Failed to allocate the active instances set"
+ " [%s] %s:%d %@(%p) Failed to create forwarder queue"
+ " [%s] %s:%d %@(%p) Failed to create read source for socket=%d (participant=%@)"
+ " [%s] %s:%d %@(%p) Failed to create sockets from configuration"
+ " [%s] %s:%d %@(%p) Failed to extract RTP information from video packet for participant=%@"
+ " [%s] %s:%d %@(%p) Failed to find datagram channel for participant=%@, skipping packet"
+ " [%s] %s:%d %@(%p) Failed to forward packet to=%@:%d (participant=%@), errno=%d"
+ " [%s] %s:%d %@(%p) Failed to init the instances lock"
+ " [%s] %s:%d %@(%p) Failed to retain participant configuration"
+ " [%s] %s:%d %@(%p) Found matching datagram channel for participant=%@"
+ " [%s] %s:%d %@(%p) Found send key material for _latestSendKeyIndex=%@, returning MKI=%@, sendKeysCount=%d"
+ " [%s] %s:%d %@(%p) Keeping transactionID=%llu, already ahead of IDS baseline initialTransactionID=%llu"
+ " [%s] %s:%d %@(%p) NACK generated for SSRC=0x%X, NACK packet size=%zubytes, listener participant=%@"
+ " [%s] %s:%d %@(%p) NWConnection reported state=%d, errorDomain=%d, errorCode=%d"
+ " [%s] %s:%d %@(%p) No cached send key material for _latestSendKeyIndex=%@, sendKeysCount=%d"
+ " [%s] %s:%d %@(%p) No streamIDs found in packet, forwarding to all participants, new received bytes=%d, listened from=%@, participants who have to receive this packet are=%@"
+ " [%s] %s:%d %@(%p) Packet too short: receivedBytes=%d < headerSize=%d, dropping"
+ " [%s] %s:%d %@(%p) Participant=%@ has no entries in the subscription table"
+ " [%s] %s:%d %@(%p) Participant=%@ has no subscription matching packet stream IDs"
+ " [%s] %s:%d %@(%p) ProcessedBuffer: hasStreams=%d, streamIDCount=%d, streamIDs=%@"
+ " [%s] %s:%d %@(%p) ProcessedBuffer: participants who have to receive this packet are=%@"
+ " [%s] %s:%d %@(%p) Skipping the participant VCAudioIO start. isHomeKitVideo=%d"
+ " [%s] %s:%d %@(%p) Skipping, a writer is already composed for"
+ " [%s] %s:%d %@(%p) Tracing number of bytes: receievedBytes=%d"
+ " [%s] %s:%d %@(%p) Tracing packet across the network, Mock QR Server received  RTP datagram size=%d, SSRC=0x%X, SeqNum=%u"
+ " [%s] %s:%d %@(%p) Trying to get the mockDatagramChannel, tempParticipantID value=%@"
+ " [%s] %s:%d %@(%p) Video frame is too old and modulated timestamp rolled backward – dropping frame. lastModulatedTimestamp=%u, modulatedTimestamp=%u, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d %@(%p) [FTDC] No desired secondary capture formats: no video device format matches width=%d, height=%d, aspectRatio=%d among %lu multicam candidates of %lu total"
+ " [%s] %s:%d %@(%p) [FTDC] No exact %dx%d rear format (picker chose %dx%d); falling back to %dx%d"
+ " [%s] %s:%d %@(%p) [FTDC] Primary connections video=%d metadata=%d"
+ " [%s] %s:%d %@(%p) [FTDC] _videoCaptureSource=%d, _dualCaptureEnabled=%d, _dualCaptureReceiverEnabled=%d, _oneToOneModeEnabled=%d"
+ " [%s] %s:%d %@(%p) [FTDC] ignoring secondary aspectRatio=%d on the disable path"
+ " [%s] %s:%d %@(%p) [FTDC] ignoring secondary disable: dual capture already off"
+ " [%s] %s:%d %@(%p) [FTDC] primaryUID=%@, secondaryUID=%@, hasSecondary=%d, aspectRatio=%d, dualCaptureEnabled=%d"
+ " [%s] %s:%d %@(%p) error zero sampleBufferSize requested, maxSamplesPerFrame=%u, mBytesPerFrame=%u, audioPayloadsCount=%lu"
+ " [%s] %s:%d %@(%p) nw connection reported state=%d, errorDomain=%d, errorCode=%d"
+ " [%s] %s:%d %@(%p) recv failed: receivedBytes=%d, errno=%d, socket=%d"
+ " [%s] %s:%d %@(%p) setMicrophoneMuted:%d"
+ " [%s] %s:%d %@(%p) streamGroupID=%s, shouldSync=%d, hksvHasVideoStreamInput=%d"
+ " [%s] %s:%d %@(%p) width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d, hasVideoPresentationOrientation=%d, previewPresentationOrientation=%d, hasPreviewPresentationOrientation=%d"
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/VCRemoteVideoManager.m:%d: VCRemoteVideoManager: null object was passed to FlushQueuesExceptStreamToken"
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/VCRemoteVideoManager.m:%d: VCRemoteVideoManager: null object was passed to SetParticipantIdForStreamToken"
+ " [%s] %s:%d Applying mute property for audioSessionId=%d, isMuted=%d"
+ " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info with header bitmap 0x%x, expecting %zu"
+ " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info, expecting %zu"
+ " [%s] %s:%d Capturing first modulatedTimestamp=%u baseline, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d Failed [super init]"
+ " [%s] %s:%d Failed to allocate _enqueueLock"
+ " [%s] %s:%d Failed to allocate _queueLock"
+ " [%s] %s:%d Failed to allocate forwarder sources"
+ " [%s] %s:%d Failed to allocate inter frame delay monitor"
+ " [%s] %s:%d Failed to allocate socket list"
+ " [%s] %s:%d Failed to allocate the active instances set"
+ " [%s] %s:%d Failed to compose loggingIdentifier for streamToken=%ld"
+ " [%s] %s:%d Failed to create compressionSessionOptions"
+ " [%s] %s:%d Failed to create forwarder queue"
+ " [%s] %s:%d Failed to create read source for socket=%d (participant=%@)"
+ " [%s] %s:%d Failed to create sockets from configuration"
+ " [%s] %s:%d Failed to init the instances lock"
+ " [%s] %s:%d Failed to register stream group=%s for capture source ID=%d"
+ " [%s] %s:%d Failed to retain participant configuration"
+ " [%s] %s:%d Found send key material for _latestSendKeyIndex=%@, returning MKI=%@, sendKeysCount=%d"
+ " [%s] %s:%d Ignoring transitional linkTechnology=%u"
+ " [%s] %s:%d Invalid parameter: dictionary=%p key=%p identifier=%p"
+ " [%s] %s:%d Invalid parameter: identifier passed as NULL"
+ " [%s] %s:%d Invalid parameter: identifier=%p value=%p"
+ " [%s] %s:%d Keeping transactionID=%llu, already ahead of IDS baseline initialTransactionID=%llu"
+ " [%s] %s:%d NWConnection reported state=%d, errorDomain=%d, errorCode=%d"
+ " [%s] %s:%d No cached send key material for _latestSendKeyIndex=%@, sendKeysCount=%d"
+ " [%s] %s:%d No participantId recorded for streamToken=%ld, skipping flush"
+ " [%s] %s:%d Not enough buffer for ECN CE count"
+ " [%s] %s:%d Not enough buffer for ECN ECT1 count"
+ " [%s] %s:%d Not enough buffer for bandwidth estimation"
+ " [%s] %s:%d Not enough buffer for video burst loss"
+ " [%s] %s:%d Packet too short: receivedBytes=%d < headerSize=%d, dropping"
+ " [%s] %s:%d Redundancy unfrozen reason=%d isNetworkCongested=%d _offChannelTimeRatio=%2.3f freezeDuration=%2.3f keptHistory=%d"
+ " [%s] %s:%d SRTP verification failed (%X), consecutiveSRTPAuthFailures=%u, ssrc=%X"
+ " [%s] %s:%d SignalEncoder[%p] MSCEncoderSessionInit failed with error=%d"
+ " [%s] %s:%d Skipping the participant VCAudioIO start. isHomeKitVideo=%d"
+ " [%s] %s:%d Skipping, a writer is already composed for"
+ " [%s] %s:%d Timed out draining rate control feedback, source=%p"
+ " [%s] %s:%d Transport streams cleared, rtpTransportStream=%p, rtcpTransportStream=%p"
+ " [%s] %s:%d VCDTMFToneGenerator[%p] Initialize event=%d, powerLevel=%d, sampleRate=%d, tableAmplitude=%d, amplitude=%d"
+ " [%s] %s:%d VCHardwareSettings: clientPreviewPresentationOrientation support overridden by user default: outOfBox=%d override=%d"
+ " [%s] %s:%d VTCompressionSessionCreateWithOptions failed (%d)"
+ " [%s] %s:%d Video frame is too old and modulated timestamp rolled backward – dropping frame. lastModulatedTimestamp=%u, modulatedTimestamp=%u, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d [%p] Adding %@=%@ to the codec session's dictionary"
+ " [%s] %s:%d [%p] Failed to create loggingIdentifier from vtLoggingIdentifier=%s"
+ " [%s] %s:%d [%p] InitialRamp Metrics: numPackets=%u numAudioPackets=%u hasSufficientAudio=%d numOOOPackets=%u maxOOODisplacementMs=%u avgOOODisplacementMs=%u"
+ " [%s] %s:%d [%p] InitialRamp OOO sn=%u prevSn=%u tsDelta=%u dispMs=%u numOOO=%u maxDispMs=%u"
+ " [%s] %s:%d [%p] InitialRamp START firstTs=%u windowEndTs=%u sampleRate=%u"
+ " [%s] %s:%d [%p] InitialRamp WINDOW CLOSED numPackets=%u numAudioPackets=%u numOOO=%u maxDispMs=%u sumDispMs=%.0f"
+ " [%s] %s:%d [%p] VideoTransmitter_CreateHandle wMTU[%d] bIsIPv6[%d] reinitOnFrameChangeEnabled[%s] reinitOnARChangeEnabled[%s]"
+ " [%s] %s:%d [AR_TX] captureAspectRatio=%@, composeLandscapeOrderedRatio=%d, clientPreviewGoverns=%d, _videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, _previewPresentationOrientation=%d, _hasPreviewPresentationOrientation=%d, _orientation=%d, _deviceOrientationMatchesReceiver=%d, _remotePreferFullBleed=%d, overrideByDefault=%d"
+ " [%s] %s:%d [AR_TX] client preview presentation orientation not honored, the active format cannot vend it. aspectRatio=%@, _previewPresentationOrientation=%d, _orientation=%d"
+ " [%s] %s:%d [AR_TX]_videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, orientation=%d, _deviceOrientationMatchesReceiver=%d"
+ " [%s] %s:%d [FTDC] No desired secondary capture formats: no video device format matches width=%d, height=%d, aspectRatio=%d among %lu multicam candidates of %lu total"
+ " [%s] %s:%d [FTDC] No exact %dx%d rear format (picker chose %dx%d); falling back to %dx%d"
+ " [%s] %s:%d [FTDC] Primary connections video=%d metadata=%d"
+ " [%s] %s:%d [FTDC] _dualCaptureSupported=%d, useVirtualCapture=%d"
+ " [%s] %s:%d [FTDC] _videoCaptureSource=%d, _dualCaptureEnabled=%d, _dualCaptureReceiverEnabled=%d, _oneToOneModeEnabled=%d"
+ " [%s] %s:%d [FTDC] ignoring secondary aspectRatio=%d on the disable path"
+ " [%s] %s:%d [FTDC] ignoring secondary disable: dual capture already off"
+ " [%s] %s:%d [FTDC] primaryUID=%@, secondaryUID=%@, hasSecondary=%d, aspectRatio=%d, dualCaptureEnabled=%d"
+ " [%s] %s:%d [FTDC][PFAR] path=afterCapture, attach=%d, dualCaptureEnabled=%d, dualCaptureReceiverEnabled=%d, shouldAttachPerFrameAR=%d, frontCamera=%d, bufferWidth=%zu, bufferHeight=%zu"
+ " [%s] %s:%d [FTDC][PFAR] path=duringProcessEffect, attach=%d, dualCaptureEnabled=%d, dualCaptureReceiverEnabled=%d, shouldAttachPerFrameAR=%d, frontCamera=%d, bufferWidth=%zu, bufferHeight=%zu"
+ " [%s] %s:%d [HKSV3] came mediaSubtype='%s' did not match camera default, retried against HomeKit camera default. isValid=%d"
+ " [%s] %s:%d _previewPresentationOrientation=%d, _hasPreviewPresentationOrientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d _previewPresentationOrientation=%d, didChange=%d, _orientation=%d, _videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d beginSession: %lu audio unit mock instance(s) carried over from a previous session"
+ " [%s] %s:%d beginSession: %lu component mock instance(s) leaked from a previous session (never disposed)"
+ " [%s] %s:%d centerStageRectOfInterest rejected, centerStageEnabled=0, reason=%@"
+ " [%s] %s:%d configureWithBuffer failed with error %08X for control info=%p, dropping it"
+ " [%s] %s:%d error zero sampleBufferSize requested, maxSamplesPerFrame=%u, mBytesPerFrame=%u, audioPayloadsCount=%lu"
+ " [%s] %s:%d eventInfo has IDSDataChannelError, code = %u, ERROR = %@"
+ " [%s] %s:%d feedbackHistoryMaxLength=%2.3f congestionKeepHistoryRatio=%2.3f keepHistoryThreshold=%2.3f"
+ " [%s] %s:%d linkTechnology=%u"
+ " [%s] %s:%d loggingIdentifier=%s is %zu chars, over the %d VideoToolbox stores"
+ " [%s] %s:%d nw connection reported state=%d, errorDomain=%d, errorCode=%d"
+ " [%s] %s:%d recv failed: receivedBytes=%d, errno=%d, socket=%d"
+ " [%s] %s:%d recvmsg failed for socket=%d, errno=%d"
+ " [%s] %s:%d sampleOffset exceeds source sampleCount: sampleOffset=%u, source.sampleCount=%u"
+ " [%s] %s:%d self=%p, _mode=%d, _type=%d, algorithm=%s"
+ " [%s] %s:%d self=%p, redundancyPercentage=%u, previousRedundancyPercentage=%u, packetLossPercentageInput=%3.3f, _packetLossPercentage=%u, burstPacketLoss=%u, redundancyPercentageBasedOnPLR=%u, redundancyPercentageBasedOnBurstyLoss=%u"
+ " [%s] %s:%d setMicrophoneMuted:%d"
+ " [%s] %s:%d streamGroupID=%s is not an enumerated AVCStreamGroupID"
+ " [%s] %s:%d streamGroupID=%s streamInputID=%@ captureSourceID=%d"
+ " [%s] %s:%d streamGroupID=%s, shouldSync=%d, hksvHasVideoStreamInput=%d"
+ " [%s] %s:%d videoDecoder=%p decoded frame colorimetry changed to ColorPrimaries=%@ TransferFunction=%@ YCbCrMatrix=%@ for streamID=%d width=%d height=%d"
+ " [%s] %s:%d videoDecoder=%p decoded frame has no CGColorSpace attachment for streamID=%d width=%d height=%d"
+ " [%s] %s:%d wasClientGoverning=%d, _orientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d, hasVideoPresentationOrientation=%d, previewPresentationOrientation=%d, hasPreviewPresentationOrientation=%d"
+ "+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke"
+ "-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke"
+ "-[AVConferencePreview setPreviewPresentationOrientation:]"
+ "-[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:aspectRatio:]_block_invoke"
+ "-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke"
+ "-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke"
+ "-[VCAVFoundationCapture encodeProcessedPixelBuffer:time:imageData:processTime:]_block_invoke"
+ "-[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]"
+ "-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke"
+ "-[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]"
+ "-[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]"
+ "-[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]"
+ "-[VCAudioSessionAVAS isInputSupported]_block_invoke"
+ "-[VCAudioToolboxAudioComponentMock init]"
+ "-[VCConnectionManagerIDS updateLocalLinkTechnology:]"
+ "-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke"
+ "-[VCCoreAudio_AudioUnitMock beginSession]"
+ "-[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]"
+ "-[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]"
+ "-[VCMockQRServer forwardOnePacketFromListenerSocket:listenerSourceIP:listenerSourcePort:forwarderSocketList:listenerParticipantID:]"
+ "-[VCMockQRServer initMockQRServer]"
+ "-[VCSessionParticipantLocal captureEncodingSize]"
+ "-[VCSessionParticipantLocal enableDualCaptureReceiver:]_block_invoke"
+ "-[VCTransportSessionMultiLink handleListenerEvents:error:result:]"
+ "-[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]"
+ "-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke"
+ "-[VCVideoCaptureServer clearRemotePresentationOrientation]"
+ "-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke"
+ "-[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]"
+ "-[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]"
+ "-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]"
+ "-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke"
+ "-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_6"
+ "-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]"
+ "2260.15.1"
+ "<%s:%p> Token (%d) Link (%d): %s <-> %s (%s, %s), priority %d, uplink bitrate cap (%u), downlink bitrate cap (%u), uplink audio only bitrate cap = (%u), uplink OneToOne bitrate cap = (%u), isLocalConstrained (%d), isRemoteConstrained (%d), isLocalExpensive (%d) isRemoteExpensive (%d) isLocalDelegated (%d) isRemoteDelegated (%d) isLocalUltraConstrained (%d) isRemoteUltraConstrained (%d) isVirtualRelayLink (%d) reportingIPVersion(%d) TransportLayerEncryption=%d relayProtocolStackDescrption(%@) channelDataBaseProtocolStackDescription(%@) _isHopByHopEncryptionSupported=%d localLinkTransport=%u localLinkTechnology=%u"
+ "AVC-CD/%ld"
+ "AVC-CE/%ld"
+ "AVC-SD/%ld"
+ "AVC-SE/%ld"
+ "AVCPreviewCameraSession [%s] %s:%d %@(%p) cameraUID=%@ orientation=%d"
+ "AVCPreviewCameraSession [%s] %s:%d cameraUID=%@ orientation=%d"
+ "AVCRC [%s] %s:%d [%p] ReportNetworkStatistics shouldReport=%d rttMs=%u arrivalTime=%f plr=%f plrAudio=%f plrVideo=%f (lastPlr=%f lastPlrAudio=%f lastPlrVideo=%f) burstPacketLoss=%u (lastBurst=%u) owrd=%u (lastOwrd=%u) isNetworkCongested=%d (lastCongested=%d) unconditional=%d"
+ "AVConferencePreview [%s] %s:%d %@(%p) orientation=%d"
+ "AVConferencePreview [%s] %s:%d orientation=%d"
+ "AVConferenceXPCServer [%s] %s:%d VCXPCServer: incoming request from PID=%d has no API key, event=%s"
+ "AVConferenceXPCServer: incoming request from PID=%d missing \"API\" key, event=%s"
+ "JBInitialRampAvgOOOTimeDisplacementMs"
+ "JBInitialRampHasSufficientAudioPackets"
+ "JBInitialRampMaxOOOTimeDisplacementMs"
+ "JBInitialRampNumAudioPackets"
+ "JBInitialRampNumOOOPackets"
+ "JBInitialRampNumPackets"
+ "Primary camera UID is required"
+ "SoundDec_Destroy"
+ "VCAudioReceiver [%s] %s:%d One or more input param(s) are NULL: audioReceiver=%p streamId=%p"
+ "VCAudioReceiver [%s] %s:%d VCAudioReceiver[%p] Could not allocate memory for Audio Frame"
+ "VCAudioStream [%s] %s:%d %@(%p) Reconfiguring VCAudioStream: transportCount=%lu->%lu localSSRC=%u->%u"
+ "VCAudioStream [%s] %s:%d Reconfiguring VCAudioStream: transportCount=%lu->%lu localSSRC=%u->%u"
+ "VCJitterBuffer_GetInitialRampMetrics"
+ "VCMediaQueue [%s] %s:%d Failed to recycle pending packet for mediaQueueStreamId=%u, status=%d"
+ "VCMediaRecorderHistory_HasConfiguredWriter"
+ "VCMediaStream [%s] %s:%d %@(%p) Last RTCP packet receive time:%f now:%f rtcpTimeoutEnabledTime=%f rtcpTimeoutInterval=%f. Triggering RTCP timeout"
+ "VCMediaStream [%s] %s:%d Last RTCP packet receive time:%f now:%f rtcpTimeoutEnabledTime=%f rtcpTimeoutInterval=%f. Triggering RTCP timeout"
+ "VCRC [%s] %s:%d Set feedback controlInfo [%p]: echoedSendTimestamp=%u bandwidthEstimation=%u videoBurstLoss=%u audioBurstLoss=%u videoReceivedPkts=%u audioReceivedPkts=%u totalReceivedKBytes=%u receiveQueueTarget=%u ecnECT1Count=%u ecnCECount=%u connectionStatsBlob=%u"
+ "VCRateControlSetFeedbackControlInfo"
+ "VCRemoteVideoManager_FlushQueuesExceptStreamToken"
+ "VCRemoteVideoManager_SetParticipantIdForStreamToken"
+ "VCSoundDec [%s] %s:%d [%p] AudioConverterDispose failed, status=%d audioConv=%p"
+ "VCStringUtils_AddVTLoggingIdentifier"
+ "VCStringUtils_SetVTLoggingIdentifier"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Discarding client preview presentation orientation request, unsupported by the hardware rule. previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Invalid previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Missing or non-numeric previewPresentationOrientation, class=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) No local video attributes to derive recording screen attributes from"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Notifying client=%p of class=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Retaining the remote presentation orientation at call end, unsupported by the hardware rule."
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Retaining the request, the dying client did not make it. diedClientPID=%d, _previewPresentationOrientationRequestPID=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] videoOrientation=%d, screenOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d, _previewPresentationOrientationRequestPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _remotePresentationOrientation=%d, _hasRemotePresentationOrientation=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) previewPresentationOrientation=%d, requestingClientPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d Discarding client preview presentation orientation request, unsupported by the hardware rule. previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d Invalid previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d Missing or non-numeric previewPresentationOrientation, class=%@"
+ "VCVideoCaptureServer [%s] %s:%d No local video attributes to derive recording screen attributes from"
+ "VCVideoCaptureServer [%s] %s:%d Notifying client=%p of class=%@"
+ "VCVideoCaptureServer [%s] %s:%d Retaining the remote presentation orientation at call end, unsupported by the hardware rule."
+ "VCVideoCaptureServer [%s] %s:%d Retaining the request, the dying client did not make it. diedClientPID=%d, _previewPresentationOrientationRequestPID=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d [AR_RX] videoOrientation=%d, screenOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d, _previewPresentationOrientationRequestPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d _remotePresentationOrientation=%d, _hasRemotePresentationOrientation=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d ignoring stale capture failure, failingCameraUID=%@, currentCameraUID=%@"
+ "VCVideoCaptureServer [%s] %s:%d previewPresentationOrientation=%d, requestingClientPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d requested secondary aspectRatio=%d not applied: _avCapture=%p lacks batchSetCameraUIDsPrimary:secondary:hasSecondary:aspectRatio:"
+ "VCVideoPlayer [%s] %s:%d VCVideoPlayer[%p] playbackClient[%p] Skipping avsync offset reporting. firstFramePresented=%d hostTimeForPlayout=%f externalSourcePlayoutTimeInSeconds=%f lastFrame.videoFrameTimeInSeconds=%f"
+ "VCVideoPlayer [%s] %s:%d VCVideoPlayer[%p] pthread_cond_timedwait_relative_np unexpected error=%d"
+ "VCVideoStream [%s] %s:%d %@(%p) Rebuilding transports for reconfigure. currentCount=%u expectedCount=%u localSSRCChanged=%d canReuse=%d"
+ "VCVideoStream [%s] %s:%d Rebuilding transports for reconfigure. currentCount=%u expectedCount=%u localSSRCChanged=%d canReuse=%d"
+ "VCVideoStream [%s] %s:%d VCVideoStream[%p] sensitive content interrupted frame, flushing other queues, streamToken=%ld"
+ "VCVideoStreamConfig_SetVTLoggingIdentifier"
+ "VideoPacketBuffer [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/Others/VideoPacketBuffer.c:%d: VideoPacketBuffer[%p] Reusing cached plaintext for re-assembled frame timestamp=%u frameSequenceNumber=%d isLate=%d"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Frame pool allocation failed, dropping packet seq=%d"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Packet pool allocation failed, dropping packet seq=%d"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Successfully assembled previously incomplete late frame timestamp=%u frameSequenceNumber=%u isFrameSequenceNumberValid=%d isRefreshFrame=%d hasRetransmittedPackets=%d"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] [recovery] Frame not submitted TS=%u seq=%u frameSequenceNumber=%d isFrameSequenceNumberValid=%d isRefreshFrame=%d isLTRPFrame=%d isIntraFrame=%d iLTRBits=0x%x hasRetransmittedPackets=%d isLate=%d keyFrameRequestReason=%s futureFramesSize=%u incompleteFramesSize=%u videoPacketsExpected=%u videoPacketsReceived=%u parityPacketsReceived=%u actualfecLevel=%.1f newestPreGapPacketAgeMs=%.1f"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] [recovery] Freeing frame TS=%u frameSequenceNumber=%d isFrameSequenceNumberValid=%d isLate=%d fScheduled=%d isFailedCompleteFrame=%d isLTRPFrame=%d isIntraFrame=%d hasRetransmittedPackets=%d fRecovered=%d frameFECStatus=%d"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] fNeedRefresh 0->1 reason=%s setTimeSec=%.3f isDecoderOutOfSync=%d"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] fNeedRefresh 1->0 (refresh satisfied) pendingReason=%s pendingForMs=%.1f"
+ "_AVCRateController_ReportNetworkStatistics"
+ "_VCJitterBuffer_CheckAndCloseRampMeasurement"
+ "_VCJitterBuffer_InitRampInfo"
+ "_VCJitterBuffer_MeasureRampOOO"
+ "_VCMediaQueue_DrainPendingRecyclePackets"
+ "_VCRemoteVideoManager_DispatchedFlushQueuesExceptStreamToken"
+ "_VideoDecoder_LogColorimetryAttachmentsChanged"
+ "_VideoPacketBuffer_SetNeedRefresh"
+ "_VideoPlayer_UpdateReportedAVSyncOffset"
+ "com.apple.AVConference.mockqrserver.forwarder"
+ "disableJitterBufferDump"
+ "disableVideoJitterBufferDump"
+ "dualCaptureRear1440x1080"
+ "forceClientPreviewPresentationOrientation"
+ "i28@?0^{tagVCMediaPacket=iS^{OpaqueCMBlockBuffer}{tagVCIDSChannelDataFormat=[12S]CBSCBBQBBBS{?=SSSSS}BBBQBSBBBB}{tagVCIDSChannelDataFormat=[12S]CBSCBBQBBBS{?=SSSSS}BBBQBSBBBB}i^v^?^{tagHANDLE}ddBBBBIIIIISIIIiIddBBBBBBBBBBiAB^{tagVCMediaPacket}}8S16S20s24"
+ "lcid"
+ "previewPresentationOrientation"
+ "previewSetPresentationOrientation"
+ "rcid"
+ "redundancyCongestionKeepHistoryRatio"
+ "secondary camera UID must differ from the primary camera UID"
+ "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12"
+ "vc-redundancy-controller-video-congestion-keep-history-ratio"
- " [%s] %s:%d %@ not available, falling back to basic initializer."
- " [%s] %s:%d %@(%p) %@ not available, falling back to basic initializer."
- " [%s] %s:%d %@(%p) Applying mute property for audioSessionId=%d, isMuted=%d (sessionMute=%@ _isMicrophoneMuted=%d hasActiveMicClients=%d)"
- " [%s] %s:%d %@(%p) Cannot find _latestSendKeyIndex '%@' in receive keys array of %d elements. Invalidating it..."
- " [%s] %s:%d %@(%p) Failed as Nil transcriptionProviderIdentifier passed to initialize SpeechTranslator"
- " [%s] %s:%d %@(%p) Failed to allocate delay monitor"
- " [%s] %s:%d %@(%p) Failed to create the _translatorClient for shared SpeechTranslator"
- " [%s] %s:%d %@(%p) Failed to create the _translatorClient for standalone SpeechTranslator"
- " [%s] %s:%d %@(%p) Failed to create the _translatorConfiguration for SpeechTranslator"
- " [%s] %s:%d %@(%p) Failed to create the converter. Captions will not be available with SpeechTranslator."
- " [%s] %s:%d %@(%p) Fatal error in STSpeechTranslator usage with caption operating mode not set for translator. Unexpected captionsOperatingMode=%@"
- " [%s] %s:%d %@(%p) Found _latestSendKeyIndex '%@' in send keys array of %d elements"
- " [%s] %s:%d %@(%p) Get error %@ from NWConnection with state: %d!"
- " [%s] %s:%d %@(%p) The server disconnected for the STSpeechTranslatorClient=%@"
- " [%s] %s:%d %@(%p) Translation started for STSpeechTranslatorClient=%@"
- " [%s] %s:%d %@(%p) Translation stopped for STSpeechTranslatorClient=%@ with error=%@"
- " [%s] %s:%d %@(%p) VCAudioCaptionsSpeechTranslator-init FAILED"
- " [%s] %s:%d %@(%p) [FTDC] primaryUID=%@, secondaryUID=%@, aspectRatio=%d, dualCaptureEnabled=%d"
- " [%s] %s:%d %@(%p) _transcriptionTimes is nil"
- " [%s] %s:%d %@(%p) error zero sampleBufferSize requested"
- " [%s] %s:%d %@(%p) no streams available"
- " [%s] %s:%d %@(%p) reportAndReset returned nil"
- " [%s] %s:%d %@(%p) setMicrophoneMuted=%d"
- " [%s] %s:%d %@(%p) skipping IFD stats: monitor=%p, param=%p"
- " [%s] %s:%d %@(%p) stopped a timer=%p that was already stop"
- " [%s] %s:%d %@(%p) width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d"
- " [%s] %s:%d @:@ VCAudioCaptionsSpeechTranslator-init Finished instance=%p Succeeded with frameworkType=%d"
- " [%s] %s:%d @:@ VCAudioCaptionsSpeechTranslator-init instance=%p"
- " [%s] %s:%d Applying mute property for audioSessionId=%d, isMuted=%d (sessionMute=%@ _isMicrophoneMuted=%d hasActiveMicClients=%d)"
- " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info, expecting %u"
- " [%s] %s:%d Cannot find _latestSendKeyIndex '%@' in receive keys array of %d elements. Invalidating it..."
- " [%s] %s:%d Failed as Nil transcriptionProviderIdentifier passed to initialize SpeechTranslator"
- " [%s] %s:%d Failed to allocate delay monitor"
- " [%s] %s:%d Failed to create the _translatorClient for shared SpeechTranslator"
- " [%s] %s:%d Failed to create the _translatorClient for standalone SpeechTranslator"
- " [%s] %s:%d Failed to create the _translatorConfiguration for SpeechTranslator"
- " [%s] %s:%d Failed to create the converter. Captions will not be available with SpeechTranslator."
- " [%s] %s:%d Failed to register stream group for capture source ID=%d"
- " [%s] %s:%d Failed to softlink VCSpeechTranslation framework and could not copy over error=%s, path=%s"
- " [%s] %s:%d Failed to softlink VCSpeechTranslation framework and could not find any error, path=%s"
- " [%s] %s:%d Failed to softlink VCSpeechTranslation framework with error=%s path=%s"
- " [%s] %s:%d Failed to start SpeechTranslation server with error=%@"
- " [%s] %s:%d Failed to start translator client. SpeechTranslator error=%@"
- " [%s] %s:%d Fatal error in STSpeechTranslator usage with caption operating mode not set for translator. Unexpected captionsOperatingMode=%@"
- " [%s] %s:%d Found _latestSendKeyIndex '%@' in send keys array of %d elements"
- " [%s] %s:%d Get error %@ from NWConnection with state: %d!"
- " [%s] %s:%d Get error %@ from nw connection with state: %d!"
- " [%s] %s:%d NOT hosting AudioTranscriptionAnalysis server."
- " [%s] %s:%d NOT hosting speech translation server."
- " [%s] %s:%d Redundancy unfrozen reason=%d isNetworkCongested=%d _offChannelTimeRatio=%2.3f"
- " [%s] %s:%d SRTP verification failed (%X)"
- " [%s] %s:%d SignalEncoder[%p] MSCEncoderSessionCreate failed with error=%i"
- " [%s] %s:%d Started SpeechTranslation server"
- " [%s] %s:%d The server disconnected for the STSpeechTranslatorClient=%@"
- " [%s] %s:%d Translation started for STSpeechTranslatorClient=%@"
- " [%s] %s:%d Translation stopped for STSpeechTranslatorClient=%@ with error=%@"
- " [%s] %s:%d Unexpected streamGroupID=%s"
- " [%s] %s:%d VCAudioCaptionsSpeechTranslator-init FAILED"
- " [%s] %s:%d VCDTMFToneGenerator[%p] Initialize event=%d, powerLevel=%d, sampleRate=%d"
- " [%s] %s:%d VCHardwareSettings: squarePreviewCapture support overridden by user default: outOfBox=%d override=%d"
- " [%s] %s:%d VTCompressionSessionCreate failed (%d)"
- " [%s] %s:%d Waiting for packet on socket=%d..."
- " [%s] %s:%d [%p] VideoTransmitter_CreateHandle wMTU[%d] bIsIPv6[%d] reinitEnabled[%s]"
- " [%s] %s:%d [AR_TX] _deviceOrientationMatchesReceiver=%d, _remotePreferFullBleed=%d, previewOnly=%d, prefersSquarePreview=%d, captureAspectRatio=%@, overrideByDefault=%d"
- " [%s] %s:%d [AR_TX]videoPresentationOrientation=%d, orientation=%d, _deviceOrientationMatchesReceiver=%d"
- " [%s] %s:%d [FTDC] _dualCaptureSupported=%d"
- " [%s] %s:%d [FTDC] primaryUID=%@, secondaryUID=%@, aspectRatio=%d, dualCaptureEnabled=%d"
- " [%s] %s:%d _transcriptionTimes is nil"
- " [%s] %s:%d error zero sampleBufferSize requested"
- " [%s] %s:%d eventInfo has IDSDataChannelError, ERROR = %@"
- " [%s] %s:%d no streams available"
- " [%s] %s:%d recvmsg failed for socket=%d"
- " [%s] %s:%d reportAndReset returned nil"
- " [%s] %s:%d setMicrophoneMuted=%d"
- " [%s] %s:%d skipping IFD stats: monitor=%p, param=%p"
- " [%s] %s:%d stopped a timer=%p that was already stop"
- " [%s] %s:%d width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d"
- "+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke"
- "-[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:aspectRatio:]_block_invoke"
- "-[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]"
- "-[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]"
- "-[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]"
- "-[VCAudioCaptionsSpeechTranslator addToCaptionTasksWithError:]"
- "-[VCAudioCaptionsSpeechTranslator client:didReceiveTranscriptionResult:]"
- "-[VCAudioCaptionsSpeechTranslator client:didReceiveTranslationResult:]"
- "-[VCAudioCaptionsSpeechTranslator client:didStopTranslationWithError:]"
- "-[VCAudioCaptionsSpeechTranslator dealloc]"
- "-[VCAudioCaptionsSpeechTranslator destroyCaptions]"
- "-[VCAudioCaptionsSpeechTranslator initWithDelegate:isLocal:taskIdentifier:reportingAgent:]"
- "-[VCAudioCaptionsSpeechTranslator packageAndSendTranscribedString:withTask:]"
- "-[VCAudioCaptionsSpeechTranslator packageAndSendTranslatedString:withTask:]"
- "-[VCAudioCaptionsSpeechTranslator pushSamples:numSamples:hostTime:]"
- "-[VCAudioCaptionsSpeechTranslator serverDidDisconnectForClient:]"
- "-[VCAudioCaptionsSpeechTranslator setUpCaptionsWithError:]"
- "-[VCAudioCaptionsSpeechTranslator setupTranslatorSharedWithError:]"
- "-[VCAudioCaptionsSpeechTranslator setupTranslatorStandaloneWithError:]"
- "-[VCAudioCaptionsSpeechTranslator setupTranslatorStandaloneWithError:]_block_invoke"
- "-[VCAudioCaptionsSpeechTranslator shouldPushSamples]"
- "-[VCAudioCaptionsSpeechTranslator startCaptionsWithError:]"
- "-[VCAudioCaptionsSpeechTranslator stopCaptions]"
- "-[VCAudioCaptionsSpeechTranslator translationDidStartForClient:]"
- "-[VCAudioSessionAVAS isInputSupported]"
- "-[VCControlChannelMultiWay lastUsedMKIBytes]"
- "-[VCDispatchTimer stop]"
- "-[VCSessionUplinkVideoStreamController anchorStreamIDWithCappedVideoStreamIDs:]"
- "-[VCTransportSessionMultiLink handleListenerEvents:error:]"
- "-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_5"
- "-[VCVideoStreamReceiver gatherInterframeDelayStats:]"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/Captions/VCAudioCaptionsSpeechTranslator.m"
- "/System/Library/PrivateFrameworks/SpeechTranslation.framework/SpeechTranslation"
- "2235.63.1.2"
- "<%s:%p> Token (%d) Link (%d): %s <-> %s (%s, %s), priority %d, uplink bitrate cap (%u), downlink bitrate cap (%u), uplink audio only bitrate cap = (%u), uplink OneToOne bitrate cap = (%u), isLocalConstrained (%d), isRemoteConstrained (%d), isLocalExpensive (%d) isRemoteExpensive (%d) isLocalDelegated (%d) isRemoteDelegated (%d) isLocalUltraConstrained (%d) isRemoteUltraConstrained (%d) isVirtualRelayLink (%d) reportingIPVersion(%d) TransportLayerEncryption=%d relayProtocolStackDescrption(%@) channelDataBaseProtocolStackDescription(%@) _isHopByHopEncryptionSupported=%d"
- "@:@ VCAudioCaptionsSpeechTranslator-init"
- "@:@ VCAudioCaptionsSpeechTranslator-init Finished"
- "AudioCallTranslation"
- "Fatal error in STSpeechTranslator usage. In SpeechTranslator module but translator operating mode is not set, captionsOperatingMode=%@"
- "HostAudioTranscriptionAnalysisServer"
- "STServerStart"
- "STSpeechTranslatorClient"
- "STSpeechTranslatorConfiguration"
- "VCAudioCaptionsSpeechTranslator.m"
- "VCAudioStream [%s] %s:%d %@(%p) Reconfiguring VCAudioStream with a different number of transports."
- "VCAudioStream [%s] %s:%d Reconfiguring VCAudioStream with a different number of transports."
- "VCFeatureFlagManager: HostAudioTranscriptionAnalysisServer=%d"
- "VCFeatureFlagManager: HostSpeechTranslationServer=%d (audioFlag=%d, videoFlag=%d)"
- "VCMediaStream [%s] %s:%d %@(%p) Last RTCP packet receive time:%f now:%f"
- "VCMediaStream [%s] %s:%d Last RTCP packet receive time:%f now:%f"
- "VCSpeechTranslation_STSpeechTranslatorClientClass"
- "VCSpeechTranslation_STSpeechTranslatorConfigurationClass"
- "VCSpeechTranslation_StartServer"
- "VCVideoCaptureServer [%s] %s:%d requested secondary aspectRatio=%d not applied: _avCapture=%p lacks batchSetCameraUIDsPrimary:secondary:aspectRatio:"
- "VCVideoStream [%s] %s:%d %@(%p) Reconfiguring VCVideoStream with a different number of transports."
- "VCVideoStream [%s] %s:%d Reconfiguring VCVideoStream with a different number of transports."
- "VideoCallTranslation"
- "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Received NULL frame"
- "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Successfully assembled previously incomplete late frame timestamp=%u frameSequenceNumber=%u isRefreshFrame=%d hasRetransmittedPackets=%d"
- "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] [recovery] Frame not submitted TS=%u seq=%u frameSequenceNumber=%d isRefreshFrame=%d isLTRPFrame=%d isIntraFrame=%d iLTRBits=0x%x hasRetransmittedPackets=%d isLate=%d keyFrameRequestReason=%s futureFramesSize=%u incompleteFramesSize=%u"
- "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] [recovery] Freeing frame TS=%u frameSequenceNumber=%d isLate=%d fScheduled=%d isFailedCompleteFrame=%d isLTRPFrame=%d isIntraFrame=%d hasRetransmittedPackets=%d"
- "_VCSpeechTranslation_LibraryHandle"
- "_VCSpeechTranslation_LibraryHandle_block_invoke"
- "enableInterframeDelay"
- "forceSquarePreviewCapture"
- "hostAudioTranscriptionAnalysisServer"
- "hostSpeechTranslationServer"
- "i28@?0^{tagVCMediaPacket=iS^{OpaqueCMBlockBuffer}{tagVCIDSChannelDataFormat=[12S]CBSCBBQBBBS{?=SSSSS}BBBQBSBBBB}{tagVCIDSChannelDataFormat=[12S]CBSCBBQBBBS{?=SSSSS}BBBQBSBBBB}i^v^?^{tagHANDLE}ddBBBBIIIIISIIIiIddBBBBBBBBBBi^{tagVCMediaPacket}}8S16S20s24"
- "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12"
```
