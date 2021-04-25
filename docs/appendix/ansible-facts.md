# Ansible Facts

Example of ansible_facts in random virtual host: 
```json
{
  "ansible_facts": {
    "all_ipv4_addresses": [
      "352.12.54.242"
    ],
    "all_ipv6_addresses": [
      "2a01:4f8:c17:8523::1",
      "fe80::3622:ff:fea7:82f8"
    ],
    "ansible_local": {},
    "apparmor": {
      "status": "enabled"
    },
    "architecture": "x86_64",
    "bios_date": "11/11/2017",
    "bios_version": "20171111",
    "cmdline": {
      "BOOT_IMAGE": "/boot/vmlinuz-5.4.0-66-generic",
      "console": "ttyS0",
      "consoleblank": "0",
      "elevator": "noop",
      "ro": true,
      "root": "UUID=a2a22k45-bafb-4bac-a152-d1f0c550294e",
      "systemd.show_status": "true"
    },
    "date_time": {
      "date": "2021-04-25",
      "day": "25",
      "epoch": "1619365961",
      "hour": "17",
      "iso8601": "2021-04-25T15:52:41Z",
      "iso8601_basic": "20210425T175241846740",
      "iso8601_basic_short": "20210425T175241",
      "iso8601_micro": "2021-04-25T15:52:41.846740Z",
      "minute": "52",
      "month": "04",
      "second": "41",
      "time": "17:52:41",
      "tz": "CEST",
      "tz_offset": "+0200",
      "weekday": "Sunday",
      "weekday_number": "0",
      "weeknumber": "16",
      "year": "2021"
    },
    "default_ipv4": {
      "address": "352.12.54.242",
      "alias": "eth0",
      "broadcast": "",
      "gateway": "172.31.1.1",
      "interface": "eth0",
      "macaddress": "96:00:00:a7:32:f8",
      "mtu": 1500,
      "netmask": "255.255.255.255",
      "network": "352.12.54.242",
      "type": "ether"
    },
    "default_ipv6": {
      "address":  "2a01:4f8:c17:8523::1",
      "gateway": "fe80::1",
      "interface": "eth0",
      "macaddress": "96:00:00:a7:32:f8",
      "mtu": 1500,
      "prefix": "64",
      "scope": "global",
      "type": "ether"
    },
    "device_links": {
      "ids": {
        "sda": [
          "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0"
        ],
        "sda1": [
          "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0-part1"
        ],
        "sda14": [
          "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0-part14"
        ],
        "sda15": [
          "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0-part15"
        ],
        "sr0": [
          "ata-QEMU_DVD-ROM_QM00001"
        ]
      },
      "labels": {},
      "masters": {},
      "uuids": {
        "sda1": [
          "a2a55d98-bafb-4bac-a152-d1f0c550294e"
        ],
        "sda15": [
          "F249-9880"
        ]
      }
    },
    "devices": {
      "loop0": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop1": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop2": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop3": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop4": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop5": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop6": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "loop7": {
        "holders": [],
        "host": "",
        "links": {
          "ids": [],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": null,
        "partitions": {},
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "0",
        "sectorsize": "512",
        "size": "0.00 Bytes",
        "support_discard": "0",
        "vendor": null,
        "virtual": 1
      },
      "sda": {
        "holders": [],
        "host": "SCSI storage controller: Red Hat, Inc. Virtio SCSI (rev 01)",
        "links": {
          "ids": [
            "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0"
          ],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": "QEMU HARDDISK",
        "partitions": {
          "sda1": {
            "holders": [],
            "links": {
              "ids": [
                "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0-part1"
              ],
              "labels": [],
              "masters": [],
              "uuids": [
                "a2a55d98-bafb-5bac-a326-d1f0c550294e"
              ]
            },
            "sectors": "79874016",
            "sectorsize": 512,
            "size": "38.09 GB",
            "start": "129024",
            "uuid": "a2a55d98-bafb-4bac-a152-d1f0c550294e"
          },
          "sda14": {
            "holders": [],
            "links": {
              "ids": [
                "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0-part14"
              ],
              "labels": [],
              "masters": [],
              "uuids": []
            },
            "sectors": "2048",
            "sectorsize": 512,
            "size": "1.00 MB",
            "start": "2048",
            "uuid": null
          },
          "sda15": {
            "holders": [],
            "links": {
              "ids": [
                "scsi-0QEMU_QEMU_HARDDISK_drive-scsi0-0-0-0-part15"
              ],
              "labels": [],
              "masters": [],
              "uuids": [
                "F249-9880"
              ]
            },
            "sectors": "124928",
            "sectorsize": 512,
            "size": "61.00 MB",
            "start": "4096",
            "uuid": "F249-9880"
          }
        },
        "removable": "0",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "80003072",
        "sectorsize": "512",
        "size": "38.15 GB",
        "support_discard": "4096",
        "vendor": "QEMU",
        "virtual": 1
      },
      "sr0": {
        "holders": [],
        "host": "SATA controller: Intel Corporation 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode] (rev 02)",
        "links": {
          "ids": [
            "ata-QEMU_DVD-ROM_QM00001"
          ],
          "labels": [],
          "masters": [],
          "uuids": []
        },
        "model": "QEMU DVD-ROM",
        "partitions": {},
        "removable": "1",
        "rotational": "1",
        "sas_address": null,
        "sas_device_handle": null,
        "scheduler_mode": "mq-deadline",
        "sectors": "2097151",
        "sectorsize": "512",
        "size": "1024.00 MB",
        "support_discard": "0",
        "vendor": "QEMU",
        "virtual": 1
      }
    },
    "discovered_interpreter_python": "/usr/bin/python3",
    "distribution": "Ubuntu",
    "distribution_file_parsed": true,
    "distribution_file_path": "/etc/os-release",
    "distribution_file_variety": "Debian",
    "distribution_major_version": "20",
    "distribution_release": "focal",
    "distribution_version": "20.04",
    "dns": {
      "nameservers": [
        "127.0.0.52"
      ],
      "options": {
        "edns0": true,
        "trust-ad": true
      }
    },
    "domain": "",
    "effective_group_id": 1001,
    "effective_user_id": 1000,
    "env": {
      "DBUS_SESSION_BUS_ADDRESS": "unix:path=/run/user/1000/bus",
      "HOME": "/home/myuser",
      "LANG": "C",
      "LC_ADDRESS": "uk_UA.UTF-8",
      "LC_ALL": "C",
      "LC_IDENTIFICATION": "uk_UA.UTF-8",
      "LC_MEASUREMENT": "uk_UA.UTF-8",
      "LC_MESSAGES": "C",
      "LC_MONETARY": "uk_UA.UTF-8",
      "LC_NAME": "uk_UA.UTF-8",
      "LC_NUMERIC": "uk_UA.UTF-8",
      "LC_PAPER": "uk_UA.UTF-8",
      "LC_TELEPHONE": "uk_UA.UTF-8",
      "LOGNAME": "yaroslawww",
      "MOTD_SHOWN": "pam",
      "PATH": "/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin",
      "PWD": "/home/myuser",
      "SHELL": "/bin/bash",
      "SHLVL": "0",
      "SSH_CLIENT": "231.8.63.3 53286 22",
      "SSH_CONNECTION": "231.8.63.3 53286 352.12.54.242 22",
      "SSH_TTY": "/dev/pts/0",
      "TERM": "xterm-256color",
      "USER": "myuser",
      "XDG_RUNTIME_DIR": "/run/user/1000",
      "XDG_SESSION_CLASS": "user",
      "XDG_SESSION_ID": "1777",
      "XDG_SESSION_TYPE": "tty",
      "_": "/bin/sh"
    },
    "eth0": {
      "active": true,
      "device": "eth0",
      "features": {
        "esp_hw_offload": "off [fixed]",
        "esp_tx_csum_hw_offload": "off [fixed]",
        "fcoe_mtu": "off [fixed]",
        "generic_receive_offload": "on",
        "generic_segmentation_offload": "on",
        "highdma": "on [fixed]",
        "hw_tc_offload": "off [fixed]",
        "l2_fwd_offload": "off [fixed]",
        "large_receive_offload": "on",
        "loopback": "off [fixed]",
        "netns_local": "off [fixed]",
        "ntuple_filters": "off [fixed]",
        "receive_hashing": "off [fixed]",
        "rx_all": "off [fixed]",
        "rx_checksumming": "on [fixed]",
        "rx_fcs": "off [fixed]",
        "rx_gro_hw": "off [fixed]",
        "rx_udp_tunnel_port_offload": "off [fixed]",
        "rx_vlan_filter": "on [fixed]",
        "rx_vlan_offload": "off [fixed]",
        "rx_vlan_stag_filter": "off [fixed]",
        "rx_vlan_stag_hw_parse": "off [fixed]",
        "scatter_gather": "on",
        "tcp_segmentation_offload": "on",
        "tls_hw_record": "off [fixed]",
        "tls_hw_rx_offload": "off [fixed]",
        "tls_hw_tx_offload": "off [fixed]",
        "tx_checksum_fcoe_crc": "off [fixed]",
        "tx_checksum_ip_generic": "on",
        "tx_checksum_ipv4": "off [fixed]",
        "tx_checksum_ipv6": "off [fixed]",
        "tx_checksum_sctp": "off [fixed]",
        "tx_checksumming": "on",
        "tx_esp_segmentation": "off [fixed]",
        "tx_fcoe_segmentation": "off [fixed]",
        "tx_gre_csum_segmentation": "off [fixed]",
        "tx_gre_segmentation": "off [fixed]",
        "tx_gso_partial": "off [fixed]",
        "tx_gso_robust": "on [fixed]",
        "tx_ipxip4_segmentation": "off [fixed]",
        "tx_ipxip6_segmentation": "off [fixed]",
        "tx_lockless": "off [fixed]",
        "tx_nocache_copy": "off",
        "tx_scatter_gather": "on",
        "tx_scatter_gather_fraglist": "off [fixed]",
        "tx_sctp_segmentation": "off [fixed]",
        "tx_tcp6_segmentation": "on",
        "tx_tcp_ecn_segmentation": "on",
        "tx_tcp_mangleid_segmentation": "off",
        "tx_tcp_segmentation": "on",
        "tx_udp_segmentation": "off [fixed]",
        "tx_udp_tnl_csum_segmentation": "off [fixed]",
        "tx_udp_tnl_segmentation": "off [fixed]",
        "tx_vlan_offload": "off [fixed]",
        "tx_vlan_stag_hw_insert": "off [fixed]",
        "vlan_challenged": "off [fixed]"
      },
      "hw_timestamp_filters": [],
      "ipv4": {
        "address": "352.12.54.242",
        "broadcast": "",
        "netmask": "255.255.255.255",
        "network": "352.12.54.242"
      },
      "ipv6": [
        {
          "address": "2a01:4f8:c17:d536::1",
          "prefix": "64",
          "scope": "global"
        },
        {
          "address": "fe80::4500:ff:fea7:82f8",
          "prefix": "64",
          "scope": "link"
        }
      ],
      "macaddress": "96:00:00:a7:32:f8",
      "module": "virtio_net",
      "mtu": 1500,
      "pciid": "virtio1",
      "promisc": false,
      "speed": -1,
      "timestamping": [
        "tx_software",
        "rx_software",
        "software"
      ],
      "type": "ether"
    },
    "fibre_channel_wwn": [],
    "fips": false,
    "form_factor": "Other",
    "fqdn": "some-name-here",
    "gather_subset": [
      "all"
    ],
    "hostname": "some-name-here",
    "hostnqn": "",
    "interfaces": [
      "eth0",
      "lo"
    ],
    "is_chroot": false,
    "iscsi_iqn": "",
    "kernel": "5.4.0-66-generic",
    "kernel_version": "#74-Ubuntu SMP Wed Jan 27 22:54:38 UTC 2021",
    "lo": {
      "active": true,
      "device": "lo",
      "features": {
        "esp_hw_offload": "off [fixed]",
        "esp_tx_csum_hw_offload": "off [fixed]",
        "fcoe_mtu": "off [fixed]",
        "generic_receive_offload": "on",
        "generic_segmentation_offload": "on",
        "highdma": "on [fixed]",
        "hw_tc_offload": "off [fixed]",
        "l2_fwd_offload": "off [fixed]",
        "large_receive_offload": "off [fixed]",
        "loopback": "on [fixed]",
        "netns_local": "on [fixed]",
        "ntuple_filters": "off [fixed]",
        "receive_hashing": "off [fixed]",
        "rx_all": "off [fixed]",
        "rx_checksumming": "on [fixed]",
        "rx_fcs": "off [fixed]",
        "rx_gro_hw": "off [fixed]",
        "rx_udp_tunnel_port_offload": "off [fixed]",
        "rx_vlan_filter": "off [fixed]",
        "rx_vlan_offload": "off [fixed]",
        "rx_vlan_stag_filter": "off [fixed]",
        "rx_vlan_stag_hw_parse": "off [fixed]",
        "scatter_gather": "on",
        "tcp_segmentation_offload": "on",
        "tls_hw_record": "off [fixed]",
        "tls_hw_rx_offload": "off [fixed]",
        "tls_hw_tx_offload": "off [fixed]",
        "tx_checksum_fcoe_crc": "off [fixed]",
        "tx_checksum_ip_generic": "on [fixed]",
        "tx_checksum_ipv4": "off [fixed]",
        "tx_checksum_ipv6": "off [fixed]",
        "tx_checksum_sctp": "on [fixed]",
        "tx_checksumming": "on",
        "tx_esp_segmentation": "off [fixed]",
        "tx_fcoe_segmentation": "off [fixed]",
        "tx_gre_csum_segmentation": "off [fixed]",
        "tx_gre_segmentation": "off [fixed]",
        "tx_gso_partial": "off [fixed]",
        "tx_gso_robust": "off [fixed]",
        "tx_ipxip4_segmentation": "off [fixed]",
        "tx_ipxip6_segmentation": "off [fixed]",
        "tx_lockless": "on [fixed]",
        "tx_nocache_copy": "off [fixed]",
        "tx_scatter_gather": "on [fixed]",
        "tx_scatter_gather_fraglist": "on [fixed]",
        "tx_sctp_segmentation": "on",
        "tx_tcp6_segmentation": "on",
        "tx_tcp_ecn_segmentation": "on",
        "tx_tcp_mangleid_segmentation": "on",
        "tx_tcp_segmentation": "on",
        "tx_udp_segmentation": "off [fixed]",
        "tx_udp_tnl_csum_segmentation": "off [fixed]",
        "tx_udp_tnl_segmentation": "off [fixed]",
        "tx_vlan_offload": "off [fixed]",
        "tx_vlan_stag_hw_insert": "off [fixed]",
        "vlan_challenged": "on [fixed]"
      },
      "hw_timestamp_filters": [],
      "ipv4": {
        "address": "127.0.0.1",
        "broadcast": "",
        "netmask": "255.0.0.0",
        "network": "127.0.0.0"
      },
      "ipv6": [
        {
          "address": "::1",
          "prefix": "128",
          "scope": "host"
        }
      ],
      "mtu": 655124,
      "promisc": false,
      "timestamping": [
        "tx_software",
        "rx_software",
        "software"
      ],
      "type": "loopback"
    },
    "lsb": {
      "codename": "focal",
      "description": "Ubuntu 20.04.2 LTS",
      "id": "Ubuntu",
      "major_release": "20",
      "release": "20.04"
    },
    "machine": "x86_64",
    "machine_id": "d58adff30edd4c7e8d819998762a2edc",
    "memfree_mb": 231,
    "memory_mb": {
      "nocache": {
        "free": 1371,
        "used": 568
      },
      "real": {
        "free": 231,
        "total": 1939,
        "used": 1708
      },
      "swap": {
        "cached": 0,
        "free": 0,
        "total": 0,
        "used": 0
      }
    },
    "memtotal_mb": 1939,
    "module_setup": true,
    "mounts": [
      {
        "block_available": 8813571,
        "block_size": 4096,
        "block_total": 9811330,
        "block_used": 997759,
        "device": "/dev/sda1",
        "fstype": "ext4",
        "inode_available": 2451605,
        "inode_total": 2493680,
        "inode_used": 42075,
        "mount": "/",
        "options": "rw,relatime,errors=remount-ro",
        "size_available": 36100386816,
        "size_total": 40187207680,
        "uuid": "a2a55d98-bafb-4bac-a152-d1f0c550294e"
      },
      {
        "block_available": 117815,
        "block_size": 512,
        "block_total": 122974,
        "block_used": 5159,
        "device": "/dev/sda15",
        "fstype": "vfat",
        "inode_available": 0,
        "inode_total": 0,
        "inode_used": 0,
        "mount": "/boot/efi",
        "options": "rw,relatime,fmask=0077,dmask=0077,codepage=437,iocharset=iso8859-1,shortname=mixed,errors=remount-ro",
        "size_available": 60321280,
        "size_total": 62962688,
        "uuid": "F249-9880"
      }
    ],
    "nodename": "some-name-here",
    "os_family": "Debian",
    "pkg_mgr": "apt",
    "proc_cmdline": {
      "BOOT_IMAGE": "/boot/vmlinuz-5.4.0-66-generic",
      "console": [
        "tty1",
        "ttyS0"
      ],
      "consoleblank": "0",
      "elevator": "noop",
      "ro": true,
      "root": "UUID=a2a55d98-bafb-4bac-a152-d1f0c550294e",
      "systemd.show_status": "true"
    },
    "processor": [
      "0",
      "AuthenticAMD",
      "AMD EPYC Processor (with IBPB)",
      "1",
      "AuthenticAMD",
      "AMD EPYC Processor (with IBPB)"
    ],
    "processor_cores": 2,
    "processor_count": 1,
    "processor_threads_per_core": 1,
    "processor_vcpus": 2,
    "product_name": "vServer",
    "product_serial": "NA",
    "product_uuid": "NA",
    "product_version": "20171111",
    "python": {
      "executable": "/usr/bin/python3",
      "has_sslcontext": true,
      "type": "cpython",
      "version": {
        "major": 3,
        "micro": 5,
        "minor": 8,
        "releaselevel": "final",
        "serial": 0
      },
      "version_info": [
        3,
        8,
        5,
        "final",
        0
      ]
    },
    "python_version": "3.8.5",
    "real_group_id": 1001,
    "real_user_id": 1000,
    "selinux": {
      "status": "Missing selinux Python library"
    },
    "selinux_python_present": false,
    "service_mgr": "systemd",
    "ssh_host_key_dsa_public": "AAAAB3NzaC1kc3MAAACBANNjADghkuNCg7dFccMuqhia7v68Figw37BNtxuINQ8g7HIxH85Edw7VT53EdTNuDD1l6AemtS+NNUufNZI1/GqzNcYsgcpyQmLiLdyAS1vhu56D1yVPwdvGtmqD92z21P04RBBRVT7Ya9CpVtmllggujxXmekHrpH2wNa1OOCOPAAAAFQDMl/rVYGiHl0rs1ErtFEI1UB6TpQAAAIEAmC07okzrojeWL3ijZayBbiKBnjsEIUGzmzxp23kna8E/lN02BXxmWZ3StiqMElae85/A4GBcWhoFAUfPYwI+do1SodNPlOnI9ZbbEn6Ua4kdRudVRV8wM2AcgkZSDJTAAlK+az20OajYKex/wTmwYQi13GXLpVJKi6Z0tU1FdhUAAACBAMUU6PNfegETlhC2NLz6envCO0+/8qOFqZ/tdIOClXTEUdQ9jv9duXSRFLlAaWzuvHNJBbmyDZltEsF1S5/1GSxcM0YZCbsApkNpgJHuxaUvzp5O5M8kNxPbMKic53JW+k/kCxQGqFwPzdESJbNSWZilWpEOVdCnb5FFhYL7FPST",
    "ssh_host_key_ecdsa_public": "AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBEUi8pGDQsZ+AMPLavMsvIMpR73sSK57Qpc/W7Ir2Ta43F8qZ6Y1FtWWPVXbYsc0hZYwhUmuC3ucu+oOd+XZ4bs=",
    "ssh_host_key_ed25519_public": "AAAAC3NzaC1lZDI1NTE5AAAAIDbXdIjJXa2ydka+jh4GW+UZTJzyNIyFRub04ZKdWLEG",
    "ssh_host_key_rsa_public": "AAAAB3NzaC1yc2EAAAADAQABAAABgQC/51CsJXhN4THU/xxtvG1YHgENwmjX0ZROsGKor5R8Buo78TRcAZ/0z2TkdnSX8+ScYw0KPpDFjnAsFbakbr8POeCM85z/kc2rb90OQVlIL+LbweGF48nJnMcl5DGEouQNyXcTRUWAuCLT7Ptsqx/C7vigAGsBrkvnFBshjtPpFnRTeQ9441MZppgMuZjt1gdpk7Vw0bjxnQpGPvm3hoj8wa6E/Top/OnzB1sUL/izlP43h9dud687/NkVwIBUaOcMEPF1dm5fsMb8CD+RFeEJN/MbKoRIlmUp0+bkWMV/umaQNnmjodUXG3lWS68xM/Xf4i+eKxp/z/n6yv268UQcGUNtPT8otVOIv9zEOjeE+7HGXDXSZjLCd/rxgnI1HurGnONy3UsocAx4qIPynvMUvdVeh3aqRZ6uCarxuFBXxof6lgPB4s0IkEemuY7i2qAG6v6pUUpmOeGDOuokNMhgYsD5HUh4tcI6TX/2pgctMGcUka2BNRjI/hItNE5SkAE=",
    "swapfree_mb": 0,
    "swaptotal_mb": 0,
    "system": "Linux",
    "system_capabilities": [
      ""
    ],
    "system_capabilities_enforced": "True",
    "system_vendor": "Hetzner",
    "uptime_seconds": 1834005,
    "user_dir": "/home/myuser",
    "user_gecos": "",
    "user_gid": 1001,
    "user_id": "myuser",
    "user_shell": "/bin/bash",
    "user_uid": 1000,
    "userspace_architecture": "x86_64",
    "userspace_bits": "64",
    "virtualization_role": "guest",
    "virtualization_type": "kvm"
  }
}
```
