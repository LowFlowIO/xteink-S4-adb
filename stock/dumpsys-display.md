DISPLAY MANAGER (dumpsys display)
  mOnlyCode=false
  mSafeMode=false
  mPendingTraversal=false
  mGlobalDisplayState=ON
  mNextNonDefaultDisplayId=1
  mViewports=[DisplayViewport{type=INTERNAL, valid=true, isActive=true, displayId=0, uniqueId='local:0', physicalPort=0, orientation=0, logicalFrame=Rect(0, 0 - 480, 800), physicalFrame=Rect(0, 0 - 480, 800), deviceWidth=480, deviceHeight=800}]
  mDefaultDisplayDefaultColorMode=0
  mSingleDisplayDemoMode=false
  mWifiDisplayScanRequestCount=0
  mStableDisplaySize=Point(480, 800)
  mMinimumBrightnessCurve=[(0.0, 0.0), (2000.0, 50.0), (4000.0, 90.0)]

Display Adapters: size=3
  LocalDisplayAdapter
  VirtualDisplayAdapter
  OverlayDisplayAdapter
    mCurrentOverlaySetting=
    mOverlays: size=0

Display Devices: size=1

  DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 480 x 800, modeId 1, defaultModeId 1, supportedModes [{id=1, width=480, height=800, fps=78.00001}], colorMode 0, supportedColorModes [0], HdrCapabilities HdrCapabilities{mSupportedHdrTypes=[], mMaxLuminance=500.0, mMaxAverageLuminance=500.0, mMinLuminance=0.0}, allmSupported false, gameContentTypeSupported false, density 219, 79.686 x 239.058 dpi, appVsyncOff 2000000, presDeadline 12820512, touch INTERNAL, rotation 0, type INTERNAL, address {port=0}, deviceProductInfo null, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
    mAdapter=LocalDisplayAdapter
    mUniqueId=local:0
    mDisplayToken=android.os.BinderProxy@205897b
    mCurrentLayerStack=0
    mCurrentOrientation=0
    mCurrentLayerStackRect=Rect(0, 0 - 480, 800)
    mCurrentDisplayRect=Rect(0, 0 - 480, 800)
    mCurrentSurface=null
    mPhysicalDisplayId=0
    mDisplayModeSpecs={baseModeId=1 primaryRefreshRateRange=[0 Infinity] appRequestRefreshRateRange=[0 Infinity]}
    mDisplayModeSpecsInvalid=false
    mActiveConfigId=0
    mActiveModeId=1
    mActiveColorMode=0
    mDefaultModeId=1
    mState=ON
    mBrightnessState=0.3503937
    mBacklight=com.android.server.lights.LightsService$LightImpl@c613398
    mAllmSupported=false
    mAllmRequested=false
    mGameContentTypeSupported=false
    mGameContentTypeRequested=false
    mDisplayInfo=DisplayInfo{isInternal=true, density=1.36875, secure=true, deviceProductInfo=null}
    mDisplayConfigs=
      DisplayConfig{width=480, height=800, xDpi=79.686, yDpi=239.058, refreshRate=78.00001, appVsyncOffsetNanos=2000000, presentationDeadlineNanos=12820512, configGroup=-1}
    mSupportedModes=
      DisplayModeRecord{mMode={id=1, width=480, height=800, fps=78.00001}}
    mSupportedColorModes=[0]
Logical Displays: size=1
  Display 0:
