# Ohai WinServer2016 vs Ubuntu18.04

----------------------------------------------------------------------------------------------------------------------------------------
# Ubuntu 18.04                                                        
<pre>
{                                                                        
  "virtualization": { ...                                                   
  },
  "kernel": { ...
  },
  "os": "linux",
  "os_version": "4.15.0-58-generic",
  "lsb": { ...
  },
  "platform": "ubuntu",
  "platform_version": "18.04",
  "platform_family": "debian",
  "filesystem": { ...
  },
  "cpu": { ...
  },
  "uptime_seconds": 356,
  "uptime": "5 minutes 56 seconds",
  "idletime_seconds": 323,
  "idletime": "5 minutes 23 seconds",
  "network": { ...
  },
  "counters": { ...
  },
  "ipaddress": "10.0.2.15",
  "macaddress": "08:00:27:BB:14:75",
  "ip6address": "fe80::a00:27ff:febb:1475",
  "memory": { ...
  },
  "languages": { ...
  },
  "hostname": "vagrant",
  "machinename": "vagrant",
  "fqdn": "vagrant.vm",
  "domain": "vm",
  "dmi": { ...
  },
  "machine_id": "01dabba83638430eb6f2bd0c796673fd",
  "etc": { ...
  },
  "current_user": "vagrant",
  "shells": [ ...
  ],
  "init_package": "systemd",
  "keys": { ...
  },
  "chef_packages": { ...
  },
  "sessions": { ...
  },
  "filesystem2": { ...
  },
  "hostnamectl": { ...
  },
  "block_device": { ...
  },
  "fips": { ...
  },
  "command": { ...
  },
  "time": { ...
  },
  "ohai_time": 1576671777.678002,
  "packages": { ...
  },
  "root_group": "root",
  "cloud_v2": null
}

</pre>
----------------------------------------------------------------------------------------------------------------------------------------

# Windows Server 2016

<pre>
{
  "kernel": { ...
  },
  "memory": { ...
  },
  "network": { ...
  },
  "counters": { ...
  },
  "ipaddress": "10.0.2.15",
  "macaddress": "08:00:27:5C:29:1E",
  "ip6address": "fe80::9b0:3012:24e7:7067",
  "os": "windows",
  "os_version": "10.0.14393",
  "platform": "windows",
  "platform_version": "10.0.14393",
  "platform_family": "windows",
  "uptime_seconds": 1280,
  "uptime": "21 minutes 20 seconds",
  "dmi": {

  },
  "virtualization": { ...
  },
  "languages": { ...
  },
  "chef_packages": { ...
  },
  "cloud": null,
  "command": {

  },
  "cpu": { ...
  },
  "filesystem": { ...
  },
  "hostname": "vagrant-2016",
  "machinename": "VAGRANT-2016",
  "fqdn": "vagrant-2016.cloudeon.com",
  "domain": "cloudeon.com",
  "keys": { ...
  },
  "fips": { ...
  },
  "ohai_time": 1578409894.56682,
  "packages": { ...
  },
  "root_group": "Administrators",
  "shard_seed": 72579257,
  "time": { ...
  },
  "virtualbox": { ...
  },
  "system_enclosure": { ...
  }
}
</pre>

