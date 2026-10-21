Build configuration: [sf PRESENT_TIME_OFFSET=0 FORCE_HWC_FOR_RBG_TO_YUV=0 MAX_VIRT_DISPLAY_DIM=0 RUNNING_WITHOUT_SYNC_FRAMEWORK=0 NUM_FRAMEBUFFER_SURFACE_BUFFERS=3] [libui] [libgui]

Display identification data:
Display 0 (HWC display 1): no identification data

Wide-Color information:
Device has wide color built-in display: 0
Device uses color management: 1
DisplayColorSetting: Managed
Display 0 color modes:
    ColorMode::NATIVE (0)
    Current color mode: ColorMode::NATIVE (0)

Sync configuration: [using: EGL_ANDROID_native_fence_sync EGL_KHR_wait_sync]

Scheduler:
+  Idle timer: off
+  Touch timer: off
+  Use content detection: off

ScreenOff: 0d00:03:53.946
78fps: 0d00:37:16.315

           app phase:   2000000 ns	         SF phase:   1000000 ns
     early app phase:   2000000 ns	   early SF phase:   1000000 ns
  GL early app phase:   2000000 ns	GL early SF phase:   1000000 ns
next VSYNC threshold: 9223372036854775807 ns
      present offset:         0 ns	     VSYNC period:  12820512 ns

DesiredDisplayConfigSpecs (DisplayManager): default config ID: 0, primary range: [0.00 inf], app request range: [0.00 inf]

(config override by backdoor: no)

app: state=Idle VSyncState={displayId=0, count=5024}
  pending events (count=0):
  connections (count=16):
    Connection{0xe8210a90, VSyncRequest::None}
    Connection{0xe8210f90, VSyncRequest::None}
    Connection{0xe8211030, VSyncRequest::None}
    Connection{0xe8210fe0, VSyncRequest::None}
    Connection{0xe8211170, VSyncRequest::None}
    Connection{0xe8211120, VSyncRequest::None}
    Connection{0xe8211260, VSyncRequest::None}
    Connection{0xe82129d0, VSyncRequest::None}
    Connection{0xe82130b0, VSyncRequest::None}
    Connection{0xe8213330, VSyncRequest::None}
    Connection{0xe8212110, VSyncRequest::None}
    Connection{0xe8212980, VSyncRequest::None}
    Connection{0xe8212a70, VSyncRequest::None}
    Connection{0xe8212070, VSyncRequest::None}
    Connection{0xe82113f0, VSyncRequest::None}
    Connection{0xe8211f80, VSyncRequest::None}
present fences are used
mPeriod: 12768000 ns (78.321 fps)
mPhase: -2499 ns
mError: 0 ns (sqrt=0.0)
mNumResyncSamplesSincePresent: 4 (limit 4)
mNumResyncSamples: 6 (max 32)
mResyncSamples:
  2471011298000
  2471024100000 (+12802000)
  2471036858000 (+12758000)
  2471049628000 (+12770000)
  2471062403000 (+12775000)
  2471075169000 (+12766000)
mPresentFences [8]:
  [invalid fence]
  [invalid fence]
  [invalid fence]
  [invalid fence]
  [invalid fence]
  [invalid fence]
  [invalid fence]
  2471037686014  (8375.715 ms ago)
current monotonic time: 2479413401231

Static screen stats:
  < 1 frames: 25.756 s (1.2%)
  < 2 frames: 30.303 s (1.4%)
  < 3 frames: 4.491 s (0.2%)
  < 4 frames: 0.766 s (0.0%)
  < 5 frames: 1.911 s (0.1%)
  < 6 frames: 1.014 s (0.0%)
  < 7 frames: 1.759 s (0.1%)
  7+ frames: 2125.347 s (97.0%)

Total missed frame count: 322
HWC missed frame count: 108
GPU missed frame count: 214

