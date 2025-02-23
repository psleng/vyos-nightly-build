## vyos-1x
- no changes
## vyos-build
- build: T3664: modify the module-level template path instead of setting an environment variable
   - PR: vyos/vyos-build#596
- T6311: Docker add dependency asciidoc-base for nftables
   - PR: vyos/vyos-build#598
- build: T3664: fix architecture mix-in loading
   - PR: vyos/vyos-build#600
- build-script: T3664: Added more options to the image format
   - PR: vyos/vyos-build#603
- build: T3664: use explicit defaults argument in the dict merging function
   - PR: vyos/vyos-build#606
- build: T3664: include build flavor name in the version file
   - PR: vyos/vyos-build#605
- build: T3664: include the architecture field in version data
   - PR: vyos/vyos-build#609
- build: T6330: fix indention of autogenerated release.pref.chroot
   - PR: vyos/vyos-build#612
- build-script: T3664: Added flavor name to a target file name
   - PR: vyos/vyos-build#616
- T3420: Remove service upnp
   - PR: vyos/vyos-build#618
- build-script: T3664: Add flavor and architecture to image name (rework)
   - PR: vyos/vyos-build#620
- T6333 non-free-firmware to trixie
   - PR: vyos/vyos-build#614
- hooks: T6346: set default boot target to multi-user.target
   - PR: vyos/vyos-build#624
- T6356: normalize '.., ntp, server' path syntax in config.boot.default
   - PR: vyos/vyos-build#626
- build-script: T3664: Allowed all options in both config file and comm…
   - PR: vyos/vyos-build#622
- Kernel: T5887: update Linux Kernel to v6.6.31
   - PR: vyos/vyos-build#629
- frr: T6250: T6283: revert local patches merged upstream
   - PR: vyos/vyos-build#631
- T6386: added caller workflows and codeowners
   - PR: vyos/vyos-build#634
- docker: T6388: use OCaml 4.14.2 for package builds
   - PR: vyos/vyos-build#635
- kernel: T6395: Enabled VFIO_NOIOMMU support
   - PR: vyos/vyos-build#638
- T6399: codeowners correction
   - PR: vyos/vyos-build#640
- T6404: update vyos1x-config commit reference
   - PR: vyos/vyos-build#641
- T6406: enables container cpu limits
   - PR: vyos/vyos-build#643
- T6406: enables CONFIG_CFS_BANDWIDTH for cpu cgroup limits
   - PR: vyos/vyos-build#645
- build: T6414: rename the "iso" flavor to "generic"
   - PR: vyos/vyos-build#646
- T6415: Add repo-sync
   - PR: vyos/vyos-build#648
- build: T6446: include support URL in the version data file
   - PR: vyos/vyos-build#649
- migration: T6006: move config.boot.default to vyos-1x
   - PR: vyos/vyos-build#651
- waagent: T6475: Added waagent build instructions
   - PR: vyos/vyos-build#654
- waagent: T6475: Fixed waagent build script permissions
   - PR: vyos/vyos-build#655
- waagent: T6475: Disabled waagent build for ARM64
   - PR: vyos/vyos-build#658
- T6484: Smoketest: Increase KVM memory limit
   - PR: vyos/vyos-build#656
- docker: arm: T6474: Initial support for dynamic arch toml loading
   - PR: vyos/vyos-build#653
- Kernel: T5887: update Linux Kernel to v6.6.34
   - PR: vyos/vyos-build#660
- Kernel: T5887: update Linux Kernel to v6.6.35
   - PR: vyos/vyos-build#666
- T6508: pr workflows updated for branch and target
   - PR: vyos/vyos-build#668
- T6506: Add a linting rule for checking executable bits on scripts
   - PR: vyos/vyos-build#675
- Docker: T6510: add missing build dependencies for vyos-configd tests
   - PR: vyos/vyos-build#677
- T6507: remove references to vyos-world package
   - PR: vyos/vyos-build#667
- T6527: remove legacy packages
   - PR: vyos/vyos-build#680
- Kernel: T5887: update Linux Kernel to v6.6.36
   - PR: vyos/vyos-build#681
- T6546: unused import check permission update
   - PR: vyos/vyos-build#685
- snmp: T6290: add custom package build
   - PR: vyos/vyos-build#686
- Kernel: T5887: update Linux Kernel to v6.6.37
   - PR: vyos/vyos-build#689
- container: T5867: pin specific podman version
   - PR: vyos/vyos-build#690
