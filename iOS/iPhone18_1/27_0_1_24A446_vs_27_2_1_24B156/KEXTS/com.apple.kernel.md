## com.apple.kernel

> `com.apple.kernel`

```diff

-13432.2.10.0.0
-  __TEXT.__const: 0x370b0
+13432.42.3.0.0
+  __TEXT.__const: 0x37180
   __TEXT.__copyio_vectors: 0x2c0
-  __TEXT.__cstring: 0x8ca67
-  __TEXT.__os_log: 0x41afb
+  __TEXT.__cstring: 0x8d5cc
+  __TEXT.__os_log: 0x41fdc
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x120
-  __DATA_CONST.__const: 0x121758
-  __DATA_CONST.__kalloc_type: 0x14fc0
-  __DATA_CONST.__assert: 0x148c
-  __DATA_CONST.__kalloc_var: 0x7e90
+  __DATA_CONST.__const: 0x121850
+  __DATA_CONST.__assert: 0x1630
+  __DATA_CONST.__kalloc_type: 0x15080
+  __DATA_CONST.__kalloc_var: 0x8020
   __DATA_CONST.__exclaves_bt: 0xc0
   __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_SPTM.__const: 0x4c000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x8f92f4
+  __TEXT_EXEC.__text: 0x900618
   __TEXT_EXEC.__hib_text: 0x10d8
   __TEXT_BOOT_EXEC.__bootcode: 0x6aec
   __KLD.__text: 0x173c

   __LAST.__pinst: 0x8
   __LAST.__last: 0x0
   __KLDDATA.__cstring: 0x6e1
-  __KLDDATA.__const: 0x3e60
+  __KLDDATA.__const: 0x3ed8
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x18269
-  __DATA.__lock_grp: 0x5cd0
+  __DATA.__lock_grp: 0x5d28
   __DATA.__percpu: 0x78b0
-  __DATA.__common: 0x7b6c8
-  __DATA.__bss: 0xa53b0
+  __DATA.__common: 0x7b808
+  __DATA.__bss: 0xa55b0
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__static_if: 0x1100
-  __BOOTDATA.__init_entry_set: 0x14ca0
-  __BOOTDATA.__init: 0x178b8
+  __BOOTDATA.__static_if: 0x1110
+  __BOOTDATA.__init_entry_set: 0x14dc0
+  __BOOTDATA.__init: 0x17938
   __BOOTDATA.__static_ifinit: 0x20
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x48d28
-  Functions: 21793
+  __LINKINFO.__symbolsets: 0x48de8
+  Functions: 21843
   Symbols:   0
-  CStrings:  21103
+  CStrings:  21170
 
CStrings:
+ "!os_add_overflow(*__counter, page_count, __counter)"
+ "!os_sub_overflow(*__counter, e->vmsk_page_count, __counter)"
+ "%s: <pid %d> Disallow request nexus with flow divert result\n"
+ "%s: d_from detach pending error %d"
+ "%s: d_to detach pending error %d"
+ "%s: mbuf %p len (%u) < off+len (%u+%u) @%s:%d"
+ "%s: rejecting AF_LINK gateway on index %u with unusable link address (nlen %u, alen %u, sdl_len %u)\n"
+ "%s: route %s on %s%d link address does not fit (sdl_alen %u, error %d)\n"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/xnu/bsd/net/iptap.c"
+ "1122122"
+ "121121111112111111111"
+ "221111212122222211222221112"
+ "22111220222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222220222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
+ "22212111221122112211102222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222220222221111112121111222221112221222222222222221122222112"
+ "22222211111311111221"
+ "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}][14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQCCACQQQiBBBB^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1b2b1b6c[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vCCCCIQ{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}IQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}^v^vIQC{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}AQ}8"
+ "Controls whether applications are eligible to have their memory swapped under pressure"
+ "FilterDropBadDirection"
+ "I16@?0{xnuupcallsv2_xnucontentupcallsprivate_unloadmemorywithflags__result_s=C(?=I)}8"
+ "I24@?0{xnuupcallsv2_aneupcallsprivate_updatexnucontentwithflags__result_s=C(?={xnuupcallsv2_driverupcallerror_s=Q}Q)}8"
+ "I28@?0r^{xnumemorydescid_v_s=C(?={?=^QQ@?}{?=*QQ}{?=^{tb_message_s}QQQ})}8I16@?<I@?{xnuupcallsv2_xnucontentupcallsprivate_unloadmemorywithflags__result_s=C(?=I)}>20"
+ "I44@?0Q8Q16r^{xnuupcallsv2_xnucontentrange_v_s=C(?={?=^{xnuupcallsv2_xnucontentrange_s}Q@?}{?=*QQ}{?=^{tb_message_s}QQQ})}24I32@?<I@?{xnuupcallsv2_aneupcallsprivate_updatexnucontentwithflags__result_s=C(?={xnuupcallsv2_driverupcallerror_s=Q}Q)}>36"
+ "Memory error logging started\n"
+ "Page modified after framebank withdraw %p\n @%s:%d"
+ "RETRY SESSION (Signing Identifier Drop)"
+ "SK[%u]: %-30s %s(%d): %d: skip cls_len < l3hlen + l4hlen\n"
+ "SK[%u]: %-30s %s(%d): EINVAL: SYNCF_ALLOC_BUF without buflet alloc ring\n"
+ "SK[%u]: %-30s %s(%d): EINVAL: SYNCF_LARGE_ALLOC with SYNCF_ALLOC/ALLOC_BUF\n"
+ "SK[%u]: %-30s %s(%d): EINVAL: SYNCF_LARGE_ALLOC without large buffer alloc ring\n"
+ "SK[%u]: %-30s %s(%d): EINVAL: unknown flags 0x%x\n"
+ "SK[%u]: %-30s Tx flow port %d != channel port %d, %s\n"
+ "SK[%u]: %-30s dropped packet injected on ring %u whose wrap flag does not match the ring direction: pkt_pflags 0x%llx\n"
+ "SK[%u]: %-30s filter packet is not mbuf-wrapped: pkt_pflags 0x%llx\n"
+ "SK[%u]: %-30s filter packet is not packet-wrapped: pkt_pflags 0x%llx\n"
+ "The lifetime number of pages freed while still on the speculative queue outside of pageout scan"
+ "The lifetime number of pages that already held content and were put on the speculative queue rather than filled speculatively"
+ "The lifetime number of times pageout scan took a page off the speculativequeue as a reclaim candidate and put it on the inactive queue"
+ "VM entry %p lock shared lock overflow <v:%d c:%c%c w:%c%c %c/%d> @%s:%d"
+ "_dtlecnt != 0"
+ "_in6m->in6m_in_dtle == true"
+ "_inm->inm_in_dtle == true"
+ "bklb-backlight-dc"
+ "bklb-backlight-frequency"
+ "com.apple.private.verified-jit-mode"
+ "com.apple.private.vfs.unmunged-access-time"
+ "com.apple.security.cs.debugger"
+ "entry != ((void*)0)"
+ "entry != NULL"
+ "iBoot reported a total memory size of 0x%llx, below the 0x%llx bytes it handed to XNU @%s:%d"
+ "ifnet_detach failed: %d @%s:%d"
+ "inconsistent DRAM size reported by iBoot: dram-size 0x%llx, memSizeActual 0x%llx @%s:%d"
+ "inm->in6m_dtlecnt != 0"
+ "inm->inm_dtlecnt != 0"
+ "ipc_misc.c"
+ "ipr != ((void*)0)"
+ "iptap != NULL"
+ "kr == KERN_SUCCESS"
+ "memory override is too small to boot; check the maxmem/memsize boot-args @%s:%d"
+ "memory override is too small to boot;check the maxmem/memsize boot-args @%s:%d"
+ "memorystatus: purged %llu KiB of deferred SK pages\n"
+ "memsize=%u MB leaves no memory for XNU/SPTM to manage: the iBoot carveouts alone are %llu MB @%s:%d"
+ "necp_set_socket_resolver_signature_from_parameters"
+ "nx_netif_filter_pkt_to_mbuf"
+ "nx_netif_filter_pkt_to_pkt"
+ "pktap != NULL"
+ "pktap_build_mbuf_header"
+ "prev_entry != ((void*)0)"
+ "ret == TB_ERROR_SUCCESS"
+ "rt_setgate"
+ "site.struct flow_divert_pcb_handle"
+ "site.struct vm_sk_deferred_entry"
+ "size <= sdl->sdl_alen"
+ "speculative_pages_demoted"
+ "speculative_pages_freed"
+ "speculative_pages_requeued_inactive"
+ "swap_all_apps"
+ "table != ((void*)0)"
+ "unloadMemoryWithFlags"
+ "updateXnuContentWithFlags"
+ "v832@?0{exclaveindicatorcontroller_sensorrequestmetrics_s=QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ}8"
+ "vm: configured segment limit would overflow slot mapping index, reducing to %d\n"
+ "vm_sk_deferred.c"
+ "vm_sk_deferred: failed to start drain thread (%d) @%s:%d"
+ "vm_sk_deferred_drain"
- "%s: mbuf %p len (%d) < off+len (%d+%d) @%s:%d"
- "12112111111211111111"
- "2211112121222222111222221112"
- "221112202222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
- "222121112211221122111022222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221111112121111222221112221222222222222221122222112"
- "2222221111131111121"
- "B16@?0^{task={lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}{os_refcnt=AI}BBBBIIQ^{_vm_map}{queue_entry=^{queue_entry}^{queue_entry}}^{task_watchports}^v{queue_entry=^{queue_entry}^{queue_entry}}^{restartable_ranges}^{processor_set}^{affinity_space}iIiiissiQ{recount_task=^{recount_track}^{recount_usage}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}[4^{ipc_port}][14{exception_action=^{ipc_port}iiii^{label}}]{hardened_exception_action={exception_action=^{ipc_port}iiii^{label}}II}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}^{ipc_port}[3^{ipc_port}]^^{ipc_port}^{ipc_space}^{task_token_data}^{ledger}{queue_entry=^{queue_entry}^{queue_entry}}iI^vQQCCACQQQiBBBB^Q^Q^Q^Q^Q^QIIIIII^{proc_ro}^{kcdata_descriptor}Q{queue_entry=^{queue_entry}^{queue_entry}}^{label}IIQQ{cpc_task=B}ACBBBBb4b4b4b4CCCCCB*^{vm_shared_region}QQQ^{thread_call}{queue_entry=^{queue_entry}^{queue_entry}}ii^{bank_task}^{ipc_importance_task}{vm_extmod_statistics=qqqqqq}{task_requested_policy=b1b1b2b2b1b1b2b1b3b3b3b1b5b3b3b1b3b1b1b3b1b3b1b1b1b4b12}{task_effective_policy=b1b1b2b1b1b1b2b1b1b3b3b1b1b1b4b1b1b1b3b3b1b1b1b1b1b26}{task_pend_token=(?={?=b1b1b1b1b1b1b1b1b1b1b1b1b1b1}I)}b1b1b1b1b1b27AI^{io_stat_info}{task_writes_counters=QQQQ}{task_writes_counters=QQQQ}{_cpu_time_qos_stats=QQQQQQQ}{_cpu_time_qos_stats=QQQQQQQ}IIQQCCCiii{queue_entry=^{queue_entry}^{queue_entry}}{lck_mtx_s=b24b8I(lck_mtx_state={?=b28b1b1b1b1SS}IQ)}b16b1b1b1b1b1b1b1b2b7[2^{coalition}][2{queue_entry=^{queue_entry}^{queue_entry}}]Q^vCCCCIQ{queue_entry=^{queue_entry}^{queue_entry}}{queue_entry=^{queue_entry}^{queue_entry}}iIQQ[16C]Q^{_vmobject_list_output_}II^{vm_deferred_reclamation_metadata_s}^v^vIQC{task_security_config=(?={?=b1b1b1b3b1b1b1b1b1b1C}I)}AQ}8"
- "Exclaves requirements which have been relaxed"
- "External objects are not implemented for CoW. %p %i %i %llx %llx @%s:%d"
- "exclaves_relaxed_requirements"
- "memorystatus: swap is disabled, bypassing fast-wake warmup\n"
- "pktap_bpf_tap"
- "protect_privileged_from_untrusted"
- "sdl->sdl_alen == size"
- "utun_flowswitch_attach - ifnet_detach failed: %d @%s:%d"
- "v344@?0{exclaveindicatorcontroller_sensorrequestmetrics_s=QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ}8"
- "vm_protect_privileged_from_untrusted"
```