----------------------------------------------------------------------------------------------------------------------------------------
 # Kernel
 
 ## Ubuntu
 <pre>

  "kernel": {
    "name": "Linux",
    "release": "4.15.0-58-generic",                                 
    "version": "#64-Ubuntu SMP Tue Aug 6 11:12:41 UTC 2019", 
    "machine": "x86_64",
    "processor": "x86_64",
    "os": "GNU/Linux",
    "modules": {  ... 
    }
  }

 </pre>
 
 
 
 ## Windows
 
 <pre>
  "kernel": {
    "os_info": {
      "boot_device": "\\Device\\HarddiskVolume1",
      "build_number": "14393",
      "build_type": "Multiprocessor Free",
      "caption": "Microsoft Windows Server 2016 Standard Evaluation",
      "code_set": "1252",
      "country_code": "1",
      "csd_version": null,
      "cs_name": "VAGRANT-2016",
      "current_time_zone": 0,
      "data_execution_prevention_32_bit_applications": true,
      "data_execution_prevention_available": true,
      "data_execution_prevention_drivers": true,
      "data_execution_prevention_support_policy": 3,
      "debug": false,
      "description": "",
      "distributed": false,
      "encryption_level": 256,
      "foreground_application_boost": 2,
      "install_date": "20191219103424.000000+000",
      "large_system_cache": null,
      "last_boot_up_time": "20200107145010.499557+000",
      "local_date_time": "20200107151130.322000+000",
      "locale": "0409",
      "manufacturer": "Microsoft Corporation",
      "max_number_of_processes": -1,
      "max_process_memory_size": "137438953344",
      "mui_languages": [
        "en-US"
      ],
      "name": "Microsoft Windows Server 2016 Standard Evaluation|C:\\Windows|\\Device\\Harddisk0\\Partition2",
      "number_of_licensed_users": 0,
      "number_of_processes": 51,
      "number_of_users": 1,
      "operating_system_sku": 79,
      "organization": "Hashicorp",
      "os_architecture": "64-bit",
      "os_language": 1033,
      "os_product_suite": 272,
      "os_type": 18,
      "other_type_description": null,
      "pae_enabled": null,
      "plus_product_id": null,
      "plus_version_number": null,
      "portable_operating_system": false,
      "primary": true,
      "product_type": 3,
      "registered_user": "",
      "serial_number": "00378-00000-00000-AA739",
      "service_pack_major_version": 0,
      "service_pack_minor_version": 0,
      "size_stored_in_paging_files": "1179648",
      "status": "OK",
      "suite_mask": 272,
      "system_device": "\\Device\\HarddiskVolume2",
      "system_directory": "C:\\Windows\\system32",
      "system_drive": "C:",
      "total_visible_memory_size": "2096692",
      "version": "10.0.14393",
      "windows_directory": "C:\\Windows"
    },
    "name": "Microsoft Windows Server 2016 Standard Evaluation",
    "release": "10.0.14393",
    "version": "10.0.14393  Build 14393",
    "os": "WINNT",
    "product_type": "Server",
    "server_core": false,
    "cs_info": {
      "admin_password_status": 3,
      "automatic_managed_pagefile": true,
      "automatic_reset_boot_option": true,
      "automatic_reset_capability": true,
      "boot_option_on_limit": null,
      "boot_option_on_watch_dog": null,
      "boot_rom_supported": true,
      "boot_status": null,
      "bootup_state": "Normal boot",
      "caption": "VAGRANT-2016",
      "chassis_bootup_state": 3,
      "chassis_sku_number": null,
      "current_time_zone": 0,
      "daylight_in_effect": null,
      "description": "AT/AT COMPATIBLE",
      "dns_host_name": "vagrant-2016",
      "domain": "WORKGROUP",
      "domain_role": 2,
      "enable_daylight_savings_time": true,
      "front_panel_reset_status": 3,
      "hypervisor_present": true,
      "infrared_supported": false,
      "initial_load_info": null,
      "install_date": null,
      "keyboard_password_status": 3,
      "last_load_info": null,
      "manufacturer": "innotek GmbH",
      "model": "VirtualBox",
      "name": "VAGRANT-2016",
      "name_format": null,
      "network_server_mode_enabled": true,
      "number_of_logical_processors": 1,
      "number_of_processors": 1,
      "oem_string_array": [
        "vboxVer_6.0.14",
        "vboxRev_133895"
      ],
      "part_of_domain": false,
      "pause_after_reset": "-1",
      "pc_system_type": 2,
      "pc_system_type_ex": 2,
      "power_management_capabilities": null,
      "power_management_supported": null,
      "power_on_password_status": 3,
      "power_state": 0,
      "power_supply_state": 3,
      "primary_owner_contact": null,
      "primary_owner_name": "",
      "reset_capability": 1,
      "reset_count": -1,
      "reset_limit": -1,
      "roles": [
        "LM_Workstation",
        "LM_Server",
        "NT",
        "Server_NT"
      ],
      "status": "OK",
      "support_contact_description": null,
      "system_family": "Virtual Machine",
      "system_sku_number": null,
      "system_startup_delay": null,
      "system_startup_options": null,
      "system_startup_setting": null,
      "system_type": "x64-based PC",
      "thermal_state": 3,
      "total_physical_memory": "2147012608",
      "user_name": "VAGRANT-2016\\vagrant",
      "wake_up_type": 6,
      "workgroup": "WORKGROUP"
    },
    "machine": "x86_64",
    "system_type": "Mobile"
  },
 
 </pre>
----------------------------------------------------------------------------------------------------------------------------------------

# Memory



