---
title: extra beefy blog boys
---
CPU:
  Info: model: N/A variant: cortex-a72 bits: 64 type: MCP arch: ARMv8
    family: 8 model-id: 0 stepping: 3
  Topology: cpus: 1x cores: 4 smt: <unsupported> cache: L1: 320 KiB
    desc: d-4x32 KiB; i-4x48 KiB L2: 1024 KiB desc: 1x1024 KiB
  Speed (MHz): avg: 1800 min/max: 600/1800 scaling: driver: cpufreq-dt
    governor: ondemand cores: 1: 1800 2: 1800 3: 1800 4: 1800
    bogomips: 432
  Features: asimd cpuid crc32 evtstrm fp
  Vulnerabilities:
  Type: gather_data_sampling status: Not affected
  Type: indirect_target_selection status: Not affected
  Type: itlb_multihit status: Not affected
  Type: l1tf status: Not affected
  Type: mds status: Not affected
  Type: meltdown status: Not affected
  Type: mmio_stale_data status: Not affected
  Type: reg_file_data_sampling status: Not affected
  Type: retbleed status: Not affected
  Type: spec_rstack_overflow status: Not affected
  Type: spec_store_bypass status: Vulnerable
  Type: spectre_v1 mitigation: __user pointer sanitization
  Type: spectre_v2 status: Vulnerable
  Type: srbds status: Not affected
  Type: tsx_async_abort status: Not affected