- ddclient: T5797: switch to Debian SALSA repository
   - PR: vyos/vyos-build#694
- Kernel: T5887: update Linux Kernel to v6.6.39
   - PR: vyos/vyos-build#693
- T6584: Revert "T6293: add Mediatek MT7921 to defconfig"
   - PR: vyos/vyos-build#699
- hostapd: T6597: update hostapd version
   - PR: vyos/vyos-build#702
- frr: T6600: apply pending upstream patch for ospfd ldp-sync
   - PR: vyos/vyos-build#704
- Kernel: T5887: update Linux Kernel to v6.6.41
   - PR: vyos/vyos-build#703
- podman: T6598: add custom podman build for version 4.9.5
   - PR: vyos/vyos-build#709
- Revert "frr: T6600: apply pending upstream patch for ospfd ldp-sync"
   - PR: vyos/vyos-build#710
- podman: T6598: add search PATH for Go
   - PR: vyos/vyos-build#711
- Kernel: T5887: update Linux Kernel to v6.6.42
   - PR: vyos/vyos-build#713
- T6231: Mellanox OFED
   - PR: vyos/vyos-build#665
- build: T6231: include out-of-tree Mellanox driver in image
   - PR: vyos/vyos-build#714
- podman: T6598: add libgpgme11 runtime dependency
   - PR: vyos/vyos-build#718
- Kernel: T5887: update Linux Kernel to v6.6.43
   - PR: vyos/vyos-build#722
- T6386: Fix typo in file name
   - PR: vyos/vyos-build#724
- ddclient: T5792: Use Debian build from Trixie
   - PR: vyos/vyos-build#723
- podman: T6598: add fuse-overlayfs runtime dependency
   - PR: vyos/vyos-build#729
- Kernel: T5887: update Linux Kernel to v6.6.45
   - PR: vyos/vyos-build#733
- Kernel: T5887: update Linux Kernel to v6.6.47
   - PR: vyos/vyos-build#739
- build: T6666: singular image_format in flavor files
   - PR: vyos/vyos-build#738
- T6231: update OFED version and fix build script
   - PR: vyos/vyos-build#744
- linux-kernel: T6485: build modules for thunderbolt and thunderbolt-net
   - PR: vyos/vyos-build#657
- build: T6653: add build/manifest.json file
   - PR: vyos/vyos-build#736
- T6674: Add build-scrips for packages without Jenkins
   - PR: vyos/vyos-build#745
- Kernel: T5887: update Linux Kernel to v6.6.49
   - PR: vyos/vyos-build#748
- T6674: Add workflow to rebuild packages
   - PR: vyos/vyos-build#752
- T1416: T861: T3664: T3664: T2640: various cleanup commits
   - PR: vyos/vyos-build#751
- T6674: Add keys gpg_key_id and package_branch to rebuild packages
   - PR: vyos/vyos-build#753
- T6674: build-kernel: Get kernel version from the defatults
   - PR: vyos/vyos-build#754
- T6703: add support for amd pstate driver
   - PR: vyos/vyos-build#755
- T6674: Fix build package netfilter dependencies
   - PR: vyos/vyos-build#759
- T861: add UEFI Secure Boot support
   - PR: vyos/vyos-build#763
- T6684: new Debian package repo snapshot logic
   - PR: vyos/vyos-build#758
- Kernel: T861: use find over ls when probing for Kernel signing public keys
   - PR: vyos/vyos-build#764
- test: T4919: Fix QEMU TPM test
   - PR: vyos/vyos-build#765
- build: T6653: fix a manifest generation error when using --reuse-iso
   - PR: vyos/vyos-build#766
- build: T3664: improve support for custom build hooks
   - PR: vyos/vyos-build#767
- build: T3664: add an option to specify artifact extensions
   - PR: vyos/vyos-build#768
- ethtool: T6729: upgrade to 6.10 to make use of more --json options
   - PR: vyos/vyos-build#769
- T861: sign all Kernel modules with an ephemeral key
   - PR: vyos/vyos-build#772
- build: T6738: add build_type field to version data instead of the very limited and unused lts_build
   - PR: vyos/vyos-build#773
- build-image: T6742: update vyos1x-config for childless non-leaf node rendering fixes
   - PR: vyos/vyos-build#774
- T861: Fix kernel suffix for package build by actions
   - PR: vyos/vyos-build#776
- T861: Fix mellanox build by actions
   - PR: vyos/vyos-build#778
