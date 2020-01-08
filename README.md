# Ohai WinServer2016 vs Ubuntu18.04

----------------------------------------------------------------------------------------------------------------------------------------
## Ubuntu 18.04                                                        
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

## Windows Server 2016

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
 ## Kernel
 
 ### Ubuntu
 <pre>

  "kernel": {
    "name": "Linux",
    "release": "4.15.0-58-generic",                                 
    "version": "#64-Ubuntu SMP Tue Aug 6 11:12:41 UTC 2019", 
    "machine": "x86_64",
    "processor": "x86_64",
    "os": "GNU/Linux",
    "[modules](#ubuntumodules)": { ...
    }
  }
  
 </pre>
 
 ### Windows
 
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
----------------------------------------------------------------------------------------------------------------------------------------
 ## Operating System

----------------------------------------------------------------------------------------------------------------------------------------
 ## Operating System
 ----------------------------------------------------------------------------------------------------------------------------------------
 ## Operating System
 ----------------------------------------------------------------------------------------------------------------------------------------
 ## Operating System





## <a name="head1">Heading One</a>






-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Shorted sections

## Ubuntu
### <a name="ubuntumodules">Ubuntu Kernel Modules</a>
hello


## Windows 
