## adc-rheia-v59.im4p

> `Firmware/isp_bni/adc-rheia-v59.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._rtk_smp_main`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`

```diff

-  __TEXT.__text: 0x9e7d44
-  __TEXT.__const: 0x95b578
-  __TEXT.__cstring: 0x94dc1
+  __TEXT.__text: 0x9e8234
+  __TEXT.__const: 0x95b708
+  __TEXT.__cstring: 0x94f6b
   __TEXT.text_env: 0x4f1a4
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__eh_frame: 0x20c
-  __DATA.__const: 0x4c540
+  __DATA.__const: 0x4c600
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xde8e0
   __DATA._rtk_power: 0x3f8

   __DATA.__mod_init_func: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0x7028f8
-  Functions: 8348
+  Functions: 8351
   Symbols:   0
-  CStrings:  16230
+  CStrings:  16240
 
CStrings:
+ "22:24:36"
+ "IC[%zu] frameSkip set to 1 at ic stopping\n"
+ "NVM header revision invalid %d - off %d\n"
+ "ch %zu: forced ProcessStopped() after %u SIF errors in IC_STOPPING"
+ "ch%zu wasPaused %d now %f RVsync %f FVsync %f\n"
+ "transition_mode019_to_mode550_revert_step0"
+ "transition_mode019_to_mode550_revert_step1"
+ "transition_mode019_to_mode550_step0"
+ "transition_mode019_to_mode550_step1"
+ "transition_mode019_to_mode650_revert_step0"
+ "transition_mode019_to_mode650_revert_step1"
+ "transition_mode019_to_mode650_step0"
+ "transition_mode019_to_mode650_step1"
- "00:34:16"
- "NVM header revision invalid\n"
- "ch %zu FC: %d Full Res Host Meta Data buffer not available"
```