- docker: T6742: libvyosconfig update for childless node rendering
   - PR: vyos/vyos-build#779
- T6755: Change default vyos mirror URL
   - PR: vyos/vyos-build#780
- T6754: Delete Jenkins build packages
   - PR: vyos/vyos-build#781
- T6758: Add build package xen-guest-agent
   - PR: vyos/vyos-build#788
- T973: Add build script for node_exporter package
   - PR: vyos/vyos-build#785
- T6763: Delete Jenkins file
   - PR: vyos/vyos-build#791
- Kernel: T5887: update Linux Kernel to v6.6.54
   - PR: vyos/vyos-build#790
- T6754: Ignore everyhting under packages folder via .gitignore
   - PR: vyos/vyos-build#795
- Testsuite: T6494: add new make target "test-interfaces"
   - PR: vyos/vyos-build#796
- T6713: Update Realtek r8152 driver
   - PR: vyos/vyos-build#762
- T3303: fix location of os-release file
   - PR: vyos/vyos-build#797
- docker: T4318: libvyosconfig update for set_tag value
   - PR: vyos/vyos-build#800
- T973: upgrade go version in dockerfile
   - PR: vyos/vyos-build#799
- T6765: Fix build python3-vici package
   - PR: vyos/vyos-build#802
- T973: add build script for frr_exporter package
   - PR: vyos/vyos-build#804
- T861: T6713: Sign Realtek drivers
   - PR: vyos/vyos-build#807
- build: T6231: remove Mellanox OFED drivers and tools until their license status is confirmed
   - PR: vyos/vyos-build#808
- actions: T6771: Build docker image without Jenkins
   - PR: vyos/vyos-build#810
- Kernel: T861: T6713: fix generation of realtek driver signature
   - PR: vyos/vyos-build#811
- build: T6776: use the official Zabbix repo for zabbix-agent2
   - PR: vyos/vyos-build#813
- T6713: Build Realtek driver change source repo
   - PR: vyos/vyos-build#816
- T6771: Fix trigger build container state changes
   - PR: vyos/vyos-build#817
- Kernel: T5887: update Linux Kernel to v6.6.58
   - PR: vyos/vyos-build#818
- T6684: new Debian package repo snapshot logic
   - PR: vyos/vyos-build#820
- T6813: Build tarballs for the packages
   - PR: vyos/vyos-build#821
- Kernel: T5887: Revert update Linux Kernel to v6.6.58
   - PR: vyos/vyos-build#823
- live: T5568: Fix live grub menu entries
   - PR: vyos/vyos-build#822
- T6813: Add tarballs for the netfilter
   - PR: vyos/vyos-build#826
- T6840: Build OpenVPN-otp use commit id instead of master
   - PR: vyos/vyos-build#825
- T6844: use our own mirror of the salt repository
   - PR: vyos/vyos-build#829
- T6813: Build tarballs for the packages in the linux-kernel dir
   - PR: vyos/vyos-build#827
- build: T6855: make the custom APT entry and key syntax more flexible
   - PR: vyos/vyos-build#831
- frr: T6854: build FRR with PCRE2 support for better performance
   - PR: vyos/vyos-build#830
- T3501: Fix cli command in check-qemu-install
   - PR: vyos/vyos-build#834
- image-tools: T6864: keep file necessary for compat add image
   - PR: vyos/vyos-build#836
- Kernel: T5887: update Linux Kernel to v6.6.61
   - PR: vyos/vyos-build#838
- T6879: Add build amazon-cloudwatch-agent
   - PR: vyos/vyos-build#839
- scripts: T6877: add a script for merging multiple flavor files
   - PR: vyos/vyos-build#837
- scripts: T6877: fix an error when the base flavor for merging has no packages field
   - PR: vyos/vyos-build#840
- build: T6903: allow passing vyos-1x repo path in an environment variable
   - PR: vyos/vyos-build#841
- build: T6904: allow development builds to have version strings
   - PR: vyos/vyos-build#842
- T6674: add package build instructions for TACACS client libraries
   - PR: vyos/vyos-build#844
- T6912: Fix build package script dependencies
   - PR: vyos/vyos-build#845
- build: T6905: Add stream build type
   - PR: vyos/vyos-build#843
- T6912: Fix build dependency use global dependency
   - PR: vyos/vyos-build#848
- build-flavors: T6913: fix Xen guest agent package in the generic image
   - PR: vyos/vyos-build#846
