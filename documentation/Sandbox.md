# SandBox




    (amd64)ubuntu@localhost:~$ dmesg
    [    0.000000] Initializing cgroup subsys cpuset
    [    0.000000] Initializing cgroup subsys cpu
    [    0.000000] Initializing cgroup subsys cpuacct
    [    0.000000] Linux version 3.19.0-33-generic (buildd@lgw01-44) (gcc version 4.9.2 (Ubuntu 4.9.2-10ubuntu13) ) #38-Ubuntu SMP Fri Nov 6 18:18:12 UTC 2015 (Ubuntu 3.19.0-33.38-generic 3.19.8-ckt7)
    [    0.000000] Command line: BOOT_IMAGE=(hd0,gpt2)/EFI/ubuntu/grub/a/vmlinuz root=LABEL=system-a ro init=/lib/systemd/systemd console=ttyS0 console=tty1 panic=-1
    [    0.000000] KERNEL supported cpus:
    [    0.000000]   Intel GenuineIntel
    [    0.000000]   AMD AuthenticAMD
    [    0.000000]   Centaur CentaurHauls
    [    0.000000] e820: BIOS-provided physical RAM map:
    [    0.000000] BIOS-e820: [mem 0x0000000000000000-0x000000000009fbff] usable
    [    0.000000] BIOS-e820: [mem 0x000000000009fc00-0x000000000009ffff] reserved
    [    0.000000] BIOS-e820: [mem 0x00000000000f0000-0x00000000000fffff] reserved
    [    0.000000] BIOS-e820: [mem 0x0000000000100000-0x000000001fffdfff] usable
    [    0.000000] BIOS-e820: [mem 0x000000001fffe000-0x000000001fffffff] reserved
    [    0.000000] BIOS-e820: [mem 0x00000000feffc000-0x00000000feffffff] reserved
    [    0.000000] BIOS-e820: [mem 0x00000000fffc0000-0x00000000ffffffff] reserved
    [    0.000000] NX (Execute Disable) protection: active
    [    0.000000] SMBIOS 2.4 present.
    [    0.000000] DMI: QEMU Standard PC (i440FX + PIIX, 1996), BIOS Bochs 01/01/2011
    [    0.000000] Hypervisor detected: KVM
    [    0.000000] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
    [    0.000000] e820: remove [mem 0x000a0000-0x000fffff] usable
    [    0.000000] AGP: No AGP bridge found
    [    0.000000] e820: last_pfn = 0x1fffe max_arch_pfn = 0x400000000
    [    0.000000] MTRR default type: write-back
    [    0.000000] MTRR fixed ranges enabled:
    [    0.000000]   00000-9FFFF write-back
    [    0.000000]   A0000-BFFFF uncachable
    [    0.000000]   C0000-FFFFF write-protect
    [    0.000000] MTRR variable ranges enabled:
    [    0.000000]   0 base 0080000000 mask FF80000000 uncachable
    [    0.000000]   1 disabled
    [    0.000000]   2 disabled
    [    0.000000]   3 disabled
    [    0.000000]   4 disabled
    [    0.000000]   5 disabled
    [    0.000000]   6 disabled
    [    0.000000]   7 disabled
    [    0.000000] PAT not supported by CPU.
    [    0.000000] found SMP MP-table at [mem 0x000f0b20-0x000f0b2f] mapped at [ffff8800000f0b20]
    [    0.000000] Scanning 1 areas for low memory corruption
    [    0.000000] Base memory trampoline at [ffff880000099000] 99000 size 24576
    [    0.000000] init_memory_mapping: [mem 0x00000000-0x000fffff]
    [    0.000000]  [mem 0x00000000-0x000fffff] page 4k
    [    0.000000] BRK [0x01fe5000, 0x01fe5fff] PGTABLE
    [    0.000000] BRK [0x01fe6000, 0x01fe6fff] PGTABLE
    [    0.000000] BRK [0x01fe7000, 0x01fe7fff] PGTABLE
    [    0.000000] init_memory_mapping: [mem 0x1fc00000-0x1fdfffff]
    [    0.000000]  [mem 0x1fc00000-0x1fdfffff] page 2M
    [    0.000000] init_memory_mapping: [mem 0x00100000-0x1fbfffff]
    [    0.000000]  [mem 0x00100000-0x001fffff] page 4k
    [    0.000000]  [mem 0x00200000-0x1fbfffff] page 2M
    [    0.000000] init_memory_mapping: [mem 0x1fe00000-0x1fffdfff]
    [    0.000000]  [mem 0x1fe00000-0x1fffdfff] page 4k
    [    0.000000] BRK [0x01fe8000, 0x01fe8fff] PGTABLE
    [    0.000000] RAMDISK: [mem 0x1e95c000-0x1f76afff]
    [    0.000000] ACPI: Early table checksum verification disabled
    [    0.000000] ACPI: RSDP 0x00000000000F0990 000014 (v00 BOCHS )
    [    0.000000] ACPI: RSDT 0x000000001FFFFBC1 000034 (v01 BOCHS  BXPCRSDT 00000001 BXPC 00000001)
    [    0.000000] ACPI: FACP 0x000000001FFFF1C0 000074 (v01 BOCHS  BXPCFACP 00000001 BXPC 00000001)
    [    0.000000] ACPI: DSDT 0x000000001FFFE040 001180 (v01 BOCHS  BXPCDSDT 00000001 BXPC 00000001)
    [    0.000000] ACPI: FACS 0x000000001FFFE000 000040
    [    0.000000] ACPI: SSDT 0x000000001FFFF234 0008DD (v01 BOCHS  BXPCSSDT 00000001 BXPC 00000001)
    [    0.000000] ACPI: APIC 0x000000001FFFFB11 000078 (v01 BOCHS  BXPCAPIC 00000001 BXPC 00000001)
    [    0.000000] ACPI: HPET 0x000000001FFFFB89 000038 (v01 BOCHS  BXPCHPET 00000001 BXPC 00000001)
    [    0.000000] ACPI: Local APIC address 0xfee00000
    [    0.000000] No NUMA configuration found
    [    0.000000] Faking a node at [mem 0x0000000000000000-0x000000001fffdfff]
    [    0.000000] NODE_DATA(0) allocated [mem 0x1fff9000-0x1fffdfff]
    [    0.000000] kvm-clock: Using msrs 4b564d01 and 4b564d00
    [    0.000000] kvm-clock: cpu 0, msr 0:1fff5001, primary cpu clock
    [    0.000000]  [ffffea0000000000-ffffea00007fffff] PMD -> [ffff88001e000000-ffff88001e7fffff] on node 0
    [    0.000000] Zone ranges:
    [    0.000000]   DMA      [mem 0x00001000-0x00ffffff]
    [    0.000000]   DMA32    [mem 0x01000000-0x1fffdfff]
    [    0.000000]   Normal   empty
    [    0.000000] Movable zone start for each node
    [    0.000000] Early memory node ranges
    [    0.000000]   node   0: [mem 0x00001000-0x0009efff]
    [    0.000000]   node   0: [mem 0x00100000-0x1fffdfff]
    [    0.000000] Initmem setup node 0 [mem 0x00001000-0x1fffdfff]
    [    0.000000] On node 0 totalpages: 130972
    [    0.000000]   DMA zone: 64 pages used for memmap
    [    0.000000]   DMA zone: 21 pages reserved
    [    0.000000]   DMA zone: 3998 pages, LIFO batch:0
    [    0.000000]   DMA32 zone: 1984 pages used for memmap
    [    0.000000]   DMA32 zone: 126974 pages, LIFO batch:31
    [    0.000000] ACPI: PM-Timer IO Port: 0xb008
    [    0.000000] ACPI: Local APIC address 0xfee00000
    [    0.000000] ACPI: LAPIC (acpi_id[0x00] lapic_id[0x00] enabled)
    [    0.000000] ACPI: LAPIC_NMI (acpi_id[0xff] dfl dfl lint[0x1])
    [    0.000000] ACPI: IOAPIC (id[0x00] address[0xfec00000] gsi_base[0])
    [    0.000000] IOAPIC[0]: apic_id 0, version 17, address 0xfec00000, GSI 0-23
    [    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
    [    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 5 global_irq 5 high level)
    [    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
    [    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 10 global_irq 10 high level)
    [    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 11 global_irq 11 high level)
    [    0.000000] ACPI: IRQ0 used by override.
    [    0.000000] ACPI: IRQ5 used by override.
    [    0.000000] ACPI: IRQ9 used by override.
    [    0.000000] ACPI: IRQ10 used by override.
    [    0.000000] ACPI: IRQ11 used by override.
    [    0.000000] Using ACPI (MADT) for SMP configuration information
    [    0.000000] ACPI: HPET id: 0x8086a201 base: 0xfed00000
    [    0.000000] smpboot: Allowing 1 CPUs, 0 hotplug CPUs
    [    0.000000] PM: Registered nosave memory: [mem 0x00000000-0x00000fff]
    [    0.000000] PM: Registered nosave memory: [mem 0x0009f000-0x0009ffff]
    [    0.000000] PM: Registered nosave memory: [mem 0x000a0000-0x000effff]
    [    0.000000] PM: Registered nosave memory: [mem 0x000f0000-0x000fffff]
    [    0.000000] e820: [mem 0x20000000-0xfeffbfff] available for PCI devices
    [    0.000000] Booting paravirtualized kernel on KVM
    [    0.000000] setup_percpu: NR_CPUS:256 nr_cpumask_bits:256 nr_cpu_ids:1 nr_node_ids:1
    [    0.000000] PERCPU: Embedded 31 pages/cpu @ffff88001fc00000 s87104 r8192 d31680 u2097152
    [    0.000000] pcpu-alloc: s87104 r8192 d31680 u2097152 alloc=1*2097152
    [    0.000000] pcpu-alloc: [0] 0 
    [    0.000000] KVM setup async PF for cpu 0
    [    0.000000] kvm-stealtime: cpu 0, msr 1fc0e200
    [    0.000000] Built 1 zonelists in Node order, mobility grouping on.  Total pages: 128903
    [    0.000000] Policy zone: DMA32
    [    0.000000] Kernel command line: BOOT_IMAGE=(hd0,gpt2)/EFI/ubuntu/grub/a/vmlinuz root=LABEL=system-a ro init=/lib/systemd/systemd console=ttyS0 console=tty1 panic=-1
    [    0.000000] PID hash table entries: 2048 (order: 2, 16384 bytes)
    [    0.000000] AGP: Checking aperture...
    [    0.000000] AGP: No AGP bridge found
    [    0.000000] Calgary: detecting Calgary via BIOS EBDA area
    [    0.000000] Calgary: Unable to locate Rio Grande table in EBDA - bailing!
    [    0.000000] Memory: 484520K/523888K available (8005K kernel code, 1234K rwdata, 3764K rodata, 1408K init, 1300K bss, 39368K reserved, 0K cma-reserved)
    [    0.000000] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
    [    0.000000] Hierarchical RCU implementation.
    [    0.000000] 	RCU dyntick-idle grace-period acceleration is enabled.
    [    0.000000] 	RCU restricting CPUs from NR_CPUS=256 to nr_cpu_ids=1.
    [    0.000000] RCU: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=1
    [    0.000000] NR_IRQS:16640 nr_irqs:256 16
    [    0.000000] 	Offload RCU callbacks from all CPUs
    [    0.000000] 	Offload RCU callbacks from CPUs: 0.
    [    0.000000] Console: colour VGA+ 80x25
    [    0.000000] console [tty1] enabled
    [    0.000000] console [ttyS0] enabled
    [    0.000000] hpet clockevent registered
    [    0.000000] tsc: Detected 2394.444 MHz processor
    [    0.008000] Calibrating delay loop (skipped) preset value.. 4788.88 BogoMIPS (lpj=9577776)
    [    0.008000] pid_max: default: 32768 minimum: 301
    [    0.008000] ACPI: Core revision 20141107
    [    0.008000] ACPI: All ACPI Tables successfully acquired
    [    0.008000] Security Framework initialized
    [    0.008000] AppArmor: AppArmor initialized
    [    0.008003] Yama: becoming mindful.
    [    0.008409] Dentry cache hash table entries: 65536 (order: 7, 524288 bytes)
    [    0.009059] Inode-cache hash table entries: 32768 (order: 6, 262144 bytes)
    [    0.009663] Mount-cache hash table entries: 1024 (order: 1, 8192 bytes)
    [    0.010222] Mountpoint-cache hash table entries: 1024 (order: 1, 8192 bytes)
    [    0.011010] Initializing cgroup subsys memory
    [    0.011458] Initializing cgroup subsys devices
    [    0.012005] Initializing cgroup subsys freezer
    [    0.012431] Initializing cgroup subsys net_cls
    [    0.012853] Initializing cgroup subsys blkio
    [    0.013260] Initializing cgroup subsys perf_event
    [    0.013699] Initializing cgroup subsys net_prio
    [    0.014125] Initializing cgroup subsys hugetlb
    [    0.014584] mce: CPU supports 10 MCE banks
    [    0.015017] Last level iTLB entries: 4KB 0, 2MB 0, 4MB 0 Last level dTLB entries: 4KB 0, 2MB 0, 4MB 0, 1GB 0
    [    0.023763] Freeing SMP alternatives memory: 32K (ffffffff81e96000 - ffffffff81e9e000)
    [    0.026379] ftrace: allocating 30118 entries in 118 pages
    [    0.032000] Enabling x2apic
    [    0.032000] Enabled x2apic
    [    0.032006] Switched APIC routing to physical x2apic.
    [    0.033465] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
    [    0.033974] smpboot: CPU0: Intel QEMU Virtual CPU version 2.0.0 (fam: 06, model: 06, stepping: 03)
    [    0.040000] APIC calibration not consistent with PM-Timer: 151ms instead of 100ms
    [    0.040000] APIC delta adjusted to PM-Timer: 6250119 (9500006)
    [    0.040000] Performance Events: Broken PMU hardware detected, using software events only.
    [    0.040000] Failed to access perfctr msr (MSR c1 is 0)
    [    0.040000] x86: Booted up 1 node, 1 CPUs
    [    0.040000] smpboot: Total of 1 processors activated (4788.88 BogoMIPS)
    [    0.040000] devtmpfs: initialized
    [    0.040458] evm: security.selinux
    [    0.040800] evm: security.SMACK64
    [    0.041137] evm: security.SMACK64EXEC
    [    0.041496] evm: security.SMACK64TRANSMUTE
    [    0.041890] evm: security.SMACK64MMAP
    [    0.042248] evm: security.ima
    [    0.042565] evm: security.capability
    [    0.042937] NMI watchdog: disabled (cpu0): hardware events not enabled
    [    0.043585] pinctrl core: initialized pinctrl subsystem
    [    0.044098] RTC time: 16:41:14, date: 12/21/15
    [    0.044681] NET: Registered protocol family 16
    [    0.045209] cpuidle: using governor ladder
    [    0.048019] cpuidle: using governor menu
    [    0.048477] ACPI: bus type PCI registered
    [    0.048861] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
    [    0.049481] PCI: Using configuration type 1 for base access
    [    0.050818] ACPI: Added _OSI(Module Device)
    [    0.051216] ACPI: Added _OSI(Processor Device)
    [    0.052001] ACPI: Added _OSI(3.0 _SCP Extensions)
    [    0.052429] ACPI: Added _OSI(Processor Aggregator Device)
    [    0.053937] ACPI: Interpreter enabled
    [    0.054305] ACPI Exception: AE_NOT_FOUND, While evaluating Sleep State [\_S1_] (20141107/hwxface-580)
    [    0.055183] ACPI Exception: AE_NOT_FOUND, While evaluating Sleep State [\_S2_] (20141107/hwxface-580)
    [    0.056282] ACPI: (supports S0 S3 S4 S5)
    [    0.056662] ACPI: Using IOAPIC for interrupt routing
    [    0.057116] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
    [    0.059454] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-ff])
    [    0.060005] acpi PNP0A03:00: _OSC: OS supports [ASPM ClockPM Segments MSI]
    [    0.060560] acpi PNP0A03:00: _OSC failed (AE_NOT_FOUND); disabling ASPM
    [    0.061147] acpi PNP0A03:00: fail to add MMCONFIG information, can't access extended PCI configuration space under this bridge.
    [    0.062300] acpiphp: Slot [3] registered
    [    0.062742] acpiphp: Slot [4] registered
    [    0.063149] acpiphp: Slot [5] registered
    [    0.063539] acpiphp: Slot [6] registered
    [    0.064013] acpiphp: Slot [7] registered
    [    0.064399] acpiphp: Slot [8] registered
    [    0.064784] acpiphp: Slot [9] registered
    [    0.065170] acpiphp: Slot [10] registered
    [    0.065566] acpiphp: Slot [11] registered
    [    0.065956] acpiphp: Slot [12] registered
    [    0.066345] acpiphp: Slot [13] registered
    [    0.066736] acpiphp: Slot [14] registered
    [    0.067152] acpiphp: Slot [15] registered
    [    0.067544] acpiphp: Slot [16] registered
    [    0.067936] acpiphp: Slot [17] registered
    [    0.068012] acpiphp: Slot [18] registered
    [    0.068404] acpiphp: Slot [19] registered
    [    0.069489] acpiphp: Slot [20] registered
    [    0.069881] acpiphp: Slot [21] registered
    [    0.070273] acpiphp: Slot [22] registered
    [    0.070667] acpiphp: Slot [23] registered
    [    0.071058] acpiphp: Slot [24] registered
    [    0.071448] acpiphp: Slot [25] registered
    [    0.072012] acpiphp: Slot [26] registered
    [    0.072402] acpiphp: Slot [27] registered
    [    0.072792] acpiphp: Slot [28] registered
    [    0.073189] acpiphp: Slot [29] registered
    [    0.073583] acpiphp: Slot [30] registered
    [    0.073974] acpiphp: Slot [31] registered
    [    0.074359] PCI host bridge to bus 0000:00
    [    0.074745] pci_bus 0000:00: root bus resource [bus 00-ff]
    [    0.075252] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7]
    [    0.076002] pci_bus 0000:00: root bus resource [io  0x0d00-0xadff]
    [    0.076514] pci_bus 0000:00: root bus resource [io  0xae0f-0xaeff]
    [    0.077029] pci_bus 0000:00: root bus resource [io  0xaf20-0xafdf]
    [    0.080009] pci_bus 0000:00: root bus resource [io  0xafe4-0xffff]
    [    0.080531] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff]
    [    0.081089] pci_bus 0000:00: root bus resource [mem 0x20000000-0xfebfffff]
    [    0.081673] pci 0000:00:00.0: [8086:1237] type 00 class 0x060000
    [    0.081899] pci 0000:00:01.0: [8086:7000] type 00 class 0x060100
    [    0.082161] pci 0000:00:01.1: [8086:7010] type 00 class 0x010180
    [    0.083544] pci 0000:00:01.1: reg 0x20: [io  0xc040-0xc04f]
    [    0.084415] pci 0000:00:01.1: legacy IDE quirk: reg 0x10: [io  0x01f0-0x01f7]
    [    0.084987] pci 0000:00:01.1: legacy IDE quirk: reg 0x14: [io  0x03f6]
    [    0.085534] pci 0000:00:01.1: legacy IDE quirk: reg 0x18: [io  0x0170-0x0177]
    [    0.086122] pci 0000:00:01.1: legacy IDE quirk: reg 0x1c: [io  0x0376]
    [    0.086760] pci 0000:00:01.3: [8086:7113] type 00 class 0x068000
    [    0.086958] pci 0000:00:01.3: quirk: [io  0xb000-0xb03f] claimed by PIIX4 ACPI
    [    0.087635] pci 0000:00:01.3: quirk: [io  0xb100-0xb10f] claimed by PIIX4 SMB
    [    0.088119] pci 0000:00:02.0: [1013:00b8] type 00 class 0x030000
    [    0.088786] pci 0000:00:02.0: reg 0x10: [mem 0xfc000000-0xfdffffff pref]
    [    0.089388] pci 0000:00:02.0: reg 0x14: [mem 0xfebf0000-0xfebf0fff]
    [    0.092594] pci 0000:00:02.0: reg 0x30: [mem 0xfebe0000-0xfebeffff pref]
    [    0.092695] pci 0000:00:03.0: [8086:100e] type 00 class 0x020000
    [    0.093215] pci 0000:00:03.0: reg 0x10: [mem 0xfebc0000-0xfebdffff]
    [    0.093788] pci 0000:00:03.0: reg 0x14: [io  0xc000-0xc03f]
    [    0.096519] pci 0000:00:03.0: reg 0x30: [mem 0xfeb80000-0xfebbffff pref]
    [    0.096918] ACPI: PCI Interrupt Link [LNKA] (IRQs 5 *10 11)
    [    0.097676] ACPI: PCI Interrupt Link [LNKB] (IRQs 5 *10 11)
    [    0.098432] ACPI: PCI Interrupt Link [LNKC] (IRQs 5 10 *11)
    [    0.099180] ACPI: PCI Interrupt Link [LNKD] (IRQs 5 10 *11)
    [    0.099900] ACPI: PCI Interrupt Link [LNKS] (IRQs *9)
    [    0.100433] ACPI: Enabled 16 GPEs in block 00 to 0F
    [    0.101045] vgaarb: setting as boot device: PCI:0000:00:02.0
    [    0.101531] vgaarb: device added: PCI:0000:00:02.0,decodes=io+mem,owns=io+mem,locks=none
    [    0.102257] vgaarb: loaded
    [    0.102560] vgaarb: bridge control possible 0000:00:02.0
    [    0.103163] SCSI subsystem initialized
    [    0.103560] libata version 3.00 loaded.
    [    0.103576] ACPI: bus type USB registered
    [    0.104017] usbcore: registered new interface driver usbfs
    [    0.104494] usbcore: registered new interface driver hub
    [    0.104961] usbcore: registered new device driver usb
    [    0.105489] PCI: Using ACPI for IRQ routing
    [    0.105885] PCI: pci_cache_line_size set to 64 bytes
    [    0.105935] e820: reserve RAM buffer [mem 0x0009fc00-0x0009ffff]
    [    0.105936] e820: reserve RAM buffer [mem 0x1fffe000-0x1fffffff]
    [    0.106018] NetLabel: Initializing
    [    0.106366] NetLabel:  domain hash size = 128
    [    0.106903] NetLabel:  protocols = UNLABELED CIPSOv4
    [    0.107352] NetLabel:  unlabeled traffic allowed by default
    [    0.108057] HPET: 3 timers in total, 0 timers will be used for per-cpu timer
    [    0.108631] hpet0: at MMIO 0xfed00000, IRQs 2, 8, 0
    [    0.109239] hpet0: 3 comparators, 64-bit 100.000000 MHz counter
    [    0.116067] Switched to clocksource kvm-clock
    [    0.119790] AppArmor: AppArmor Filesystem Enabled
    [    0.120293] pnp: PnP ACPI init
    [    0.120677] pnp 00:00: Plug and Play ACPI device, IDs PNP0b00 (active)
    [    0.120711] pnp 00:01: Plug and Play ACPI device, IDs PNP0303 (active)
    [    0.120737] pnp 00:02: Plug and Play ACPI device, IDs PNP0f13 (active)
    [    0.120763] pnp 00:03: [dma 2]
    [    0.120773] pnp 00:03: Plug and Play ACPI device, IDs PNP0700 (active)
    [    0.120814] pnp 00:04: Plug and Play ACPI device, IDs PNP0400 (active)
    [    0.120850] pnp 00:05: Plug and Play ACPI device, IDs PNP0501 (active)
    [    0.120976] pnp: PnP ACPI: found 6 devices
    [    0.126941] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7]
    [    0.126943] pci_bus 0000:00: resource 5 [io  0x0d00-0xadff]
    [    0.126944] pci_bus 0000:00: resource 6 [io  0xae0f-0xaeff]
    [    0.126945] pci_bus 0000:00: resource 7 [io  0xaf20-0xafdf]
    [    0.126946] pci_bus 0000:00: resource 8 [io  0xafe4-0xffff]
    [    0.126947] pci_bus 0000:00: resource 9 [mem 0x000a0000-0x000bffff]
    [    0.126948] pci_bus 0000:00: resource 10 [mem 0x20000000-0xfebfffff]
    [    0.126967] NET: Registered protocol family 2
    [    0.127486] TCP established hash table entries: 4096 (order: 3, 32768 bytes)
    [    0.128067] TCP bind hash table entries: 4096 (order: 4, 65536 bytes)
    [    0.128604] TCP: Hash tables configured (established 4096 bind 4096)
    [    0.129134] TCP: reno registered
    [    0.129477] UDP hash table entries: 256 (order: 1, 8192 bytes)
    [    0.129971] UDP-Lite hash table entries: 256 (order: 1, 8192 bytes)
    [    0.130510] NET: Registered protocol family 1
    [    0.130924] pci 0000:00:00.0: Limiting direct PCI/PCI transfers
    [    0.131431] pci 0000:00:01.0: PIIX3: Enabling Passive Release
    [    0.131928] pci 0000:00:01.0: Activating ISA DMA hang workarounds
    [    0.132465] pci 0000:00:02.0: Video device with shadowed ROM
    [    0.132474] PCI: CLS 0 bytes, default 64
    [    0.132516] Trying to unpack rootfs image as initramfs...
    [    1.985588] Freeing initrd memory: 14396K (ffff88001e95c000 - ffff88001f76b000)
    [    1.986541] microcode: CPU0 sig=0x663, pf=0x1, revision=0x1
    [    1.987055] microcode: Microcode Update Driver: v2.00 <tigran@aivazian.fsnet.co.uk>, Peter Oruba
    [    1.987841] Scanning for low memory corruption every 60 seconds
    [    1.988482] futex hash table entries: 256 (order: 2, 16384 bytes)
    [    1.988999] Initialise system trusted keyring
    [    1.989442] audit: initializing netlink subsys (disabled)
    [    1.989916] audit: type=2000 audit(1450716077.406:1): initialized
    [    1.990616] HugeTLB registered 2 MB page size, pre-allocated 0 pages
    [    1.992114] zpool: loaded
    [    1.992415] zbud: loaded
    [    1.992806] VFS: Disk quotas dquot_6.5.2
    [    1.993211] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
    [    1.994059] fuse init (API version 7.23)
    [    1.994542] Key type big_key registered
    [    1.995053] Key type asymmetric registered
    [    1.995445] Asymmetric key parser 'x509' registered
    [    1.995906] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 252)
    [    2.051360] io scheduler noop registered
    [    2.051749] io scheduler deadline registered (default)
    [    2.052248] io scheduler cfq registered
    [    2.052812] pci_hotplug: PCI Hot Plug PCI Core version: 0.5
    [    2.053311] pciehp: PCI Express Hot Plug Controller Driver version: 0.4
    [    2.053869] intel_idle: does not run on family 6 model 6
    [    2.053919] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input0
    [    2.054604] ACPI: Power Button [PWRF]
    [    2.055047] GHES: HEST is not enabled!
    [    2.055483] Serial: 8250/16550 driver, 32 ports, IRQ sharing enabled
    [    2.079743] 00:05: ttyS0 at I/O 0x3f8 (irq = 4, base_baud = 115200) is a 16550A
    [    2.136969] Linux agpgart interface v0.103
    [    2.138185] brd: module loaded
    [    2.138995] loop: module loaded