mDisplayId=0
    mLayerStack=0
    mHasContent=true
    mDesiredDisplayModeSpecs={baseModeId=1 primaryRefreshRateRange=[0 Infinity] appRequestRefreshRateRange=[0 Infinity]}
    mRequestedColorMode=0
    mDisplayOffset=(0, 0)
    mDisplayScalingDisabled=false
    mPrimaryDisplayDevice=Built-in Screen
    mBaseDisplayInfo=DisplayInfo{"Built-in Screen", displayId 0, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS, FLAG_TRUSTED, real 480 x 800, largest app 480 x 800, smallest app 480 x 800, appVsyncOff 2000000, presDeadline 12820512, mode 1, defaultMode 1, modes [{id=1, width=480, height=800, fps=78.00001}], hdrCapabilities HdrCapabilities{mSupportedHdrTypes=[], mMaxLuminance=500.0, mMaxAverageLuminance=500.0, mMinLuminance=0.0}, minimalPostProcessingSupported false, rotation 0, state ON, type INTERNAL, uniqueId "local:0", app 480 x 800, density 219 (79.686 x 239.058) dpi, layerStack 0, colorMode 0, supportedColorModes [0], address {port=0}, deviceProductInfo null, removeMode 0}
    mOverrideDisplayInfo=DisplayInfo{"Built-in Screen", displayId 0, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS, FLAG_TRUSTED, real 480 x 800, largest app 800 x 748, smallest app 480 x 428, appVsyncOff 2000000, presDeadline 12820512, mode 1, defaultMode 1, modes [{id=1, width=480, height=800, fps=78.00001}], hdrCapabilities HdrCapabilities{mSupportedHdrTypes=[], mMaxLuminance=500.0, mMaxAverageLuminance=500.0, mMinLuminance=0.0}, minimalPostProcessingSupported false, rotation 0, state OFF, type INTERNAL, uniqueId "local:0", app 480 x 800, density 219 (79.686 x 239.058) dpi, layerStack 0, colorMode 0, supportedColorModes [0], address {port=0}, deviceProductInfo null, removeMode 0}
    mRequestedMinimalPostProcessing=false

DisplayModeDirector
  mSupportedModesByDisplay:
    0 -> [{id=1, width=480, height=800, fps=78.00001}]
  mDefaultModeByDisplay:
    0 -> {id=1, width=480, height=800, fps=78.00001}
  mVotesByDisplay:
    -1:
      PRIORITY_USER_SETTING_MIN_REFRESH_RATE -> Vote{width=-1, height=-1, minRefreshRate=0.0, maxRefreshRate=Infinity}
      PRIORITY_DEFAULT_REFRESH_RATE -> Vote{width=-1, height=-1, minRefreshRate=0.0, maxRefreshRate=60.0}
  SettingsObserver
    mDefaultRefreshRate: 60.0
    mDefaultPeakRefreshRate: 0.0
  AppRequestObserver
    mAppRequestedModeByDisplay:
  BrightnessObserver
    mAmbientLux: -1.0
    mBrightness: 90
    mDefaultDisplayState: 2
    mLowPowerModeEnabled: false
    mRefreshRateChangeable: false
    mShouldObserveDisplayLowChange: false
    mShouldObserveAmbientLowChange: false
    mRefreshRateInLowZone: 0
    mShouldObserveDisplayHighChange: false
    mShouldObserveAmbientHighChange: false
    mRefreshRateInHighZone: 0
    mLastSensorData: 0.0
    mTimestamp: 1970-01-01 01:00:00.000

Callbacks: size=25
  0: mPid=389, mWifiDisplayScanRequested=false
  1: mPid=537, mWifiDisplayScanRequested=false
  2: mPid=684, mWifiDisplayScanRequested=false
  3: mPid=703, mWifiDisplayScanRequested=false
  4: mPid=723, mWifiDisplayScanRequested=false
  5: mPid=743, mWifiDisplayScanRequested=false
  6: mPid=901, mWifiDisplayScanRequested=false
  7: mPid=953, mWifiDisplayScanRequested=false
  8: mPid=978, mWifiDisplayScanRequested=false
  9: mPid=1001, mWifiDisplayScanRequested=false
  10: mPid=1019, mWifiDisplayScanRequested=false
  11: mPid=1039, mWifiDisplayScanRequested=false
  12: mPid=1060, mWifiDisplayScanRequested=false
  13: mPid=1079, mWifiDisplayScanRequested=false
  14: mPid=1144, mWifiDisplayScanRequested=false
  15: mPid=1198, mWifiDisplayScanRequested=false
  16: mPid=1206, mWifiDisplayScanRequested=false
  17: mPid=1268, mWifiDisplayScanRequested=false
  18: mPid=1288, mWifiDisplayScanRequested=false
  19: mPid=1307, mWifiDisplayScanRequested=false
  20: mPid=1328, mWifiDisplayScanRequested=false
  21: mPid=1347, mWifiDisplayScanRequested=false
  22: mPid=1383, mWifiDisplayScanRequested=false
  23: mPid=1431, mWifiDisplayScanRequested=false
  24: mPid=1454, mWifiDisplayScanRequested=false