## Ubuntu 
<pre>
"memory": {
    "swap": {
      "cached": "0kB",
      "total": "1003516kB",
      "free": "1003516kB"
    },
    "hugepages": {
      "total": "0",
      "free": "0",
      "reserved": "0",
      "surplus": "0"
    },
    "total": "1009112kB",
    "free": "333184kB",
    "buffers": "25080kB",
    "cached": "527504kB",
    "active": "451944kB",
    "inactive": "142436kB",
    "dirty": "112kB",
    "writeback": "0kB",
    "anon_pages": "41784kB",
    "mapped": "40440kB",
    "slab": "58648kB",
    "slab_reclaimable": "36564kB",
    "slab_unreclaim": "22084kB",
    "page_tables": "3456kB",
    "nfs_unstable": "0kB",
    "bounce": "0kB",
    "commit_limit": "1508072kB",
    "committed_as": "236960kB",
    "vmalloc_total": "34359738367kB",
    "vmalloc_used": "0kB",
    "vmalloc_chunk": "0kB",
    "hugepage_size": "2048kB"
  },
  </pre>
  
## Windows 
<pre>
"memory": {
    "swap": {
      "total": "1179648kB",
      "free": "1027656kB"
    },
    "total": "2096692kB",
    "free": "980948kB"
  },
</pre>

----------------------------------------------------------------------------------------------------------------------------------------

# CPU


## Ubuntu
<pre>
"cpu": {
    "0": {
      "vendor_id": "GenuineIntel",
      "family": "6",
      "model": "142",
      "model_name": "Intel(R) Core(TM) i7-8650U CPU @ 1.90GHz",
      "stepping": "10",
      "mhz": "2112.000",
      "cache_size": "8192 KB",
      "physical_id": "0",
      "core_id": "0",
      "cores": "1",
      "flags": [
        "fpu",
        "vme",
        "de",
        "pse",
        "tsc",
        "msr",
        "pae",
        "mce",
        "cx8",
        "apic",
        "sep",
        "mtrr",
        "pge",
        "mca",
        "cmov",
        "pat",
        "pse36",
        "clflush",
        "mmx",
        "fxsr",
        "sse",
        "sse2",
        "ht",
        "syscall",
        "nx",
        "rdtscp",
        "lm",
        "constant_tsc",
        "rep_good",
        "nopl",
        "xtopology",
        "nonstop_tsc",
        "cpuid",
        "tsc_known_freq",
        "pni",
        "pclmulqdq",
        "monitor",
        "ssse3",
        "cx16",
        "pcid",
        "sse4_1",
        "sse4_2",
        "x2apic",
        "movbe",
        "popcnt",
        "aes",
        "xsave",
        "avx",
        "rdrand",
        "hypervisor",
        "lahf_lm",
        "abm",
        "3dnowprefetch",
        "invpcid_single",
        "pti",
        "fsgsbase",
        "avx2",
        "invpcid",
        "rdseed",
        "clflushopt",
        "md_clear",
        "flush_l1d"
      ]
    },
    "total": 1,
    "real": 1,
    "cores": 1
  },
</pre>


## Windows 
<pre>
"cpu": {
    "0": {
      "cores": 1,
      "vendor_id": "GenuineIntel",
      "family": "2",
      "model": "",
      "stepping": "10",
      "physical_id": "CPU0",
      "model_name": "Intel(R) Core(TM) i7-8650U CPU @ 1.90GHz",
      "description": "Intel64 Family 6 Model 142 Stepping 10",
      "mhz": "2112",
      "cache_size": " KB"
    },
    "total": 1,
    "cores": 1,
    "real": 1
  },

</pre>

----------------------------------------------------------------------------------------------------------------------------------------

# Network


## Ubuntu 