[    2.139442] ata_piix 0000:00:01.1: version 2.13
[    2.140132] scsi host0: ata_piix
[    2.140556] scsi host1: ata_piix
[    2.140915] ata1: PATA max MWDMA2 cmd 0x1f0 ctl 0x3f6 bmdma 0xc040 irq 14
[    2.141470] ata2: PATA max MWDMA2 cmd 0x170 ctl 0x376 bmdma 0xc048 irq 15
[    2.142209] libphy: Fixed MDIO Bus: probed
[    2.142598] tun: Universal TUN/TAP device driver, 1.6
[    2.143038] tun: (C) 1999-2004 Max Krasnyansky <maxk@qualcomm.com>
[    2.143578] PPP generic driver version 2.4.2
[    2.144050] ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
[    2.144589] ehci-pci: EHCI PCI platform driver
[    2.145001] ehci-platform: EHCI generic platform driver
[    2.145464] ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
[    2.145976] ohci-pci: OHCI PCI platform driver
[    2.146387] ohci-platform: OHCI generic platform driver
[    2.146845] uhci_hcd: USB Universal Host Controller Interface driver
[    2.147402] i8042: PNP: PS/2 Controller [PNP0303:KBD,PNP0f13:MOU] at 0x60,0x64 irq 1,12
[    2.148686] serio: i8042 KBD port at 0x60,0x64 irq 1
[    2.149124] serio: i8042 AUX port at 0x60,0x64 irq 12
[    2.149639] mousedev: PS/2 mouse device common for all mice
[    2.150278] input: AT Translated Set 2 keyboard as /devices/platform/i8042/serio0/input/input1
[    2.151214] rtc_cmos 00:00: RTC can wake from S4
[    2.151762] rtc_cmos 00:00: rtc core: registered rtc_cmos as rtc0
[    2.152442] rtc_cmos 00:00: alarms up to one day, 114 bytes nvram, hpet irqs
[    2.153084] i2c /dev entries driver
[    2.153481] device-mapper: uevent: version 1.0.3
[    2.153944] device-mapper: ioctl: 4.29.0-ioctl (2014-10-28) initialised: dm-devel@redhat.com
[    2.154712] ledtrig-cpu: registered to indicate activity on CPUs
[    2.155255] PCCT header not found.
[    2.155603] ACPI PCC probe failed.
[    2.156017] TCP: cubic registered
[    2.156426] NET: Registered protocol family 10
[    2.156936] NET: Registered protocol family 17
[    2.157361] Key type dns_resolver registered
[    2.157897] Loading compiled-in X.509 certificates
[    2.158881] Loaded X.509 cert 'Magrathea: Glacier signing key: a2adc229c86b53bfcc9f2e784bf426b55fae91b2'
[    2.159703] registered taskstats version 1
[    2.161165] Key type trusted registered
[    2.163094] Key type encrypted registered
[    2.163489] AppArmor: AppArmor sha1 policy hashing enabled
[    2.163960] ima: No TPM chip found, activating TPM-bypass!
[    2.164462] evm: HMAC attrs: 0x1
[    2.164892]   Magic number: 11:445:692
[    2.219822] hpet1: lost 3 rtc interrupts
[    2.220360] rtc_cmos 00:00: setting system clock to 2015-12-21 16:41:17 UTC (1450716077)
[    2.221286] BIOS EDD facility v0.16 2004-Jun-25, 0 devices found
[    2.221828] EDD information not available.
[    2.222307] PM: Hibernation image not present or could not be loaded.
[    2.304553] ata2.01: NODEV after polling detection
[    2.304727] ata2.00: ATAPI: QEMU DVD-ROM, 2.0.0, max UDMA/100
[    2.305594] ata2.00: configured for MWDMA2
[    2.306185] ata1.01: NODEV after polling detection
[    2.306360] ata1.00: ATA-7: QEMU HARDDISK, 2.0.0, max UDMA/100
[    2.306904] ata1.00: 7617187 sectors, multi 16: LBA48 
[    2.307629] ata1.00: configured for MWDMA2
[    2.308078] scsi 0:0:0:0: Direct-Access     ATA      QEMU HARDDISK    0    PQ: 0 ANSI: 5
[    2.308940] sd 0:0:0:0: [sda] 7617187 512-byte logical blocks: (3.89 GB/3.63 GiB)
[    2.309662] sd 0:0:0:0: [sda] Write Protect is off
[    2.310094] sd 0:0:0:0: [sda] Mode Sense: 00 3a 00 00
[    2.310103] sd 0:0:0:0: Attached scsi generic sg0 type 0
[    2.310617] sd 0:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    2.311589] scsi 1:0:0:0: CD-ROM            QEMU     QEMU DVD-ROM     2.0. PQ: 0 ANSI: 5
[    2.320669] sr 1:0:0:0: [sr0] scsi3-mmc drive: 4x/4x cd/rw xa/form2 tray
[    2.321386] cdrom: Uniform CD-ROM driver Revision: 3.20
[    2.322178] sr 1:0:0:0: Attached scsi CD-ROM sr0
[    2.322676] sr 1:0:0:0: Attached scsi generic sg1 type 5
[    2.326741]  sda: sda1 sda2 sda3 sda4 sda5
[    2.327316] sd 0:0:0:0: [sda] Attached SCSI disk
[    2.327919] Freeing unused kernel memory: 1408K (ffffffff81d36000 - ffffffff81e96000)
[    2.328688] Write protecting the kernel read-only data: 12288k
[    2.329303] Freeing unused kernel memory: 176K (ffff8800017d4000 - ffff880001800000)
[    2.330831] Freeing unused kernel memory: 332K (ffff880001bad000 - ffff880001c00000)
[    2.392726] random: systemd-udevd urandom read with 12 bits of entropy available
[    2.410673] e1000: Intel(R) PRO/1000 Network Driver - version 7.3.21-k8-NAPI
[    2.411253] e1000: Copyright (c) 1999-2006 Intel Corporation.
[    2.411919] ACPI: PCI Interrupt Link [LNKC] enabled at IRQ 11
[    2.795739] e1000 0000:00:03.0 eth0: (PCI:33MHz:32-bit) 52:54:00:12:34:56
[    2.796330] e1000 0000:00:03.0 eth0: Intel(R) PRO/1000 Network Connection
[    2.797572] initrd: mounting /dev/sda3
[    2.798430] EXT4-fs (sda3): couldn't mount as ext3 due to feature incompatibilities
[    2.799376] EXT4-fs (sda3): couldn't mount as ext2 due to feature incompatibilities
[    2.856812] EXT4-fs (sda3): mounted filesystem with ordered data mode. Opts: (null)
[    2.858069] initrd: mounting /run
[    2.861495] initrd: checking filesystem for writable partition
[    2.862756] EXT4-fs (sda5): couldn't mount as ext3 due to feature incompatibilities
[    2.863705] EXT4-fs (sda5): couldn't mount as ext2 due to feature incompatibilities
[    2.865793] EXT4-fs (sda5): mounted filesystem with ordered data mode. Opts: errors=remount-ro
[    3.048084] tsc: Refined TSC clocksource calibration: 2394.441 MHz
[    3.793263] input: ImExPS/2 Generic Explorer Mouse as /devices/platform/i8042/serio1/input/input3
[    4.524515] initrd: mounting writable partition
[    4.528619] EXT4-fs: Warning: mounting with data=journal disables delayed allocation and O_DIRECT support!
[    4.529573] EXT4-fs (sda5): couldn't mount as ext3 due to feature incompatibilities
[    4.530782] EXT4-fs (sda5): Mount option "data=journal" incompatible with ext2
[    4.588042] EXT4-fs (sda5): mounted filesystem with journalled data mode. Opts: data=journal
[    5.458343] systemd[1]: Inserted module 'autofs4'
[    5.461699] systemd[1]: systemd 219 running in system mode. (+PAM +AUDIT +SELINUX +IMA +APPARMOR +SMACK +SYSVINIT +UTMP +LIBCRYPTSETUP +GCRYPT -GNUTLS +ACL +XZ -LZ4 -SECCOMP +BLKID -ELFUTILS +KMOD -IDN)
[    5.463177] systemd[1]: Detected virtualization kvm.
[    5.463631] systemd[1]: Detected architecture x86-64.
[    5.464894] systemd[1]: Set hostname to <localhost.localdomain>.
[    5.465605] systemd[1]: Initializing machine ID from random generator.
[    5.466300] systemd[1]: Installed transient /etc/machine-id file.
[    5.568129] systemd[1]: Unit etc-ppp.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.569178] systemd[1]: Unit etc-ssh.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.570038] systemd[1]: Unit etc-apparmor.d-cache.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.570937] systemd[1]: Unit etc-writable.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.571791] systemd[1]: Unit etc-hosts.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.572659] systemd[1]: Unit etc-network-interfaces.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.573561] systemd[1]: Unit etc-sysctl.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.574422] systemd[1]: Unit etc-modules\x2dload.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.575299] systemd[1]: Unit etc-dbus\x2d1-system.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.576196] systemd[1]: Unit etc-udev-rules.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.577046] systemd[1]: Unit etc-sudoers.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.577891] systemd[1]: Unit etc-ufw.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.578710] systemd[1]: Unit etc-modprobe.d.mount is bound to inactive unit dev-sda5.device. Stopping, too.
[    5.579728] systemd[1]: Mounted /etc/cloud/cloud.cfg.d.
[    5.580239] systemd[1]: Mounted /etc/systemd/system.
[    5.580691] systemd[1]: Mounted /writable.
[    5.645551] systemd[1]: Cannot add dependency job for unit sshd-keygen.service, ignoring: Unit sshd-keygen.service failed to load: No such file or directory.
[    5.646721] systemd[1]: Cannot add dependency job for unit display-manager.service, ignoring: Unit display-manager.service failed to load: No such file or directory.
[    5.649126] systemd[1]: Set up automount Arbitrary Executable File Formats File System Automount Point.
[    5.649981] systemd[1]: Starting Arbitrary Executable File Formats File System Automount Point.
[    5.650831] systemd[1]: Started Dispatch Password Requests to Console Directory Watch.
[    5.651550] systemd[1]: Starting Dispatch Password Requests to Console Directory Watch.
[    5.652751] systemd[1]: Reached target Swap.
[    5.653235] systemd[1]: Starting Swap.
[    5.654026] systemd[1]: Reached target Remote File Systems (Pre).
[    5.654576] systemd[1]: Starting Remote File Systems (Pre).
[    5.655078] systemd[1]: Started Forward Password Requests to Wall Directory Watch.
[    5.655778] systemd[1]: Starting Forward Password Requests to Wall Directory Watch.
[    5.656892] systemd[1]: Reached target Paths.
[    5.657325] systemd[1]: Starting Paths.
[    5.658106] systemd[1]: Reached target Encrypted Volumes.
[    5.658575] systemd[1]: Starting Encrypted Volumes.
[    5.659423] systemd[1]: Created slice Root Slice.
[    5.659853] systemd[1]: Starting Root Slice.
[    5.660721] systemd[1]: Listening on Delayed Shutdown Socket.
[    5.661224] systemd[1]: Starting Delayed Shutdown Socket.
[    5.662113] systemd[1]: Listening on Journal Socket.
[    5.662567] systemd[1]: Starting Journal Socket.
[    5.663451] systemd[1]: Listening on Journal Audit Socket.
[    5.663933] systemd[1]: Starting Journal Audit Socket.
[    5.664825] systemd[1]: Listening on Journal Socket (/dev/log).
[    5.719861] systemd[1]: Starting Journal Socket (/dev/log).
[    5.721056] systemd[1]: Listening on udev Kernel Socket.
[    5.721588] systemd[1]: Starting udev Kernel Socket.
[    5.722520] systemd[1]: Listening on fsck to fsckd communication Socket.
[    5.723073] systemd[1]: Starting fsck to fsckd communication Socket.
[    5.724080] systemd[1]: Listening on /dev/initctl Compatibility Named Pipe.
[    5.724650] systemd[1]: Starting /dev/initctl Compatibility Named Pipe.
[    5.725613] systemd[1]: Listening on udev Control Socket.
[    5.726108] systemd[1]: Starting udev Control Socket.
[    5.727038] systemd[1]: Created slice User and Session Slice.
[    5.727533] systemd[1]: Starting User and Session Slice.
[    5.728461] systemd[1]: Created slice System Slice.
[    5.728930] systemd[1]: Starting System Slice.
[    5.729996] systemd[1]: Starting Load Kernel Modules...
[    5.731173] systemd[1]: Started Set Up Additional Binary Formats.
[    5.731988] systemd[1]: Starting Set the hostname to the value stored on the writable partition...
[    5.735144] systemd[1]: Created slice system-getty.slice.
[    5.735681] systemd[1]: Starting system-getty.slice.
[    5.736488] systemd[1]: Starting Nameserver information manager...
[    5.741998] systemd[1]: Mounting Debug File System...
[    5.747381] systemd[1]: Starting Create list of required static device nodes for the current kernel...
[    5.806446] systemd[1]: Created slice system-serial\x2dgetty.slice.
[    5.806982] systemd[1]: Starting system-serial\x2dgetty.slice.
[    5.807732] systemd[1]: Starting Remount Root and Kernel File Systems...
[    5.810971] EXT4-fs (sda3): re-mounted. Opts: (null)
[    5.811933] systemd[1]: Reached target Slices.
[    5.812404] systemd[1]: Starting Slices.
[    5.813633] systemd[1]: Created slice system-systemd\x2dfsck.slice.
[    5.814173] systemd[1]: Starting system-systemd\x2dfsck.slice.
[    5.815762] systemd[1]: Starting udev Coldplug all Devices...
[    5.816938] systemd[1]: Mounting Huge Pages File System...
[    5.822352] systemd[1]: Mounting POSIX Message Queue File System...
[    5.825453] systemd[1]: Starting Increase datagram queue length...
[    5.831273] systemd[1]: Mounted Debug File System.
[    5.832344] systemd[1]: Mounted Huge Pages File System.
[    5.833264] systemd[1]: Mounted POSIX Message Queue File System.
[    5.889049] random: nonblocking pool is initialized
[    5.890623] systemd[1]: Started Load Kernel Modules.
[    5.892105] systemd[1]: Started Set the hostname to the value stored on the writable partition.
[    5.893802] systemd[1]: Started Create list of required static device nodes for the current kernel.
[    5.895890] systemd[1]: Started Remount Root and Kernel File Systems.
[    5.897925] systemd[1]: Started Increase datagram queue length.
    [    5.903397] systemd[1]: Started Nameserver information manager.
    [    5.910159] systemd[1]: Started udev Coldplug all Devices.
    [    5.976873] systemd[1]: Listening on Syslog Socket.
    [    5.977480] systemd[1]: Starting Syslog Socket.
    [    5.978273] systemd[1]: Starting Journal Service...
    [    5.980789] systemd[1]: Started Rebuild Hardware Database.
    [    5.983237] systemd[1]: Started Various fixups to make systemd work better on Debian.
    [    5.987454] systemd[1]: Starting Create Static Device Nodes in /dev...
    [    5.993065] systemd[1]: Mounting FUSE Control File System...
    [    6.001098] systemd[1]: Starting Apply Kernel Variables...
    [    6.059037] systemd[1]: Mounted Configuration File System.
    [    6.060470] systemd[1]: Mounted FUSE Control File System.
    [    6.061237] systemd[1]: Started Journal Service.
    [    6.330076] parport_pc 00:04: reported by Plug and Play ACPI
    [    6.330141] parport0: PC-style at 0x378, irq 7 [PCSPP,TRISTATE]
    [    6.347202] piix4_smbus 0000:00:01.3: SMBus Host Controller at 0xb100, revision 0
    [    6.449185] [drm] Initialized drm 1.1.0 20060810
    [    6.534749] systemd-journald[523]: Received request to flush runtime journal from PID 1
    [    6.634047] [TTM] Zone  kernel: Available graphics memory: 250432 kiB
    [    6.634048] [TTM] Initializing pool allocator
    [    6.634050] [TTM] Initializing DMA pool allocator
    [    6.634227] [drm] fb mappable at 0xFC000000
    [    6.634228] [drm] vram aper at 0xFC000000
    [    6.634228] [drm] size 33554432
    [    6.634228] [drm] fb depth is 24
    [    6.634228] [drm]    pitch is 3072
    [    6.636768] fbcon: cirrusdrmfb (fb0) is primary device
    [    6.702100] Console: switching to colour frame buffer device 128x48
    [    6.702831] ppdev: user-space parallel port driver
    [    6.710411] cirrus 0000:00:02.0: fb0: cirrusdrmfb frame buffer device
    [    6.710412] cirrus 0000:00:02.0: registered panic notifier
    [    6.719234] [drm] Initialized cirrus 1.0.0 20110418 for 0000:00:02.0 on minor 0
    [    6.808081] EXT4-fs (sda4): mounted filesystem with ordered data mode. Opts: (null)
    [    7.161510] audit: type=1400 audit(1450716082.436:2): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/sbin/dhclient" pid=651 comm="apparmor_parser"
    [    7.161758] audit: type=1400 audit(1450716082.436:3): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/lib/NetworkManager/nm-dhcp-client.action" pid=651 comm="apparmor_parser"
    [    7.161942] audit: type=1400 audit(1450716082.436:4): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/lib/NetworkManager/nm-dhcp-helper" pid=651 comm="apparmor_parser"
    [    7.162115] audit: type=1400 audit(1450716082.436:5): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/lib/connman/scripts/dhclient-script" pid=651 comm="apparmor_parser"
    [    7.175351] audit: type=1400 audit(1450716082.448:6): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/bin/ubuntu-core-launcher" pid=653 comm="apparmor_parser"
    [    7.763589] audit: type=1400 audit(1450716083.036:7): apparmor="STATUS" operation="profile_load" profile="unconfined" name="webdm_snappyd_0.9.4" pid=768 comm="apparmor_parser"
    [    8.166709] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
    [   10.216446] e1000: eth0 NIC Link is Up 1000 Mbps Full Duplex, Flow Control: RX
    [   10.216809] IPv6: ADDRCONF(NETDEV_CHANGE): eth0: link becomes ready

