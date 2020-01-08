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
    "os_info": { ...
    },
    "name": "Microsoft Windows Server 2016 Standard Evaluation",
    "release": "10.0.14393",
    "version": "10.0.14393  Build 14393",
    "os": "WINNT",
    "product_type": "Server",
    "server_core": false,
    "cs_info": { ... 
    },
    "machine": "x86_64",
    "system_type": "Mobile"
  },
 
 </pre>

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
</pre>










## Shorted sections

### Ubuntu
#### modulez
sdaasd
### Windows