- build: T6922: add an option to specify bootloaders for the image
   - PR: vyos/vyos-build#850
- build-flavors: T6915: clean up flavor definitions
   - PR: vyos/vyos-build#847
- build: T6859: include EULA files in build type definitions
   - PR: vyos/vyos-build#833
- build: T6923: use the Debian mirror for security updates if it's specified explicitly
   - PR: vyos/vyos-build#849
- docker: T6929: fix sed pattern for change in Opam install.sh
   - PR: vyos/vyos-build#854
- T6718: use the vyconf daemon for validation of set commands
   - PR: vyos/vyos-build#824
- Kernel: T5887: update Linux Kernel to v6.6.64
   - PR: vyos/vyos-build#857
- T6718: update libvyosconfig commit hash for fix to dlopen lib name
   - PR: vyos/vyos-build#858
- flavors: T6942: remove VM guest agents from the generic flavor
   - PR: vyos/vyos-build#856
- frr: T6746: upgrade package to 10.2
   - PR: vyos/vyos-build#853
- Kernel: T5887: update Linux Kernel to v6.6.66
   - PR: vyos/vyos-build#860
- T6960: package-build: Disable unnecessary builds for  package
   - PR: vyos/vyos-build#864
- T6958: Clear Babel config on babeld stop
   - PR: vyos/vyos-build#862
- T6964: Add PHONY to make VPP smoketests
   - PR: vyos/vyos-build#866
- T6674: move patches to "package/<package_name>" subfolder
   - PR: vyos/vyos-build#868
- eula: T6859: reformat file to honor default UNIX 80x25 terminal width and length
   - PR: vyos/vyos-build#867
- T6952: enable exFat in kernel config
   - PR: vyos/vyos-build#863
- T6674: remove all references to Jenkins
   - PR: vyos/vyos-build#869
- T6954: added PR mirror workflows
   - PR: vyos/vyos-build#870
- T6949: Adds build for blackbox exporter deb package
   - PR: vyos/vyos-build#871
- GitHub: adjust PR template to our current needs/workflow
   - PR: vyos/vyos-build#873
- Testsuite: T861: inform smoketest about this environment
   - PR: vyos/vyos-build#872
- Testsuite: T861: use proper base MAC address from RFC7042
   - PR: vyos/vyos-build#874
-  Kernel: T861: enable lockdown subsystem as UEFI secure boot dependency
   - PR: vyos/vyos-build#875
- Testsuite: T6999: validate content of /etc/os-release in target system
   - PR: vyos/vyos-build#876
- T7019: use VyOS release train in /etc/os-release codename over Debian release
   - PR: vyos/vyos-build#877
- packages: T7026: Add a script for building VPP
   - PR: vyos/vyos-build#878
- testsuite: T7031: add version to manifest if not explicitly set
   - PR: vyos/vyos-build#879
- T7032: Add missing libpam-radius-auth build
   - PR: vyos/vyos-build#880
- T7037: Add prebuild hook for the package-build
   - PR: vyos/vyos-build#882
- T7026: Use prebuild hook to build vpp
   - PR: vyos/vyos-build#883
- T7043: Add arguments for CPU and memory for the check-qemu-install
   - PR: vyos/vyos-build#884
- T2326: opennhrp: Removed OpenNHRP package
   - PR: vyos/vyos-build#885
- T7026: Use vpp patches during build as they not applied
   - PR: vyos/vyos-build#886
- T7026: Extend vyos-1x build to include vyos-vpp
   - PR: vyos/vyos-build#881
- T7043: increase smoketest memory to 8G for vpp
   - PR: vyos/vyos-build#887
- T7026: build vpp source plus binaries instead of only binaries
   - PR: vyos/vyos-build#888
- T6895: Build hsflowd with option PSAMPLE
   - PR: vyos/vyos-build#889
- frr: T6746: add libc-ares-dev build dependency
   - PR: vyos/vyos-build#890
- T7046: T6342: update libvyosconfig commit hash
   - PR: vyos/vyos-build#891
- Testsuite: T7043: make build/manifest.json optional
   - PR: vyos/vyos-build#892
- T7106: Extend check-qemu-install to show vpp version
   - PR: vyos/vyos-build#894
- T7105: Disable by default vpp service until it is configured
   - PR: vyos/vyos-build#893
- T7110: Increase memory to 8G for the smoketests
   - PR: vyos/vyos-build#896