Display Power Controller Locked State:
  mDisplayReadyLocked=true
  mPendingRequestLocked=policy=BRIGHT, useProximitySensor=false, screenBrightnessOverride=NaN, useAutoBrightness=false, screenAutoBrightnessAdjustmentOverride=NaN, screenLowPowerBrightnessFactor=1.0, blockScreenOn=false, lowPowerMode=false, boostScreenBrightness=false, dozeScreenBrightness=NaN, dozeScreenState=UNKNOWN
  mPendingRequestChangedLocked=false
  mPendingWaitForNegativeProximityLocked=false
  mPendingUpdatePowerStateLocked=false

Display Power Controller Configuration:
  mScreenBrightnessDozeConfig=0.0
  mScreenBrightnessDimConfig=0.05
  mScreenBrightnessDefault=0.39763778
  mScreenBrightnessForVrRangeMinimum=0.307087
  mScreenBrightnessForVrRangeMaximum=1.0
  mScreenBrightnessForVrDefault=0.33464
  mUseSoftwareAutoBrightnessConfig=true
  mAllowAutoBrightnessWhileDozingConfig=false
  mSkipScreenOnBrightnessRamp=false
  mColorFadeFadesConfig=false
  mColorFadeEnabled=false
  mDisplayBlanksAfterDozeConfig=false
  mBrightnessBucketsInDozeConfig=false

Display Power Controller Thread State:
  mPowerRequest=policy=BRIGHT, useProximitySensor=false, screenBrightnessOverride=NaN, useAutoBrightness=false, screenAutoBrightnessAdjustmentOverride=NaN, screenLowPowerBrightnessFactor=1.0, blockScreenOn=false, lowPowerMode=false, boostScreenBrightness=false, dozeScreenBrightness=NaN, dozeScreenState=UNKNOWN
  mUnfinishedBusiness=false
  mWaitingForNegativeProximity=false
  mProximitySensor=null
  mProximitySensorEnabled=false
  mProximityThreshold=0.0
  mProximity=Unknown
  mPendingProximity=Unknown
  mPendingProximityDebounceTime=-1 (1730789 ms ago)
  mScreenOffBecauseOfProximity=false
  mLastUserSetScreenBrightnessFloat=0.0
  mPendingScreenBrightnessSettingFloat=NaN
  mTemporaryScreenBrightnessFloat=NaN
  mAutoBrightnessAdjustment=0.0
  mBrightnessReason=manual
  mTemporaryAutoBrightnessAdjustment=NaN
  mPendingAutoBrightnessAdjustment=NaN
  mScreenBrightnessForVrFloat=0.33464
  mAppliedAutoBrightness=false
  mAppliedDimming=false
  mAppliedLowPower=false
  mAppliedScreenBrightnessOverride=false
  mAppliedTemporaryBrightness=false
  mDozing=false
  mSkipRampState=RAMP_STATE_SKIP_NONE
  mScreenOnBlockStartRealTime=3161920
  mScreenOffBlockStartRealTime=3157676
  mPendingScreenOnUnblocker=null
  mPendingScreenOffUnblocker=null
  mPendingScreenOff=false
  mReportedToPolicy=REPORTED_TO_POLICY_SCREEN_ON
  mScreenBrightnessRampAnimator.isAnimating()=false