<pre>
"network": {
    "interfaces": {
      "lo": {
        "mtu": "65536",
        "flags": [
          "LOOPBACK",
          "UP",
          "LOWER_UP"
        ],
        "encapsulation": "Loopback",
        "addresses": {
          "127.0.0.1": {
            "family": "inet",
            "prefixlen": "8",
            "netmask": "255.0.0.0",
            "scope": "Node"
          },
          "::1": {
            "family": "inet6",
            "prefixlen": "128",
            "scope": "Node",
            "tags": [

            ]
          }
        },
        "state": "unknown"
      },
      "eth0": {
        "type": "eth",
        "number": "0",
        "mtu": "1500",
        "flags": [
          "BROADCAST",
          "MULTICAST",
          "UP",
          "LOWER_UP"
        ],
        "encapsulation": "Ethernet",
        "addresses": {
          "08:00:27:BB:14:75": {
            "family": "lladdr"
          },
          "10.0.2.15": {
            "family": "inet",
            "prefixlen": "24",
            "netmask": "255.255.255.0",
            "broadcast": "10.0.2.255",
            "scope": "Global"
          },
          "fe80::a00:27ff:febb:1475": {
            "family": "inet6",
            "prefixlen": "64",
            "scope": "Link",
            "tags": [

            ]
          }
        },
        "state": "up",
        "arp": {
          "10.0.2.2": "52:54:00:12:35:02",
          "10.0.2.3": "52:54:00:12:35:03"
        },
        "routes": [
          {
            "destination": "default",
            "family": "inet",
            "via": "10.0.2.2",
            "metric": "100",
            "proto": "dhcp",
            "src": "10.0.2.15"
          },
          {
            "destination": "10.0.2.0/24",
            "family": "inet",
            "scope": "link",
            "proto": "kernel",
            "src": "10.0.2.15"
          },
          {
            "destination": "10.0.2.2",
            "family": "inet",
            "scope": "link",
            "metric": "100",
            "proto": "dhcp",
            "src": "10.0.2.15"
          },
          {
            "destination": "fe80::/64",
            "family": "inet6",
            "metric": "256",
            "proto": "kernel"
          }
        ],
        "link_speed": 1000,
        "duplex": "Full",
        "port": "Twisted Pair",
        "transceiver": "internal",
        "auto_negotiation": "on",
        "mdi_x": "off (auto)",
        "ring_params": {
          "max_rx": 4096,
          "max_rx_mini": 0,
          "max_rx_jumbo": 0,
          "max_tx": 4096,
          "current_rx": 256,
          "current_rx_mini": 0,
          "current_rx_jumbo": 0,
          "current_tx": 256
        }
      }
    },
    "default_interface": "eth0",
    "default_gateway": "10.0.2.2"
  },
</pre>





##  Windows 
<pre>
    "network": {
    "interfaces": {
      "0x2": {
        "configuration": {
          "ip_address": [
            "10.0.2.15",
            "fe80::9b0:3012:24e7:7067"
          ],
          "arp_always_source_route": null,
          "arp_use_ether_snap": null,
          "caption": "[00000001] Intel(R) PRO/1000 MT Desktop Adapter",
          "database_path": "%SystemRoot%\\System32\\drivers\\etc",
          "dead_gw_detect_enabled": null,
          "default_ip_gateway": [
            "10.0.2.2"
          ],
          "default_tos": null,
          "default_ttl": null,
          "description": "Intel(R) PRO/1000 MT Desktop Adapter",
          "dhcp_enabled": true,
          "dhcp_lease_expires": "20200108145016.000000+000",
          "dhcp_lease_obtained": "20200107145016.000000+000",
          "dhcp_server": "10.0.2.2",
          "dns_domain": "cloudeon.com",
          "dns_domain_suffix_search_order": [
            "cloudeon.com"
          ],
          "dns_enabled_for_wins_resolution": false,
          "dns_host_name": "vagrant-2016",
          "dns_server_search_order": [
            "10.0.2.3"
          ],
          "domain_dns_registration_enabled": false,
          "forward_buffer_memory": null,
          "full_dns_registration_enabled": true,
          "gateway_cost_metric": [
            0
          ],
          "igmp_level": null,
          "index": 1,
          "interface_index": 2,
          "ip_connection_metric": 25,
          "ip_enabled": true,
          "ip_filter_security_enabled": false,
          "ip_port_security_enabled": null,
          "ip_sec_permit_ip_protocols": [

          ],
          "ip_sec_permit_tcp_ports": [

          ],
          "ip_sec_permit_udp_ports": [

          ],
          "ip_subnet": [
            "255.255.255.0",
            "64"
          ],
          "ip_use_zero_broadcast": null,
          "ipx_address": null,
          "ipx_enabled": null,
          "ipx_frame_type": null,
          "ipx_media_type": null,
          "ipx_network_number": null,
          "ipx_virtual_net_number": null,
          "keep_alive_interval": null,
          "keep_alive_time": null,
          "mac_address": "08:00:27:5C:29:1E",
          "mtu": null,
          "num_forward_packets": null,
          "pmtubh_detect_enabled": null,
          "pmtu_discovery_enabled": null,
          "service_name": "E1G60",
          "setting_id": "{05A45C42-813C-4ADF-BCB6-54D4B1DC672C}",
          "tcpip_netbios_options": 0,
          "tcp_max_connect_retransmissions": null,
          "tcp_max_data_retransmissions": null,
          "tcp_num_connections": null,
          "tcp_use_rfc1122_urgent_pointer": null,
          "tcp_window_size": 64240,
          "wins_enable_lm_hosts_lookup": true,
          "wins_host_lookup_file": null,
          "wins_primary_server": null,
          "wins_scope_id": "",
          "wins_secondary_server": null
        },
        "instance": {
          "adapter_type": "Ethernet 802.3",
          "adapter_type_id": 0,
          "auto_sense": null,
          "availability": 3,
          "caption": "[00000001] Intel(R) PRO/1000 MT Desktop Adapter",
          "config_manager_error_code": 0,
          "config_manager_user_config": false,
          "description": "Intel(R) PRO/1000 MT Desktop Adapter",
          "device_id": "1",
          "error_cleared": null,
          "error_description": null,
          "guid": "{05A45C42-813C-4ADF-BCB6-54D4B1DC672C}",
          "index": 1,
          "install_date": null,
          "installed": true,
          "interface_index": 2,
          "last_error_code": null,
          "mac_address": "08:00:27:5C:29:1E",
          "manufacturer": "Intel",
          "max_number_controlled": 0,
          "max_speed": null,
          "name": "Intel(R) PRO/1000 MT Desktop Adapter",
          "net_connection_id": "Ethernet",
          "net_connection_status": 2,
          "net_enabled": true,
          "network_addresses": null,
          "permanent_address": null,
          "physical_adapter": true,
          "pnp_device_id": "PCI\\VEN_8086&DEV_100E&SUBSYS_001E8086&REV_02\\3&267A616A&1&18",
          "power_management_capabilities": null,
          "power_management_supported": false,
          "product_name": "Intel(R) PRO/1000 MT Desktop Adapter",
          "service_name": "E1G60",
          "speed": "1000000000",
          "status": null,
          "status_info": null,
          "system_name": "VAGRANT-2016",
          "time_of_last_reset": "20200107145010.499557+000"
        },
        "counters": {

        },
        "addresses": {
          "10.0.2.15": {
            "prefixlen": "24",
            "netmask": "255.255.255.0",
            "broadcast": "10.0.2.255",
            "family": "inet"
          },
          "fe80::9b0:3012:24e7:7067": {
            "prefixlen": "64",
            "family": "inet6",
            "scope": "Link"
          },
          "08:00:27:5C:29:1E": {
            "family": "lladdr"
          }
        },
        "mtu": null,
        "type": "Ethernet 802.3",
        "arp": {
          "10.0.2.2": "52:54:00:12:35:02",
          "10.0.2.3": "52:54:00:12:35:03",
          "10.0.2.255": "ff:ff:ff:ff:ff:ff",
          "224.0.0.22": "01:00:5e:00:00:16",
          "224.0.0.252": "01:00:5e:00:00:fc",
          "239.255.255.250": "01:00:5e:7f:ff:fa",
          "255.255.255.255": "ff:ff:ff:ff:ff:ff"
        },
        "encapsulation": "Ethernet"
      }
    },
    "default_gateway": "10.0.2.2",
    "default_interface": "0x2"
  },
</pre>

----------------------------------------------------------------------------------------------------------------------------------------


# Filesystem

## ubuntu  

<pre>
 "filesystem": {
    "udev": {
      "kb_size": "473252",
      "kb_used": "0",
      "kb_available": "473252",
      "percent_used": "0%",
      "mount": "/dev",
      "total_inodes": "118313",
      "inodes_used": "403",
      "inodes_available": "117910",
      "inodes_percent_used": "1%",
      "fs_type": "devtmpfs",
      "mount_options": [
        "rw",
        "nosuid",
        "relatime",
        "size=473252k",
        "nr_inodes=118313",
        "mode=755"
      ]
    },
    "tmpfs": {
      "kb_size": "100908",
      "kb_used": "0",
      "kb_available": "100908",
      "percent_used": "0%",
      "mount": "/run/user/1000",
      "total_inodes": "126139",
      "inodes_used": "10",
      "inodes_available": "126129",
      "inodes_percent_used": "1%",
      "fs_type": "tmpfs",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "relatime",
        "size=100908k",
        "mode=700",
        "uid=1000",
        "gid=1000"
      ]
    },
    "/dev/mapper/vagrant--vg-root": {
      "kb_size": "64800356",
      "kb_used": "1681016",
      "kb_available": "59797896",
      "percent_used": "3%",
      "mount": "/",
      "total_inodes": "4136960",
      "inodes_used": "47544",
      "inodes_available": "4089416",
      "inodes_percent_used": "2%",
      "fs_type": "ext4",
      "mount_options": [
        "rw",
        "relatime",
        "errors=remount-ro",
        "data=ordered"
      ],
      "uuid": "2380b918-859a-4c05-94dd-112699668ce6"
    },
    "vagrant": {
      "kb_size": "497814524",
      "kb_used": "158899068",
      "kb_available": "338915456",
      "percent_used": "32%",
      "mount": "/vagrant"
    },
    "sysfs": {
      "mount": "/sys",
      "fs_type": "sysfs",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "noexec",
        "relatime"
      ]
    },
    "proc": {
      "mount": "/proc",
      "fs_type": "proc",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "noexec",
        "relatime"
      ]
    },
    "devpts": {
      "mount": "/dev/pts",
      "fs_type": "devpts",
      "mount_options": [
        "rw",
        "nosuid",
        "noexec",
        "relatime",
        "gid=5",
        "mode=620",
        "ptmxmode=000"
      ]
    },
    "securityfs": {
      "mount": "/sys/kernel/security",
      "fs_type": "securityfs",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "noexec",
        "relatime"
      ]
    },
    "cgroup": {
      "mount": "/sys/fs/cgroup/pids",
      "fs_type": "cgroup",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "noexec",
        "relatime",
        "pids"
      ]
    },
    "pstore": {
      "mount": "/sys/fs/pstore",
      "fs_type": "pstore",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "noexec",
        "relatime"
      ]
    },
    "systemd-1": {
      "mount": "/proc/sys/fs/binfmt_misc",
      "fs_type": "autofs",
      "mount_options": [
        "rw",
        "relatime",
        "fd=37",
        "pgrp=1",
        "timeout=0",
        "minproto=5",
        "maxproto=5",
        "direct",
        "pipe_ino=13623"
      ]
    },
    "mqueue": {
      "mount": "/dev/mqueue",
      "fs_type": "mqueue",
      "mount_options": [
        "rw",
        "relatime"
      ]
    },
    "debugfs": {
      "mount": "/sys/kernel/debug",
      "fs_type": "debugfs",
      "mount_options": [
        "rw",
        "relatime"
      ]
    },
    "hugetlbfs": {
      "mount": "/dev/hugepages",
      "fs_type": "hugetlbfs",
      "mount_options": [
        "rw",
        "relatime",
        "pagesize=2M"
      ]
    },
    "fusectl": {
      "mount": "/sys/fs/fuse/connections",
      "fs_type": "fusectl",
      "mount_options": [
        "rw",
        "relatime"
      ]
    },
    "configfs": {
      "mount": "/sys/kernel/config",
      "fs_type": "configfs",
      "mount_options": [
        "rw",
        "relatime"
      ]
    },
    "sunrpc": {
      "mount": "/run/rpc_pipefs",
      "fs_type": "rpc_pipefs",
      "mount_options": [
        "rw",
        "relatime"
      ]
    },
    "lxcfs": {
      "mount": "/var/lib/lxcfs",
      "fs_type": "fuse.lxcfs",
      "mount_options": [
        "rw",
        "nosuid",
        "nodev",
        "relatime",
        "user_id=0",
        "group_id=0",
        "allow_other"
      ]
    },
    "/vagrant": {
      "mount": "/vagrant",
      "fs_type": "vboxsf",
      "mount_options": [
        "rw",
        "nodev",
        "relatime",
        "iocharset=utf8",
        "uid=1000",
        "gid=1000"
      ]
    },
    "/dev/sda1": {
      "fs_type": "LVM2_member",
      "uuid": "t2mdkA-YYUs-YGO6-LDxu-I8rk-DdPc-dWScXR"
    },
    "/dev/mapper/vagrant--vg-swap_1": {
      "fs_type": "swap",
      "uuid": "f22638ad-4e42-48f2-8895-2d31935ef112"
    }
  },

</pre>

## Windows 
<pre>
 "filesystem": {
    "C:": {
      "kb_size": 62545457,
      "kb_available": 42937565,
      "kb_used": 19607892,
      "percent_used": 31,
      "mount": "C:",
      "fs_type": "ntfs",
      "volume_name": "windows 2016"
    }
  },
</pre>

----------------------------------------------------------------------------------------------------------------------------------------
.