Buffering stats:
  [Layer name] <Active time> <Two buffer> <Double buffered> <Triple buffered>
  [com.android.settings/com.android.settings.SubSettings#0] 54.54 0.004 0.236 0.764
  [com.android.settings/com.android.settings.Settings$MyDeviceInfoActivity#0] 2.74 0.350 0.703 0.297
  [com.android.settings/com.android.settings.SubSettings#1] 1.28 0.000 0.787 0.213
  [com.android.settings/com.android.settings.Settings$SystemDashboardActivity#0] 0.98 0.149 0.719 0.281
  [android.rockchip.update.service/android.rockchip.update.service.OtaUpdateNotifyActivity#0] 0.85 0.000 0.000 1.000
  [com.android.systemui/com.android.systemui.usb.UsbDebuggingActivity#0] 0.27 0.000 0.000 1.000

Visible layers (count = 44)
GraphicBufferProducers: 5, max 4096
Composition layers
* Layer 0xe5b93800 (com.android.systemui.ImageWallpaper#0)
      isSecure=false geomUsesSourceCrop=true geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x05 (SCALE TRANSLATE )
    0.6875  0.0000  -24.0000
    0.0000  0.6875  -40.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 1280 1280] geomContentCrop=[0 0 1280 1280] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe7e9816c, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[34.909088 58.181816 733.090820 1221.818115]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=2013 appId=10099 composition type=DEVICE (2) 
      buffer: slot=1 buffer=0xe8140fa0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe6665000 (Task=1#0)
      isSecure=false geomUsesSourceCrop=false geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x00 (IDENTITY )
    1.0000  0.0000  0.0000
    0.0000  1.0000  0.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 -1 -1] geomContentCrop=[0 0 -1 -1] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe7e9456c, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 0.000000 480.000000 800.000000]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=0 appId=0 composition type=INVALID (0) 
      buffer: slot=-1 buffer=0x0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe59ce000 (Task=39#0)
      isSecure=false geomUsesSourceCrop=false geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x00 (IDENTITY )
    1.0000  0.0000  0.0000
    0.0000  1.0000  0.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 -1 -1] geomContentCrop=[0 0 -1 -1] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe58ed2ec, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 0.000000 480.000000 800.000000]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=0 appId=0 composition type=INVALID (0) 
      buffer: slot=-1 buffer=0x0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe5b91000 (com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0)
      isSecure=false geomUsesSourceCrop=true geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x00 (IDENTITY )
    1.0000  0.0000  0.0000
    0.0000  1.0000  0.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 480 800] geomContentCrop=[0 0 480 800] geomCrop=[0 0 480 800] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe7e96aec, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 0.000000 480.000000 800.000000]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=1 appId=1000 composition type=DEVICE (2) 
      buffer: slot=0 buffer=0xe8141180 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe5b7f000 (Surface(name=db128f6 InputMethod)/@0xf78c5cd - animation-leash#1)
      isSecure=false geomUsesSourceCrop=false geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x01 (TRANSLATE )
    1.0000  0.0000  0.0000
    0.0000  1.0000  800.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 -1 -1] geomContentCrop=[0 0 -1 -1] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe7e97c6c, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 -800.000000 480.000000 0.000000]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=0 appId=0 composition type=INVALID (0) 
      buffer: slot=-1 buffer=0x0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe5a44000 (Surface(name=db8a4ea StatusBar)/@0xf5a24d1 - animation-leash#0)
      isSecure=false geomUsesSourceCrop=false geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x00 (IDENTITY )
    1.0000  0.0000  0.0000
    0.0000  1.0000  0.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 -1 -1] geomContentCrop=[0 0 -1 -1] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe58ed7ec, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 0.000000 480.000000 800.000000]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=0 appId=0 composition type=INVALID (0) 
      buffer: slot=-1 buffer=0x0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe59e0800 (StatusBar#0)
      isSecure=false geomUsesSourceCrop=true geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x00 (IDENTITY )
    1.0000  0.0000  0.0000
    0.0000  1.0000  0.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 480 52] geomContentCrop=[0 0 480 52] geomCrop=[0 0 480 52] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe7e988ec, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 0.000000 480.000000 52.000000]       shadowRadius=0.000000 
      blend=PREMULTIPLIED (2) alpha=1.000000 backgroundBlurRadius=0 
      type=2000 appId=10099 composition type=DEVICE (2) 
      buffer: slot=2 buffer=0xe8143200 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=false hasProtectedContent=false isColorspaceAgnostic=true dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe5a42000 (Surface(name=df6112c NavigationBar0)/@0xb3f8b36 - animation-leash#0)
      isSecure=false geomUsesSourceCrop=false geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x01 (TRANSLATE )
    1.0000  0.0000  0.0000
    0.0000  1.0000  800.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 -1 -1] geomContentCrop=[0 0 -1 -1] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe58eda6c, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 -800.000000 480.000000 0.000000]       shadowRadius=0.000000 
      blend=NONE (1) alpha=1.000000 backgroundBlurRadius=0 
      type=0 appId=0 composition type=INVALID (0) 
      buffer: slot=-1 buffer=0x0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=true hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
* Layer 0xe59de000 (NavigationBar0#0)
      isSecure=false geomUsesSourceCrop=false geomBufferUsesDisplayInverseTransform=false geomLayerTransform 0x00000000 (ROT_0 ) 0x01 (TRANSLATE )
    1.0000  0.0000  0.0000
    0.0000  1.0000  800.0000
    0.0000  0.0000  1.0000

      geomBufferSize=[0 0 -1 -1] geomContentCrop=[0 0 -1 -1] geomCrop=[0 0 -1 -1] geomBufferTransform=0 
        Region transparentRegionHint (this=0xe7e983ec, count=1)
    [  0,   0,   0,   0]
      geomLayerBounds=[0.000000 -800.000000 480.000000 0.000000]       shadowRadius=0.000000 
      blend=PREMULTIPLIED (2) alpha=1.000000 backgroundBlurRadius=0 
      type=0 appId=0 composition type=INVALID (0) 
      buffer: slot=-1 buffer=0x0 
      sideband stream=0x0 
      color=[0.000000 0.000000 0.000000] 
      isOpaque=false hasProtectedContent=false isColorspaceAgnostic=false dataspace=UNKNOWN (0) hdr metadata types=0 colorTransform=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]
Displays (1 entries)
+ DisplayDevice{0, internal, primary, "Internal display"}
   powerMode=On (2), activeConfig=0,    Composition Display State: ["Internal display"]
   isVirtual=false hwcId=0 
   isEnabled=true isSecure=true usesClientComposition=true usesDeviceComposition=false flipClientTarget=false reusedClientComposition=false layerStack=0 layerStackInternal=true 
   transform 0x00000000 (ROT_0 ) 0x00 (IDENTITY )
    1.0000  0.0000  -0.0000
    0.0000  1.0000  -0.0000
    0.0000  0.0000  1.0000

   bounds=[0 0 480 800] frame=[0 0 480 800] viewport=[0 0 480 800] sourceClip=[0 0 480 800] destinationClip=[0 0 480 800] needsFiltering=false 
   colorMode=NATIVE (0) renderIntent=COLORIMETRIC (0) dataspace=UNKNOWN (0) colorTransformMatrix=[[1.000,0.000,0.000,0.000][0.000,1.000,0.000,0.000][0.000,0.000,1.000,0.000][0.000,0.000,0.000,1.000]]target dataspace=UNKNOWN (0) 
   Composition Display Color State:
   HWC Support: wideColorGamut=false hdr10plus=false hdr10=false hlg=false dv=false metadata=0 
   Composition RenderSurface State:
   size=[480 800] ANativeWindow=0xe6bd5c08 (format 1) flips=4855 
  FramebufferSurface: dataspace: Default(0)
   mAbandoned=0
   - BufferQueue mMaxAcquiredBufferCount=2 mMaxDequeuedBufferCount=1
     mDequeueBufferCannotBlock=0 mAsyncMode=0
     mQueueBufferCanDrop=0 mLegacyBufferDrop=1
     default-size=[480x800] default-format=1      transform-hint=00 frame-counter=305
     mTransformHintInUse=00 mAutoPrerotation=0
   FIFO(0):
   (mConsumerName=FramebufferSurface, mConnectedApi=1, mConsumerUsageBits=6656, mId=a600000000, producer=[208:???], consumer=[166:/system/bin/surfaceflinger])
   Slots:
    >[01:0xe8140b40] state=ACQUIRED 0xe7c3c300 frame=305 [ 480x 800:   0,  1]
     [00:0xe8140a00] state=FREE     0xe7c3c200 frame=303 [ 480x 800:   0,  1]
     [02:0xe8140c80] state=FREE     0xe7c3c400 frame=304 [ 480x 800:   0,  1]

   2 Layers
  - Output Layer 0xe5f12800(com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0)
        Region visibleRegion (this=0xe5f12810, count=1)
    [  0,   0, 480, 800]
        Region visibleNonTransparentRegion (this=0xe5f12864, count=1)
    [  0,   0, 480, 800]
        Region coveredRegion (this=0xe5f128b8, count=1)
    [  0,   0, 480,  52]
        Region output visibleRegion (this=0xe5f1290c, count=1)
    [  0,   0, 480, 800]
        Region shadowRegion (this=0xe5f12960, count=1)
    [  0,   0,   0,   0]
      forceClientComposition=false clearClientTarget=false displayFrame=[0 0 480 800] sourceCrop=[0.000000 0.000000 480.000000 800.000000] bufferTransform=0 (0) dataspace=UNKNOWN (0) z-index=0 
      hwc: layer=0x0824 composition=CLIENT (1) 
  - Output Layer 0xe5cffc00(StatusBar#0)
        Region visibleRegion (this=0xe5cffc10, count=1)
    [  0,   0, 480,  52]
        Region visibleNonTransparentRegion (this=0xe5cffc64, count=1)
    [  0,   0, 480,  52]
        Region coveredRegion (this=0xe5cffcb8, count=1)
    [  0,   0,   0,   0]
        Region output visibleRegion (this=0xe5cffd0c, count=1)
    [  0,   0, 480,  52]
        Region shadowRegion (this=0xe5cffd60, count=1)
    [  0,   0,   0,   0]
      forceClientComposition=false clearClientTarget=false displayFrame=[0 0 480 52] sourceCrop=[0.000000 0.000000 480.000000 52.000000] bufferTransform=0 (0) dataspace=UNKNOWN (0) z-index=1 
      hwc: layer=0x0822 composition=CLIENT (1) 

SurfaceFlinger global state:
EGL implementation : 1.4 Bifrost-"g2p0-01eac0"
EGL_ANDROID_image_native_buffer EGL_ANDROID_recordable EGL_ANDROID_native_fence_sync EGL_ANDROID_framebuffer_target EGL_ANDROID_image_crop EGL_ANDROID_blob_cache EGL_KHR_partial_update EGL_KHR_mutable_render_buffer EGL_ARM_image_format EGL_KHR_config_attribs EGL_KHR_image EGL_KHR_image_base EGL_KHR_fence_sync EGL_KHR_wait_sync EGL_KHR_gl_colorspace EGL_KHR_get_all_proc_addresses EGL_IMG_context_priority EGL_KHR_no_config_context EGL_EXT_image_dma_buf_import EGL_EXT_image_dma_buf_import_modifiers EGL_EXT_yuv_surface EGL_EXT_pixel_format_float EGL_ARM_pixmap_multisample_discard EGL_ARM_implicit_external_sync EGL_KHR_gl_texture_2D_image EGL_KHR_gl_renderbuffer_image EGL_KHR_create_context EGL_KHR_surfaceless_context EGL_KHR_gl_texture_cubemap_image EGL_EXT_image_gl_colorspace EGL_EXT_create_context_robustness
GLES: ARM, Mali-G31, OpenGL ES 3.2 v1.g2p0-01eac0.a818193b06a486891a03b96b9dd972e3
GL_EXT_debug_marker GL_ARM_rgba8 GL_ARM_mali_shader_binary GL_OES_depth24 GL_OES_depth_texture GL_OES_depth_texture_cube_map GL_OES_packed_depth_stencil GL_OES_rgb8_rgba8 GL_EXT_read_format_bgra GL_OES_compressed_paletted_texture GL_OES_compressed_ETC1_RGB8_texture GL_OES_standard_derivatives GL_OES_EGL_image GL_OES_EGL_image_external GL_OES_EGL_image_external_essl3 GL_OES_EGL_sync GL_OES_texture_npot GL_OES_vertex_half_float GL_OES_required_internalformat GL_OES_vertex_array_object GL_OES_mapbuffer GL_EXT_texture_format_BGRA8888 GL_EXT_texture_rg GL_EXT_texture_type_2_10_10_10_REV GL_OES_fbo_render_mipmap GL_OES_element_index_uint GL_EXT_shadow_samplers GL_OES_texture_compression_astc GL_KHR_texture_compression_astc_ldr GL_KHR_texture_compression_astc_hdr GL_KHR_texture_compression_astc_sliced_3d GL_EXT_texture_compression_astc_decode_mode GL_EXT_texture_compression_astc_decode_mode_rgb9e5 GL_KHR_debug GL_EXT_occlusion_query_boolean GL_EXT_disjoint_timer_query GL_EXT_blend_minmax GL_EXT_discard_framebuffer GL_OES_get_program_binary GL_OES_texture_3D GL_EXT_texture_storage GL_EXT_multisampled_render_to_texture GL_EXT_multisampled_render_to_texture2 GL_OES_surfaceless_context GL_OES_texture_stencil8 GL_EXT_shader_pixel_local_storage GL_ARM_shader_framebuffer_fetch GL_ARM_shader_framebuffer_fetch_depth_stencil GL_ARM_mali_program_binary GL_EXT_sRGB GL_EXT_sRGB_write_control GL_EXT_texture_sRGB_decode GL_EXT_texture_sRGB_R8 GL_EXT_texture_sRGB_RG8 GL_KHR_blend_equation_advanced GL_KHR_blend_equation_advanced_coherent GL_OES_texture_storage_multisample_2d_array GL_OES_shader_image_atomic GL_EXT_robustness GL_EXT_draw_buffers_indexed GL_OES_draw_buffers_indexed GL_EXT_texture_border_clamp GL_OES_texture_border_clamp GL_EXT_texture_cube_map_array GL_OES_texture_cube_map_array GL_OES_sample_variables GL_OES_sample_shading GL_OES_shader_multisample_interpolation GL_EXT_shader_io_blocks GL_OES_shader_io_blocks GL_EXT_tessellation_shader GL_OES_tessellation_shader GL_EXT_primitive_bounding_box GL_OES_primitive_bounding_box GL_EXT_geometry_shader GL_OES_geometry_shader GL_ANDROID_extension_pack_es31a GL_EXT_gpu_shader5 GL_OES_gpu_shader5 GL_EXT_texture_buffer GL_OES_texture_buffer GL_EXT_copy_image GL_OES_copy_image GL_EXT_shader_non_constant_global_initializers GL_EXT_color_buffer_half_float GL_EXT_color_buffer_float GL_EXT_YUV_target GL_OVR_multiview GL_OVR_multiview2 GL_OVR_multiview_multisampled_render_to_texture GL_KHR_robustness GL_KHR_robust_buffer_access_behavior GL_EXT_draw_elements_base_vertex GL_OES_draw_elements_base_vertex GL_EXT_protected_textures GL_EXT_buffer_storage GL_EXT_external_buffer GL_EXT_EGL_image_array GL_ARM_texture_unnormalized_coordinates 
RenderEngine supports protected context: 0
RenderEngine is in protected context: 0
RenderEngine program cache size for unprotected context: 64
RenderEngine program cache size for protected context: 0
RenderEngine last dataspace conversion: (Default) to (BT709 sRGB Full range)
RenderEngine image cache size: 9
Dumping buffer ids...
0xa600000f94
0xa600000f95
0xa600000f96
0xa6000000b6
0xa6000000b5
0xa600000113
0xa600000f93
0xa6000000b4
0xa6000000b7
RenderEngine framebuffer image cache size: 3
Dumping buffer ids...
0xa600000003
0xa600000002
0xa600000001
  Region undefinedRegion (this=0xe8107738, count=1)
    [  0,   0,   0,   0]
  orientation=ROTATION_0, isPoweredOn=1
  transaction-flags         : 00000000
  gpu_to_cpu_unsupported    : 0
  refresh-rate              : 78.000005 fps
  x-dpi                     : 79.685997
  y-dpi                     : 239.057999
  transaction time: 0.000000 us
Tracing state: disabled
  number of entries: 0 (0.00MB / 0.00MB)

Display 0 HWC layers:
-----------------------------------------------------------------------------------------------------------------------------------------------
 Layer name
           Z |  Window Type |  Comp Type |  Transform |   Disp Frame (LTRB) |          Source Crop (LTRB) |     Frame Rate (Explicit) [Focused]
-----------------------------------------------------------------------------------------------------------------------------------------------
 com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
  rel      0 |            1 |     CLIENT |          0 |    0    0  480  800 |    0.0    0.0  480.0  800.0 |                              [*]
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
 StatusBar#0
  rel      0 |         2000 |     CLIENT |          0 |    0    0  480   52 |    0.0    0.0  480.0   52.0 |                              [ ]
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

h/w composer state:
  h/w composer enabled
-- HWC2On1Adapter --
Adapting to a HWC 1.4 device
Capabilities:
  PresentFenceIsNotReliable
  SidebandStream
Displays:
  Display 1: Physical  HWC1 ID: 0  Power mode: On  Vsync: Disable
    Color modes [active]: [0]
    1 Config (* active)
    * 480 x 800 @ 78.0 Hz, DPI: 79.7 x 239.1
        HWC1 ID/Color transform: [1/0]
    2 Layers
      Client Layer  HWC2/1: 36/0  Z: 0  Buffer: 0xf09bee00
        Display frame [LTRB]: [0, 0, 480, 800]
        Source crop: [0, 0, 480, 800]
        Transform: None  Blend mode: None DataSpace: 0
        Visible Region                  Surface Damage
        [0, 0, 480, 800]                None
      Client Layer  HWC2/1: 34/1  Z: 1  Buffer: 0xf09beb00
        Display frame [LTRB]: [0, 0, 480, 52]
        Source crop: [0, 0, 480, 52]
        Transform: None  Blend mode: Premultiplied DataSpace: 0
        Visible Region                  Surface Damage
        [0, 0, 480, 52]                 None
    Client target: 0xf09be700
    Last requested HWC1 state
      Geometry changed: N
      3 Layers
        Layer 0  Composition: Framebuffer  Buffer: 0xf09bee00/-1
          Display frame: [0, 0, 480, 800]
          Source crop: [0, 0, 480, 800]
          Transform: None  Blend mode: None
        Layer 1  Composition: Framebuffer  Buffer: 0xf09beb00/-1
          Display frame: [0, 0, 480, 52]
          Source crop: [0, 0, 480, 52]
          Transform: None  Blend mode: Premultiplied
        Layer 2  Composition: FramebufferTarget  Buffer: 0xf09be700/-1
          Display frame: [0, 0, 480, 800]
          Source crop: [0, 0, 480, 800]
          Transform: None  Blend mode: Premultiplied

HWC1 dump:
DrmCompositor stats:
--DrmDisplayCompositor[0]: num_frames=33 num_ms=1106 fps=29.8373
----DrmDisplayComposition crtc=59 type=FRAME timeline[current/squash/pre-comp/done]=0/0/0/1
    Layers: count=1
DrmHwcLayer[0] buffer[w/h/format]=480/800/DRM_FORMAT_ABGR8888 transform=<invalid> blending[a=255]=PREMULT source_crop[x/y/w/h]=0/0/480/800 handle parameter[w/h/s]=480/800/480 display_frame[x/y/w/h]=0/0/480/800
    Planes: count=6
DrmCompositionPlane[0] plane=58 type=LAYER
DrmCompositionPlane[1] plane=57 type=DISABLE
DrmCompositionPlane[2] plane=61 type=DISABLE
DrmCompositionPlane[3] plane=62 type=DISABLE
DrmCompositionPlane[4] plane=63 type=DISABLE
DrmCompositionPlane[5] plane=60 type=DISABLE
    Squash Regions: count=0
    Pre-Comp Regions: count=0
----SquashState generation=0 history=0
    Regions: count=0
--DrmDisplayCompositor[1]: num_frames=0 num_ms=1106 fps=0
----SquashState generation=0 history=0
    Regions: count=0
GraphicBufferAllocator buffers:
0xe5baa600: unknown     |  480 (   0) x  800 |    1 |        1 | 0x40000000000b00 | com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
0xe5baa900: unknown     | 1280 (   0) x 1280 |    1 |        2 | 0x40000000000b00 | com.android.systemui.ImageWallpaper#0
0xe613b000: unknown     |  480 (   0) x  800 |    1 |        1 | 0x40000000000b00 | com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
0xe7b52700: 1500.00 KiB |  480 ( 480) x  800 |    1 |        1 | 0x333 | screenshot
0xe7b52800: 1500.00 KiB |  480 ( 480) x  800 |    1 |        1 | 0x333 | screenshot
0xe7b52a00: unknown     |  480 (   0) x   52 |    1 |        1 | 0x40000000000b00 | StatusBar#0
0xe7b52b00: unknown     |  480 (   0) x   52 |    1 |        1 | 0x40000000000b00 | StatusBar#0
0xe7b52c00: unknown     |  480 (   0) x   52 |    1 |        1 | 0x40000000000b00 | StatusBar#0
0xe7b52d00: unknown     |  480 (   0) x   52 |    1 |        1 | 0x40000000000b00 | StatusBar#0
0xe7b52e00: unknown     |  480 (   0) x  800 |    1 |        1 | 0x40000000000b00 | com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
0xe7b52f00: unknown     |  480 (   0) x  800 |    1 |        1 | 0x40000000000b00 | com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
0xe7c3c200: unknown     |  480 (   0) x  800 |    1 |        1 | 0x1a00 | FramebufferSurface
0xe7c3c300: unknown     |  480 (   0) x  800 |    1 |        1 | 0x1a00 | FramebufferSurface
0xe7c3c400: unknown     |  480 (   0) x  800 |    1 |        1 | 0x1a00 | FramebufferSurface
0xe7c3ca00: unknown     |  480 (   0) x  800 |    1 |        1 | 0x40000000000b00 | com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
0xe81e3900: unknown     |    1 (   0) x    1 |    1 |        1 | 0x300 | placeholder
Total allocated by GraphicBufferAllocator (estimate): 3000.00 KB
Imported gralloc buffers:
+ name:screenshot, id:850403525403, size:1.5e+03KiB, w/h:480x800, usage: 0x333, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:screenshot, id:850403525402, size:1.5e+03KiB, w/h:480x800, usage: 0x333, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0, id:850403525389, size:1.5e+03KiB, w/h:480x800, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0, id:850403525387, size:1.5e+03KiB, w/h:480x800, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0, id:850403525340, size:1.5e+03KiB, w/h:480x800, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:com.android.systemui.ImageWallpaper#0, id:850403524666, size:6.4e+03KiB, w/h:1280x1280, usage: 0x40000000000b00, req fmt:2, fourcc/mod:875709016/0, compressed: false
	planes: R/G/B:	 w/h:1280x1280, stride:5120 bytes, size:6553600
+ name:StatusBar#0, id:850403524657, size:98KiB, w/h:480x52, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x52, stride:1920 bytes, size:99840
+ name:StatusBar#0, id:850403524659, size:98KiB, w/h:480x52, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x52, stride:1920 bytes, size:99840
+ name:StatusBar#0, id:850403524656, size:98KiB, w/h:480x52, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x52, stride:1920 bytes, size:99840
+ name:com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0, id:850403525390, size:1.5e+03KiB, w/h:480x800, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:StatusBar#0, id:850403524658, size:98KiB, w/h:480x52, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x52, stride:1920 bytes, size:99840
+ name:placeholder, id:850403524608, size:0.062KiB, w/h:1x1, usage: 0x300, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:1x1, stride:64 bytes, size:64
+ name:com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0, id:850403525388, size:1.5e+03KiB, w/h:480x800, usage: 0x40000000000b00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:FramebufferSurface, id:850403524610, size:1.5e+03KiB, w/h:480x800, usage: 0x1a00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:FramebufferSurface, id:850403524609, size:1.5e+03KiB, w/h:480x800, usage: 0x1a00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
+ name:FramebufferSurface, id:850403524611, size:1.5e+03KiB, w/h:480x800, usage: 0x1a00, req fmt:1, fourcc/mod:875708993/0, compressed: false
	planes: R/G/B/A:	 w/h:480x800, stride:1920 bytes, size:1536000
Total imported by gralloc: 2.2e+04KiB
TimeStats miniDump:
Number of layers currently being tracked is 0
Number of layers in the stats pool is 0

+ ContainerLayer (Root#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000002, tr=[0.00, 0.00][0.00, 0.00]
      parent=none
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (mWindowContainers#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (DisplayArea.Root#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=mWindowContainers#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (Leaf:0:1#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DisplayArea.Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WallpaperWindowToken{1c84b2f token=android.os.Binder@478750e}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:0:1#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (b34735b com.android.systemui.ImageWallpaper#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WallpaperWindowToken{1c84b2f token=android.os.Binder@478750e}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ BufferQueueLayer (com.android.systemui.ImageWallpaper#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(-24,-40), size=(1280,1280), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=RGBx_8888, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000003, tr=[0.69, 0.00][0.00, 0.69]
      parent=b34735b com.android.systemui.ImageWallpaper#0
      zOrderRelativeOf=none
      activeBuffer=[1280x1280:   0,RGBx_8888], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={windowType:2013, ownerUID:10099}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (Leaf:2:2#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        1, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DisplayArea.Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (DefaultTaskDisplayArea#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        2, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DisplayArea.Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ EffectLayer (Task=1#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0, 480, 800], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(-1.000,-1.000,-1.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DefaultTaskDisplayArea#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={taskId:1}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ EffectLayer (Task=39#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(-1.000,-1.000,-1.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Task=1#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={taskId:39}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (ActivityRecord{2e726c1 u0 com.wetao.elauncher/.ui.main.MainActivity#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Task=39#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (75e9b58 com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=ActivityRecord{2e726c1 u0 com.wetao.elauncher/.ui.main.MainActivity#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ BufferQueueLayer (com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=1)
    [  0,   0, 480, 800]
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=( 480, 800), crop=[  0,   0, 480, 800], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=RGBA_8888, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000002, tr=[0.00, 0.00][0.00, 0.00]
      parent=75e9b58 com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
      zOrderRelativeOf=none
      activeBuffer=[ 480x 800:   0,RGBA_8888], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={windowType:1, ownerUID:1000}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (ImeContainer#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        1, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=ActivityRecord{2e726c1 u0 com.wetao.elauncher/.ui.main.MainActivity#0
      zOrderRelativeOf=75e9b58 com.wetao.elauncher/com.wetao.elauncher.ui.main.MainActivity#0
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{31fa5ac android.os.Binder@654e75f}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=ImeContainer#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ EffectLayer (Surface(name=db128f6 InputMethod)/@0xf78c5cd - animation-leash#1)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,800), size=(   0,   0), crop=[  0,   0,   0,   0], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(-1.000,-1.000,-1.000,1.000), flags=0x00000001, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{31fa5ac android.os.Binder@654e75f}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (db128f6 InputMethod#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,800), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Surface(name=db128f6 InputMethod)/@0xf78c5cd - animation-leash#1
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (homeAnimationLayer#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        1, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DefaultTaskDisplayArea#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (splitScreenDividerAnchor#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        2, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DefaultTaskDisplayArea#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (animationLayer#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        3, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DefaultTaskDisplayArea#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (boostedAnimationLayer#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        4, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DefaultTaskDisplayArea#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (Leaf:3:14#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        3, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DisplayArea.Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{6897632 android.os.BinderProxy@d99e394}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:3:14#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (736bf83 AssistPreviewPanel#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,800), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{6897632 android.os.BinderProxy@d99e394}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (Leaf:17:34#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        5, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=DisplayArea.Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{ecd84d5 android.os.BinderProxy@c932abf}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:17:34#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ EffectLayer (Surface(name=db8a4ea StatusBar)/@0xf5a24d1 - animation-leash#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,   0,   0], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(-1.000,-1.000,-1.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{ecd84d5 android.os.BinderProxy@c932abf}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (db8a4ea StatusBar#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Surface(name=db8a4ea StatusBar)/@0xf5a24d1 - animation-leash#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ BufferQueueLayer (StatusBar#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=1)
    [  0,   0, 480,  52]
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=( 480,  52), crop=[  0,   0, 480,  52], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=0, dataspace=Default, defaultPixelFormat=RGBA_8888, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=db8a4ea StatusBar#0
      zOrderRelativeOf=none
      activeBuffer=[ 480x  52:   0,RGBA_8888], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={windowType:2000, ownerUID:10099}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{3dda360 android.os.BinderProxy@fa7f592}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        1, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:17:34#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (9660019 NotificationShade#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{3dda360 android.os.BinderProxy@fa7f592}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{11bd0df android.os.BinderProxy@f6b7139}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        2, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:17:34#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ EffectLayer (Surface(name=df6112c NavigationBar0)/@0xb3f8b36 - animation-leash#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,800), size=(   0,   0), crop=[  0,   0,   0,   0], cornerRadius=0.000000, isProtected=0, isOpaque=1, invalidate=0, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(-1.000,-1.000,-1.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{11bd0df android.os.BinderProxy@f6b7139}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (df6112c NavigationBar0#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,800), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Surface(name=df6112c NavigationBar0)/@0xb3f8b36 - animation-leash#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ BufferQueueLayer (NavigationBar0#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,800), size=( 480,   1), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=0, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000001, tr=[0.00, 0.00][0.00, 0.00]
      parent=df6112c NavigationBar0#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={windowType:2019, ownerUID:10099}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{664242d android.os.BinderProxy@9b43b44}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        3, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:17:34#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (3774d62 pip-dismiss-overlay#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(0,458), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{664242d android.os.BinderProxy@9b43b44}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{b1e5660 android.os.BinderProxy@419da63}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        4, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:17:34#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (87c3719 EdgeBackGestureHandler0#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(240,400), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{b1e5660 android.os.BinderProxy@419da63}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (WindowToken{a249178 android.os.BinderProxy@e2632db}#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        5, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Leaf:17:34#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (b4b051 SecondaryHomeHandle0#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        0, pos=(240,400), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=WindowToken{a249178 android.os.BinderProxy@e2632db}#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 
+ ContainerLayer (mOverlayContainers#0)
  Region TransparentRegion (this=0 count=0)
  Region VisibleRegion (this=0 count=0)
  Region SurfaceDamageRegion (this=0 count=0)
      layerStack=   0, z=        1, pos=(0,0), size=(   0,   0), crop=[  0,   0,  -1,  -1], cornerRadius=0.000000, isProtected=0, isOpaque=0, invalidate=1, dataspace=Default, defaultPixelFormat=Unknown/None, backgroundBlurRadius=0, color=(0.000,0.000,0.000,1.000), flags=0x00000000, tr=[0.00, 0.00][0.00, 0.00]
      parent=Root#0
      zOrderRelativeOf=none
      activeBuffer=[   0x   0:   0,Unknown/None], tr=[0.00, 0.00][0.00, 0.00] queued-frames=0, mRefreshPending=0, metadata={}, cornerRadiusCrop=[0.00, 0.00, 0.00, 0.00],  shadowRadius=0.000, 

Offscreen Layers:
Layer Surface(name=db128f6 InputMethod)/@0xf78c5cd - animation-leash#0 (EffectLayer) pid:389 uid:1000