Display Power State:
  mScreenState=ON
  mScreenBrightness=0.3503937
  mScreenReady=true
  mScreenUpdatePending=false
  mColorFadePrepared=false
  mColorFadeLevel=1.0
  mColorFadeReady=true
  mColorFadeDrawPending=false

Photonic Modulator State:
  mPendingState=ON
  mPendingBacklight=0.3503937
  mActualState=ON
  mActualBacklight=0.3503937
  mStateChangeInProgress=false
  mBacklightChangeInProgress=false

Automatic Brightness Controller Configuration:
  mScreenBrightnessRangeMinimum=0.035433073
  mScreenBrightnessRangeMaximum=1.0
  mDozeScaleFactor=1.0
  mInitialLightSensorRate=250
  mNormalLightSensorRate=250
  mLightSensorWarmUpTimeConfig=0
  mBrighteningLightDebounceConfig=4000
  mDarkeningLightDebounceConfig=8000
  mResetAmbientLuxAfterWarmUpConfig=true
  mAmbientLightHorizon=10000
  mWeightingIntercept=10000

Automatic Brightness Controller State:
  mLightSensor=null
  mLightSensorEnabled=false
  mLightSensorEnableTime=0 (1730788 ms ago)
  mCurrentLightSensorRate=-1
  mAmbientLux=0.0
  mAmbientLuxValid=false
  mAmbientBrighteningThreshold=0.0
  mAmbientDarkeningThreshold=0.0
  mScreenBrighteningThreshold=0.0
  mScreenDarkeningThreshold=0.0
  mLastObservedLux=0.0
  mLastObservedLuxTime=0 (1730789 ms ago)
  mRecentLightSamples=0
  mAmbientLightRingBuffer=[]
  mScreenAutoBrightness=NaN
  mDisplayPolicy=BRIGHT
  mShortTermModelTimeout=300000
  mShortTermModelAnchor=-1.0
  mShortTermModelValid=true
  mBrightnessAdjustmentSamplePending=false
  mBrightnessAdjustmentSampleOldLux=0.0
  mBrightnessAdjustmentSampleOldBrightness=0.0
  mForegroundAppPackageName=null
  mPendingForegroundAppPackageName=null
  mForegroundAppCategory=-1
  mPendingForegroundAppCategory=-1

SimpleMappingStrategy
  mSpline=MonotoneCubicSpline{[(0.0, 0.035433073: 0.013600573), (11.0, 0.18503937: 0.0), (41.0, 0.18503937: 0.0), (91.0, 0.2992126: 0.0019572554), (161.0, 0.41338584: 0.0016332092), (226.0, 0.51968503: 0.00146004), (321.0, 0.6417323: 8.269012E-4), (641.0, 0.7598425: 2.7989666E-4), (1281.0, 0.88188976: 1.4008814E-4), (2601.0, 1.0: 8.947746E-5)]}
  mMaxGamma=3.0
  mAutoBrightnessAdjustment=0.0
  mUserLux=-1.0
  mUserBrightness=-1.0

HysteresisLevels
  mBrighteningThresholds=[0.1]
  mDarkeningThresholds=[0.2]
  mThresholdLevels=[]
HysteresisLevels
  mBrighteningThresholds=[0.1]
  mDarkeningThresholds=[0.2]
  mThresholdLevels=[]

BrightnessTracker state:
  mStarted=false
  mLastBatteryLevel=NaN
  mLastBrightness=-1.0
  mLastSensorReadings.size=0
  mEventsDirty=false
  mEvents.size=0
  mWriteBrightnessTrackerStateScheduled=false
  mSensorRegistered=false
  mColorSamplingEnabled=false
  mNoFramesToSample=0
  mFrameRate=0.0


PersistentDataStore
  mLoaded=true
  mDirty=false
  RememberedWifiDisplays:
  DisplayStates:
  StableDeviceValues:
      StableDisplayWidth=480
      StableDisplayHeight=800
  BrightnessConfigurations:
