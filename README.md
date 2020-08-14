# Otus_3th_homework
<pre>[andrey@localhost LVM]$ vagrant up
Bringing machine &apos;lvm&apos; up with &apos;virtualbox&apos; provider...
<b>==&gt; lvm: Importing base box &apos;centos/7&apos;...</b>
<b>==&gt; lvm: Matching MAC address for NAT networking...</b>
<b>==&gt; lvm: Checking if box &apos;centos/7&apos; version &apos;1804.02&apos; is up to date...</b>
<b>==&gt; lvm: Setting the name of the VM: LVM_lvm_1597325809268_33612</b>
<b>==&gt; lvm: Clearing any previously set network interfaces...</b>
<b>==&gt; lvm: Preparing network interfaces based on configuration...</b>
    lvm: Adapter 1: nat
    lvm: Adapter 2: hostonly
<b>==&gt; lvm: Forwarding ports...</b>
    lvm: 22 (guest) =&gt; 2222 (host) (adapter 1)
<b>==&gt; lvm: Running &apos;pre-boot&apos; VM customizations...</b>
<b>==&gt; lvm: Booting VM...</b>
<b>==&gt; lvm: Waiting for machine to boot. This may take a few minutes...</b>
    lvm: SSH address: 127.0.0.1:2222
    lvm: SSH username: vagrant
    lvm: SSH auth method: private key
    lvm: 
    lvm: Vagrant insecure key detected. Vagrant will automatically replace
    lvm: this with a newly generated keypair for better security.
    lvm: 
    lvm: Inserting generated public key within guest...
    lvm: Removing insecure key from the guest if it&apos;s present...
    lvm: Key inserted! Disconnecting and reconnecting using new SSH key...
<b>==&gt; lvm: Machine booted and ready!</b>
<b>==&gt; lvm: Checking for guest additions in VM...</b>
    lvm: No guest additions were detected on the base box for this VM! Guest
    lvm: additions are required for forwarded ports, shared folders, host only
    lvm: networking, and more. If SSH fails on this machine, please install
    lvm: the guest additions and repackage the box to continue.
    lvm: 
    lvm: This is not an error message; everything may continue to work properly,
    lvm: in which case you may ignore this message.
<b>==&gt; lvm: Setting hostname...</b>
<b>==&gt; lvm: Configuring and enabling network interfaces...</b>
<b>==&gt; lvm: Rsyncing folder: /home2/andrey/LVM/ =&gt; /vagrant</b>
<b>==&gt; lvm: Running provisioner: shell...</b>
    lvm: Running: inline script
<font color="#859900">    lvm: Loaded plugins: fastestmirror</font>
<font color="#859900">    lvm: Determining fastest mirrors</font>
<font color="#859900">    lvm:  * base: mirror.axelname.ru</font>
<font color="#859900">    lvm:  * extras: mirror.axelname.ru</font>
<font color="#859900">    lvm:  * updates: mirror.axelname.ru</font>
<font color="#859900">    lvm: Resolving Dependencies</font>
<font color="#859900">    lvm: --&gt; Running transaction check</font>
<font color="#859900">    lvm: ---&gt; Package gdisk.x86_64 0:0.8.10-3.el7 will be installed</font>
<font color="#859900">    lvm: ---&gt; Package hdparm.x86_64 0:9.43-5.el7 will be installed</font>
<font color="#859900">    lvm: ---&gt; Package mdadm.x86_64 0:4.1-4.el7 will be installed</font>
<font color="#859900">    lvm: --&gt; Processing Dependency: libreport-filesystem for package: mdadm-4.1-4.el7.x86_64</font>
<font color="#859900">    lvm: ---&gt; Package smartmontools.x86_64 1:7.0-2.el7 will be installed</font>
<font color="#859900">    lvm: --&gt; Processing Dependency: mailx for package: 1:smartmontools-7.0-2.el7.x86_64</font>
<font color="#859900">    lvm: --&gt; Running transaction check</font>
<font color="#859900">    lvm: ---&gt; Package libreport-filesystem.x86_64 0:2.1.11-53.el7.centos will be installed</font>
<font color="#859900">    lvm: ---&gt; Package mailx.x86_64 0:12.5-19.el7 will be installed</font>
<font color="#859900">    lvm: --&gt; Finished Dependency Resolution</font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: Dependencies Resolved</font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: ================================================================================</font>
<font color="#859900">    lvm:  Package                  Arch       Version                     Repository</font>
<font color="#859900">    lvm:                                                                            Size</font>
<font color="#859900">    lvm: ================================================================================</font>
<font color="#859900">    lvm: Installing:</font>
<font color="#859900">    lvm:  gdisk                    x86_64     0.8.10-3.el7                base     190 k</font>
<font color="#859900">    lvm:  hdparm                   x86_64     9.43-5.el7                  base      83 k</font>
<font color="#859900">    lvm:  mdadm                    x86_64     4.1-4.el7                   base     439 k</font>
<font color="#859900">    lvm:  smartmontools            x86_64     1:7.0-2.el7                 base     546 k</font>
<font color="#859900">    lvm: Installing for dependencies:</font>
<font color="#859900">    lvm:  libreport-filesystem     x86_64     2.1.11-53.el7.centos        base      41 k</font>
<font color="#859900">    lvm:  mailx                    x86_64     12.5-19.el7                 base     245 k</font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: Transaction Summary</font>
<font color="#859900">    lvm: ================================================================================</font>
<font color="#859900">    lvm: Install  4 Packages (+2 Dependent packages)</font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: Total download size: 1.5 M</font>
<font color="#859900">    lvm: Installed size: 4.3 M</font>
<font color="#859900">    lvm: Downloading packages:</font>
<font color="#859900">    lvm: Public key for libreport-filesystem-2.1.11-53.el7.centos.x86_64.rpm is not installed</font>
<font color="#DC322F">    lvm: warning: /var/cache/yum/x86_64/7/base/packages/libreport-filesystem-2.1.11-53.el7.centos.x86_64.rpm: Header V3 RSA/SHA256 Signature, key ID f4a80eb5: NOKEY</font>
<font color="#859900">    lvm: --------------------------------------------------------------------------------</font>
<font color="#859900">    lvm: Total                                              469 kB/s | 1.5 MB  00:03     </font>
<font color="#859900">    lvm: Retrieving key from file:///etc/pki/rpm-gpg/RPM-GPG-KEY-CentOS-7</font>
<font color="#DC322F">    lvm: Importing GPG key 0xF4A80EB5:</font>
<font color="#DC322F">    lvm:  Userid     : &quot;CentOS-7 Key (CentOS 7 Official Signing Key) &lt;security@centos.org&gt;&quot;</font>
<font color="#DC322F">    lvm:  Fingerprint: 6341 ab27 53d7 8a78 a7c2 7bb1 24c6 a8a7 f4a8 0eb5</font>
<font color="#DC322F">    lvm:  Package    : centos-release-7-5.1804.el7.centos.x86_64 (@anaconda)</font>
<font color="#DC322F">    lvm:  From       : /etc/pki/rpm-gpg/RPM-GPG-KEY-CentOS-7</font>
<font color="#859900">    lvm: Running transaction check</font>
<font color="#859900">    lvm: Running transaction test</font>
<font color="#859900">    lvm: Transaction test succeeded</font>
<font color="#859900">    lvm: Running transaction</font>
<font color="#859900">    lvm:   Installing : libreport-filesystem-2.1.11-53.el7.centos.x86_64             1/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Installing : mailx-12.5-19.el7.x86_64                                     2/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Installing : 1:smartmontools-7.0-2.el7.x86_64                             3/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Installing : mdadm-4.1-4.el7.x86_64                                       4/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Installing : hdparm-9.43-5.el7.x86_64                                     5/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Installing : gdisk-0.8.10-3.el7.x86_64                                    6/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Verifying  : 1:smartmontools-7.0-2.el7.x86_64                             1/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Verifying  : gdisk-0.8.10-3.el7.x86_64                                    2/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Verifying  : mailx-12.5-19.el7.x86_64                                     3/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Verifying  : hdparm-9.43-5.el7.x86_64                                     4/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Verifying  : mdadm-4.1-4.el7.x86_64                                       5/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm:   Verifying  : libreport-filesystem-2.1.11-53.el7.centos.x86_64             6/6</font>
<font color="#859900">    lvm:  </font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: Installed:</font>
<font color="#859900">    lvm:   gdisk.x86_64 0:0.8.10-3.el7          hdparm.x86_64 0:9.43-5.el7               </font>
<font color="#859900">    lvm:   mdadm.x86_64 0:4.1-4.el7             smartmontools.x86_64 1:7.0-2.el7         </font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: Dependency Installed:</font>
<font color="#859900">    lvm:   libreport-filesystem.x86_64 0:2.1.11-53.el7.centos mailx.x86_64 0:12.5-19.el7</font>
<font color="#859900">    lvm: </font>
<font color="#859900">    lvm: Complete!</font>
[andrey@localhost LVM]$ vagrant ssh
[vagrant@lvm ~]$ script
Script started, file is typescript
[vagrant@lvm ~]$ exit
Script done, file is typescript
[vagrant@lvm ~]$ sudo -s
[root@lvm vagrant]# script
Script started, file is typescript
[root@lvm vagrant]# lsblk
NAME                    MAJ:MIN RM  SIZE RO TYPE MOUNTPOINT
sda                       8:0    0   40G  0 disk 
├─sda1                    8:1    0    1M  0 part 
├─sda2                    8:2    0    1G  0 part /boot
└─sda3                    8:3    0   39G  0 part 
  ├─VolGroup00-LogVol00 253:0    0 37.5G  0 lvm  /
  └─VolGroup00-LogVol01 253:1    0  1.5G  0 lvm  [SWAP]
sdb                       8:16   0   10G  0 disk 
sdc                       8:32   0    2G  0 disk 
sdd                       8:48   0    1G  0 disk 
sde                       8:64   0    1G  0 disk 
[root@lvm vagrant]# pvcreate /dev/sdb
  Physical volume &quot;/dev/sdb&quot; successfully created.
[root@lvm vagrant]# vgcreate vg_root /dev/sdb
  Volume group &quot;vg_root&quot; successfully created
[root@lvm vagrant]# lvcreate -n lv_root -l+100%FREE /dev/vg_root
  Logical volume &quot;lv_root&quot; created.
[root@lvm vagrant]# mkfs.xfs /dev/vg_root/lv_root
meta-data=/dev/vg_root/lv_root   isize=512    agcount=4, agsize=655104 blks
         =                       sectsz=512   attr=2, projid32bit=1
         =                       crc=1        finobt=0, sparse=0
data     =                       bsize=4096   blocks=2620416, imaxpct=25
         =                       sunit=0      swidth=0 blks
naming   =version 2              bsize=4096   ascii-ci=0 ftype=1
log      =internal log           bsize=4096   blocks=2560, version=2
         =                       sectsz=512   sunit=0 blks, lazy-count=1
realtime =none                   extsz=4096   blocks=0, rtextents=0
[root@lvm vagrant]# mount /dev/vg_root/lv_root /mnt
[root@lvm vagrant]# mount |grep lv_root
/dev/mapper/vg_root-<font color="#CB4B16"><b>lv_root</b></font> on /mnt type xfs (rw,relatime,seclabel,attr2,inode64,noquota)
[root@lvm vagrant]# yum install xfsdump
Loaded plugins: fastestmirror
Loading mirror speeds from cached hostfile
 * base: mirror.axelname.ru
 * extras: mirror.axelname.ru
 * updates: mirror.axelname.ru
Resolving Dependencies
--&gt; Running transaction check
---&gt; Package xfsdump.x86_64 0:3.1.7-1.el7 will be installed
--&gt; Processing Dependency: attr &gt;= 2.0.0 for package: xfsdump-3.1.7-1.el7.x86_64
--&gt; Running transaction check
---&gt; Package attr.x86_64 0:2.4.46-13.el7 will be installed
--&gt; Finished Dependency Resolution

Dependencies Resolved

=========================================================================================================
 Package                 Arch                   Version                       Repository            Size
=========================================================================================================
Installing:
 xfsdump                 x86_64                 3.1.7-1.el7                   base                 308 k
Installing for dependencies:
 attr                    x86_64                 2.4.46-13.el7                 base                  66 k

Transaction Summary
=========================================================================================================
Install  1 Package (+1 Dependent package)

Total download size: 374 k
Installed size: 1.1 M
Is this ok [y/d/N]: y
Downloading packages:
(1/2): attr-2.4.46-13.el7.x86_64.rpm                                              |  66 kB  00:00:00     
(2/2): xfsdump-3.1.7-1.el7.x86_64.rpm                                             | 308 kB  00:00:00     
---------------------------------------------------------------------------------------------------------
Total                                                                    621 kB/s | 374 kB  00:00:00     
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : attr-2.4.46-13.el7.x86_64                                                             1/2 
  Installing : xfsdump-3.1.7-1.el7.x86_64                                                            2/2 
  Verifying  : attr-2.4.46-13.el7.x86_64                                                             1/2 
  Verifying  : xfsdump-3.1.7-1.el7.x86_64                                                            2/2 

Installed:
  xfsdump.x86_64 0:3.1.7-1.el7                                                                           

Dependency Installed:
  attr.x86_64 0:2.4.46-13.el7                                                                            

Complete!
[root@lvm vagrant]# xfsdump -J - /dev/VolGroup00/LogVol00 | xfsrestore -J - /mnt
xfsrestore: using file dump (drive_simple) strategy
xfsrestore: version 3.1.7 (dump format 3.0)
xfsdump: using file dump (drive_simple) strategy
xfsdump: version 3.1.7 (dump format 3.0)
xfsdump: level 0 dump of lvm:/
xfsdump: dump date: Thu Aug 13 13:44:47 2020
xfsdump: session id: 548ec4de-cdcb-47fc-89ee-e2df7dfd475f
xfsdump: session label: &quot;&quot;
xfsrestore: searching media for dump
xfsdump: ino map phase 1: constructing initial dump list
xfsdump: ino map phase 2: skipping (no pruning necessary)
xfsdump: ino map phase 3: skipping (only one dump stream)
xfsdump: ino map construction complete
xfsdump: estimated dump size: 739198784 bytes
xfsdump: creating dump session media file 0 (media 0, file 0)
xfsdump: dumping ino map
xfsdump: dumping directories
xfsrestore: examining media file 0
xfsrestore: dump description: 
xfsrestore: hostname: lvm
xfsrestore: mount point: /
xfsrestore: volume: /dev/mapper/VolGroup00-LogVol00
xfsrestore: session time: Thu Aug 13 13:44:47 2020
xfsrestore: level: 0
xfsrestore: session label: &quot;&quot;
xfsrestore: media label: &quot;&quot;
xfsrestore: file system id: b60e9498-0baa-4d9f-90aa-069048217fee
xfsrestore: session id: 548ec4de-cdcb-47fc-89ee-e2df7dfd475f
xfsrestore: media id: 07cfa3e9-0fb8-4473-a125-deca20a0f554
xfsrestore: searching media for directory dump
xfsrestore: reading directories
xfsdump: dumping non-directory files
xfsrestore: 2698 directories and 23615 entries processed
xfsrestore: directory post-processing
xfsrestore: restoring non-directory files
xfsdump: ending media file
xfsdump: media file size 716254824 bytes
xfsdump: dump size (non-dir files) : 703092000 bytes
xfsdump: dump complete: 11 seconds elapsed
xfsdump: Dump Status: SUCCESS
xfsrestore: restore complete: 11 seconds elapsed
xfsrestore: Restore Status: SUCCESS
[root@lvm vagrant]# for i in /proc/ /sys/ /dev/ /run/ /boot/; do mount --bind $i /mnt/$i;done
[root@lvm vagrant]# chroot /mnt
[root@lvm /]# grub2-mkconfig -o /boot/grub2/grub.cfg
Generating grub configuration file ...
Found linux image: /boot/vmlinuz-3.10.0-862.2.3.el7.x86_64
Found initrd image: /boot/initramfs-3.10.0-862.2.3.el7.x86_64.img
done
[root@lvm /]# cd /boot ; for i in &apos;ls initramfs-*img&apos;; do dracut -v $i &apos;echo $i|sed &quot;s/initramfs-//g;s/.img//g&quot;&apos; --force; done

Unknown arguments: echo $i|sed &quot;s/initramfs-//g;s/.img//g&quot;

Usage: /sbin/dracut [OPTION]... [&lt;initramfs&gt; [&lt;kernel-version&gt;]]

Version: 033-535.el7

Creates initial ramdisk images for preloading modules

  -h, --help  Display all options

If a [LIST] has multiple arguments, then you have to put these in quotes.

For example:

    # dracut --add-drivers &quot;module1 module2&quot;  ...

[root@lvm boot]# cd /boot ; for i in `ls initramfs-*img`; do dracut -v $i `echo $i|sed &quot;s/initramfs-//g; s/.img//g&quot;` --force; done
Executing: /sbin/dracut -v initramfs-3.10.0-862.2.3.el7.x86_64.img 3.10.0-862.2.3.el7.x86_64 --force
dracut module &apos;busybox&apos; will not be installed, because command &apos;busybox&apos; could not be found!
dracut module &apos;crypt&apos; will not be installed, because command &apos;cryptsetup&apos; could not be found!
dracut module &apos;dmraid&apos; will not be installed, because command &apos;dmraid&apos; could not be found!
dracut module &apos;dmsquash-live-ntfs&apos; will not be installed, because command &apos;ntfs-3g&apos; could not be found!
dracut module &apos;multipath&apos; will not be installed, because command &apos;multipath&apos; could not be found!
dracut module &apos;busybox&apos; will not be installed, because command &apos;busybox&apos; could not be found!
dracut module &apos;crypt&apos; will not be installed, because command &apos;cryptsetup&apos; could not be found!
dracut module &apos;dmraid&apos; will not be installed, because command &apos;dmraid&apos; could not be found!
dracut module &apos;dmsquash-live-ntfs&apos; will not be installed, because command &apos;ntfs-3g&apos; could not be found!
dracut module &apos;multipath&apos; will not be installed, because command &apos;multipath&apos; could not be found!
*** Including module: bash ***
*** Including module: nss-softokn ***
*** Including module: i18n ***
*** Including module: drm ***
*** Including module: plymouth ***
*** Including module: dm ***
Skipping udev rule: 64-device-mapper.rules
Skipping udev rule: 60-persistent-storage-dm.rules
Skipping udev rule: 55-dm.rules
*** Including module: kernel-modules ***
Omitting driver floppy
*** Including module: lvm ***
Skipping udev rule: 64-device-mapper.rules
Skipping udev rule: 56-lvm.rules
Skipping udev rule: 60-persistent-storage-lvm.rules
*** Including module: qemu ***
*** Including module: resume ***
*** Including module: rootfs-block ***
*** Including module: terminfo ***
*** Including module: udev-rules ***
Skipping udev rule: 40-redhat-cpu-hotplug.rules
Skipping udev rule: 91-permissions.rules
*** Including module: biosdevname ***
*** Including module: systemd ***
*** Including module: usrmount ***
*** Including module: base ***
*** Including module: fs-lib ***
*** Including module: shutdown ***
*** Including modules done ***
*** Installing kernel module dependencies and firmware ***
*** Installing kernel module dependencies and firmware done ***
*** Resolving executable dependencies ***
*** Resolving executable dependencies done***
*** Hardlinking files ***
*** Hardlinking files done ***
*** Stripping files ***
*** Stripping files done ***
*** Generating early-microcode cpio image contents ***
*** No early-microcode cpio image needed ***
*** Store current command line parameters ***
*** Creating image file ***
*** Creating image file done ***
*** Creating initramfs image file &apos;/boot/initramfs-3.10.0-862.2.3.el7.x86_64.img&apos; done ***
[root@lvm boot]# vi ./boot/grub2/grub.cfg
[root@lvm boot]# vi /boot/grub2/grub.cfg
[root@lvm boot]# exit
[root@lvm vagrant]# exit
exit
Script done, file is typescript
[root@lvm vagrant]# exit
exit
[vagrant@lvm ~]$ exit
logout
Connection to 127.0.0.1 closed.
[andrey@localhost LVM]$ vagrant halt
<b>==&gt; lvm: Attempting graceful shutdown of VM...</b>
[andrey@localhost LVM]$ vagrant up
Bringing machine &apos;lvm&apos; up with &apos;virtualbox&apos; provider...
<b>==&gt; lvm: Checking if box &apos;centos/7&apos; version &apos;1804.02&apos; is up to date...</b>
<b>==&gt; lvm: Clearing any previously set forwarded ports...</b>
<b>==&gt; lvm: Clearing any previously set network interfaces...</b>
<b>==&gt; lvm: Preparing network interfaces based on configuration...</b>
    lvm: Adapter 1: nat
    lvm: Adapter 2: hostonly
<b>==&gt; lvm: Forwarding ports...</b>
    lvm: 22 (guest) =&gt; 2222 (host) (adapter 1)
<b>==&gt; lvm: Running &apos;pre-boot&apos; VM customizations...</b>
<b>==&gt; lvm: Booting VM...</b>
<b>==&gt; lvm: Waiting for machine to boot. This may take a few minutes...</b>
    lvm: SSH address: 127.0.0.1:2222
    lvm: SSH username: vagrant
    lvm: SSH auth method: private key
<b>==&gt; lvm: Machine booted and ready!</b>
<b>==&gt; lvm: Checking for guest additions in VM...</b>
    lvm: No guest additions were detected on the base box for this VM! Guest
    lvm: additions are required for forwarded ports, shared folders, host only
    lvm: networking, and more. If SSH fails on this machine, please install
    lvm: the guest additions and repackage the box to continue.
    lvm: 
    lvm: This is not an error message; everything may continue to work properly,
    lvm: in which case you may ignore this message.
<b>==&gt; lvm: Setting hostname...</b>
<b>==&gt; lvm: Configuring and enabling network interfaces...</b>
<b>==&gt; lvm: Rsyncing folder: /home2/andrey/LVM/ =&gt; /vagrant</b>
<b>==&gt; lvm: Machine already provisioned. Run `vagrant provision` or use the `--provision`</b>
<b>==&gt; lvm: flag to force provisioning. Provisioners marked to run always will still run.</b>
[andrey@localhost LVM]$ vagrant ssh
Last login: Thu Aug 13 13:38:20 2020 from 10.0.2.2
[vagrant@lvm ~]$ sudo -s
[root@lvm vagrant]# script -a
Script started, file is typescript
[root@lvm vagrant]# lsblk
NAME                    MAJ:MIN RM  SIZE RO TYPE MOUNTPOINT
sda                       8:0    0   40G  0 disk 
├─sda1                    8:1    0    1M  0 part 
├─sda2                    8:2    0    1G  0 part /boot
└─sda3                    8:3    0   39G  0 part 
  ├─VolGroup00-LogVol01 253:1    0  1.5G  0 lvm  [SWAP]
  └─VolGroup00-LogVol00 253:2    0 37.5G  0 lvm  
sdb                       8:16   0   10G  0 disk 
└─vg_root-lv_root       253:0    0   10G  0 lvm  /
sdc                       8:32   0    2G  0 disk 
sdd                       8:48   0    1G  0 disk 
sde                       8:64   0    1G  0 disk 
[root@lvm vagrant]# lvremote /dev/VolGroup00/LogVol00
bash: lvremote: command not found
[root@lvm vagrant]# lvremove /dev/VolGroup00/LogVol00
Do you really want to remove active logical volume VolGroup00/LogVol00? [y/n]: y
  Logical volume &quot;LogVol00&quot; successfully removed
[root@lvm vagrant]# lvcreate -n VolGroup00/LogVol00 -L 8G /dev/VolGroup00
WARNING: xfs signature detected on /dev/VolGroup00/LogVol00 at offset 0. Wipe it? [y/n]: y
  Wiping xfs signature on /dev/VolGroup00/LogVol00.
  Logical volume &quot;LogVol00&quot; created.
[root@lvm vagrant]# mkfs.xfs /dev/VolGroup00/LogVol00
meta-data=/dev/VolGroup00/LogVol00 isize=512    agcount=4, agsize=524288 blks
         =                       sectsz=512   attr=2, projid32bit=1
         =                       crc=1        finobt=0, sparse=0
data     =                       bsize=4096   blocks=2097152, imaxpct=25
         =                       sunit=0      swidth=0 blks
naming   =version 2              bsize=4096   ascii-ci=0 ftype=1
log      =internal log           bsize=4096   blocks=2560, version=2
         =                       sectsz=512   sunit=0 blks, lazy-count=1
realtime =none                   extsz=4096   blocks=0, rtextents=0
[root@lvm vagrant]# mount /dev/VolGroup00/LogVol00 /mnt
[root@lvm vagrant]# xfsdump -J - /dev/vg_root/lv_root |xfsrestore -J - /mnt
xfsdump: using file dump (drive_simple) strategy
xfsdump: version 3.1.7 (dump format 3.0)
xfsdump: level 0 dump of lvm:/
xfsdump: dump date: Thu Aug 13 13:57:48 2020
xfsdump: session id: 7ad6d0e3-10a6-45da-9b33-1082978a0e9e
xfsdump: session label: &quot;&quot;
xfsrestore: using file dump (drive_simple) strategy
xfsrestore: version 3.1.7 (dump format 3.0)
xfsrestore: searching media for dump
xfsdump: ino map phase 1: constructing initial dump list
xfsdump: ino map phase 2: skipping (no pruning necessary)
xfsdump: ino map phase 3: skipping (only one dump stream)
xfsdump: ino map construction complete
xfsdump: estimated dump size: 737971584 bytes
xfsdump: creating dump session media file 0 (media 0, file 0)
xfsdump: dumping ino map
xfsdump: dumping directories
xfsrestore: examining media file 0
xfsrestore: dump description: 
xfsrestore: hostname: lvm
xfsrestore: mount point: /
xfsrestore: volume: /dev/mapper/vg_root-lv_root
xfsrestore: session time: Thu Aug 13 13:57:48 2020
xfsrestore: level: 0
xfsrestore: session label: &quot;&quot;
xfsrestore: media label: &quot;&quot;
xfsrestore: file system id: cfe9aaf8-84d0-4d8b-9303-646fd1b2d8af
xfsrestore: session id: 7ad6d0e3-10a6-45da-9b33-1082978a0e9e
xfsrestore: media id: af3c8151-dace-4d2d-b3ba-b4b50e0601a7
xfsrestore: searching media for directory dump
xfsrestore: reading directories
xfsdump: dumping non-directory files
xfsrestore: 2702 directories and 23620 entries processed
xfsrestore: directory post-processing
xfsrestore: restoring non-directory files
xfsdump: ending media file
xfsdump: media file size 715033120 bytes
xfsdump: dump size (non-dir files) : 701866608 bytes
xfsdump: dump complete: 17 seconds elapsed
xfsdump: Dump Status: SUCCESS
xfsrestore: restore complete: 18 seconds elapsed
xfsrestore: Restore Status: SUCCESS
[root@lvm vagrant]# for i in /proc/ /sys/ /dev/ /run/ /boot/; do mount --bind $i /mnt/$i; done
[root@lvm vagrant]# chroot /mnt/
[root@lvm /]# grub2-mkconfig -o /boot/grub2/grub.cfg
Generating grub configuration file ...
Found linux image: /boot/vmlinuz-3.10.0-862.2.3.el7.x86_64
Found initrd image: /boot/initramfs-3.10.0-862.2.3.el7.x86_64.img
done
[root@lvm /]# cd /boot ; for i in `ls initramfs-*img`; do dracut -v $i `echo $i|sed &quot;s/initramfs-//g; s/.img//g&quot;` --force; done
Executing: /sbin/dracut -v initramfs-3.10.0-862.2.3.el7.x86_64.img 3.10.0-862.2.3.el7.x86_64 --force
dracut module &apos;busybox&apos; will not be installed, because command &apos;busybox&apos; could not be found!
dracut module &apos;crypt&apos; will not be installed, because command &apos;cryptsetup&apos; could not be found!
dracut module &apos;dmraid&apos; will not be installed, because command &apos;dmraid&apos; could not be found!
dracut module &apos;dmsquash-live-ntfs&apos; will not be installed, because command &apos;ntfs-3g&apos; could not be found!
dracut module &apos;multipath&apos; will not be installed, because command &apos;multipath&apos; could not be found!
dracut module &apos;busybox&apos; will not be installed, because command &apos;busybox&apos; could not be found!
dracut module &apos;crypt&apos; will not be installed, because command &apos;cryptsetup&apos; could not be found!
dracut module &apos;dmraid&apos; will not be installed, because command &apos;dmraid&apos; could not be found!
dracut module &apos;dmsquash-live-ntfs&apos; will not be installed, because command &apos;ntfs-3g&apos; could not be found!
dracut module &apos;multipath&apos; will not be installed, because command &apos;multipath&apos; could not be found!
*** Including module: bash ***
*** Including module: nss-softokn ***
*** Including module: i18n ***
*** Including module: drm ***
*** Including module: plymouth ***
*** Including module: dm ***
Skipping udev rule: 64-device-mapper.rules
Skipping udev rule: 60-persistent-storage-dm.rules
Skipping udev rule: 55-dm.rules
*** Including module: kernel-modules ***
Omitting driver floppy
*** Including module: lvm ***
Skipping udev rule: 64-device-mapper.rules
Skipping udev rule: 56-lvm.rules
Skipping udev rule: 60-persistent-storage-lvm.rules
*** Including module: qemu ***
*** Including module: resume ***
*** Including module: rootfs-block ***
*** Including module: terminfo ***
*** Including module: udev-rules ***
Skipping udev rule: 40-redhat-cpu-hotplug.rules
Skipping udev rule: 91-permissions.rules
*** Including module: biosdevname ***
*** Including module: systemd ***
*** Including module: usrmount ***
*** Including module: base ***
*** Including module: fs-lib ***
*** Including module: shutdown ***
*** Including modules done ***
*** Installing kernel module dependencies and firmware ***
*** Installing kernel module dependencies and firmware done ***
*** Resolving executable dependencies ***
*** Resolving executable dependencies done***
*** Hardlinking files ***
*** Hardlinking files done ***
*** Stripping files ***
*** Stripping files done ***
*** Generating early-microcode cpio image contents ***
*** No early-microcode cpio image needed ***
*** Store current command line parameters ***
*** Creating image file ***
*** Creating image file done ***
*** Creating initramfs image file &apos;/boot/initramfs-3.10.0-862.2.3.el7.x86_64.img&apos; done ***
[root@lvm boot]# pvcreate /dev/sdc /dev/sdd
  Physical volume &quot;/dev/sdc&quot; successfully created.
  Physical volume &quot;/dev/sdd&quot; successfully created.
[root@lvm boot]# vgcreate vg_var /dev/sdc /dev/sdd
  Volume group &quot;vg_var&quot; successfully created
[root@lvm boot]# lvcreate -L 950M -m1 -n lv_var vg_var
  Rounding up size to full physical extent 952.00 MiB
  Logical volume &quot;lv_var&quot; created.
[root@lvm boot]# mkfs.ext4 /dev/vg_var/lv_var
mke2fs 1.42.9 (28-Dec-2013)
Filesystem label=
OS type: Linux
Block size=4096 (log=2)
Fragment size=4096 (log=2)
Stride=0 blocks, Stripe width=0 blocks
60928 inodes, 243712 blocks
12185 blocks (5.00%) reserved for the super user
First data block=0
Maximum filesystem blocks=249561088
8 block groups
32768 blocks per group, 32768 fragments per group
7616 inodes per group
Superblock backups stored on blocks: 
	32768, 98304, 163840, 229376

Allocating group tables: done                            
Writing inode tables: done                            
Creating journal (4096 blocks): done
Writing superblocks and filesystem accounting information: done

[root@lvm boot]# mount /dev/vg_var/lv_var /mnt
[root@lvm boot]# mount |grep mnt
/dev/mapper/vg_var-lv_var on /<font color="#CB4B16"><b>mnt</b></font> type ext4 (rw,relatime,seclabel,data=ordered)
[root@lvm boot]# cp -aR /var/* /mnt/
[root@lvm boot]# mkdir /tmp/oldvar &amp;&amp; mv /var/* /tmp/oldvar
[root@lvm boot]# umount /mnt
[root@lvm boot]# mount /dev/vg_var/lv_var /var
[root@lvm boot]# echo &quot;`blkid | grep var: | awk &apos;{print $2}&apos;` /var ext4 defaults 0 0&quot; &gt;&gt; /etc/fstab
[root@lvm boot]# exit
[root@lvm vagrant]# exit
exit
Script done, file is typescript
[root@lvm vagrant]# exit
exit
[vagrant@lvm ~]$ exit
logout
Connection to 127.0.0.1 closed.
[andrey@localhost LVM]$ vagrant halp
Usage: vagrant [options] &lt;command&gt; [&lt;args&gt;]

    -h, --help                       Print this help.

Common commands:
     box             manages boxes: installation, removal, etc.
     cloud           manages everything related to Vagrant Cloud
     destroy         stops and deletes all traces of the vagrant machine
     global-status   outputs status Vagrant environments for this user
     halt            stops the vagrant machine
     help            shows the help for a subcommand
     init            initializes a new Vagrant environment by creating a Vagrantfile
     login           
     package         packages a running vagrant environment into a box
     plugin          manages plugins: install, uninstall, update, etc.
     port            displays information about guest port mappings
     powershell      connects to machine via powershell remoting
     provision       provisions the vagrant machine
     push            deploys code in this environment to a configured destination
     rdp             connects to machine via RDP
     reload          restarts vagrant machine, loads new Vagrantfile configuration
     resume          resume a suspended vagrant machine
     snapshot        manages snapshots: saving, restoring, etc.
     ssh             connects to machine via SSH
     ssh-config      outputs OpenSSH valid configuration to connect to the machine
     status          outputs status of the vagrant machine
     suspend         suspends the machine
     up              starts and provisions the vagrant environment
     upload          upload to machine via communicator
     validate        validates the Vagrantfile
     version         prints current and latest Vagrant version
     winrm           executes commands on a machine via WinRM
     winrm-config    outputs WinRM configuration to connect to the machine

For help on any individual command run `vagrant COMMAND -h`

Additional subcommands are available, but are either more advanced
or not commonly used. To see all subcommands, run the command
`vagrant list-commands`.
        --[no-]color                 Enable or disable color output
        --machine-readable           Enable machine readable output
    -v, --version                    Display Vagrant version
        --debug                      Enable debug output
        --timestamp                  Enable timestamps on log output
        --debug-timestamp            Enable debug output with timestamps
        --no-tty                     Enable non-interactive output

[andrey@localhost LVM]$ vagrant halt
<b>==&gt; lvm: Attempting graceful shutdown of VM...</b>
[andrey@localhost LVM]$ vagrant up
Bringing machine &apos;lvm&apos; up with &apos;virtualbox&apos; provider...
<b>==&gt; lvm: Checking if box &apos;centos/7&apos; version &apos;1804.02&apos; is up to date...</b>
<b>==&gt; lvm: Clearing any previously set forwarded ports...</b>
<b>==&gt; lvm: Clearing any previously set network interfaces...</b>
<b>==&gt; lvm: Preparing network interfaces based on configuration...</b>
    lvm: Adapter 1: nat
    lvm: Adapter 2: hostonly
<b>==&gt; lvm: Forwarding ports...</b>
    lvm: 22 (guest) =&gt; 2222 (host) (adapter 1)
<b>==&gt; lvm: Running &apos;pre-boot&apos; VM customizations...</b>
<b>==&gt; lvm: Booting VM...</b>
<b>==&gt; lvm: Waiting for machine to boot. This may take a few minutes...</b>
    lvm: SSH address: 127.0.0.1:2222
    lvm: SSH username: vagrant
    lvm: SSH auth method: private key
<b>==&gt; lvm: Machine booted and ready!</b>
<b>==&gt; lvm: Checking for guest additions in VM...</b>
    lvm: No guest additions were detected on the base box for this VM! Guest
    lvm: additions are required for forwarded ports, shared folders, host only
    lvm: networking, and more. If SSH fails on this machine, please install
    lvm: the guest additions and repackage the box to continue.
    lvm: 
    lvm: This is not an error message; everything may continue to work properly,
    lvm: in which case you may ignore this message.
<b>==&gt; lvm: Setting hostname...</b>
<b>==&gt; lvm: Configuring and enabling network interfaces...</b>
<b>==&gt; lvm: Rsyncing folder: /home2/andrey/LVM/ =&gt; /vagrant</b>
<b>==&gt; lvm: Machine already provisioned. Run `vagrant provision` or use the `--provision`</b>
<b>==&gt; lvm: flag to force provisioning. Provisioners marked to run always will still run.</b>
[andrey@localhost LVM]$ vagrant ssh
Last login: Thu Aug 13 13:52:55 2020 from 10.0.2.2
[vagrant@lvm ~]$ sudo -s
[root@lvm vagrant]# script -a
Script started, file is typescript
[root@lvm vagrant]# lvremove /dev/vg_root/lv_root
Do you really want to remove active logical volume vg_root/lv_root? [y/n]: y
  Logical volume &quot;lv_root&quot; successfully removed
[root@lvm vagrant]# vgremove /dev/vg_root
  Volume group &quot;vg_root&quot; successfully removed
[root@lvm vagrant]# pvremove /dev/sdb
  Labels on physical volume &quot;/dev/sdb&quot; successfully wiped.
[root@lvm vagrant]# lvcreate -n LogVol_Home -L 2G /dev/VolGroup00
  Logical volume &quot;LogVol_Home&quot; created.
[root@lvm vagrant]# mkfs.xfs /dev/VolGroup00/LogVol_Home
meta-data=/dev/VolGroup00/LogVol_Home isize=512    agcount=4, agsize=131072 blks
         =                       sectsz=512   attr=2, projid32bit=1
         =                       crc=1        finobt=0, sparse=0
data     =                       bsize=4096   blocks=524288, imaxpct=25
         =                       sunit=0      swidth=0 blks
naming   =version 2              bsize=4096   ascii-ci=0 ftype=1
log      =internal log           bsize=4096   blocks=2560, version=2
         =                       sectsz=512   sunit=0 blks, lazy-count=1
realtime =none                   extsz=4096   blocks=0, rtextents=0
[root@lvm vagrant]# mount /dev/VolGroup00/LogVol_Home /mnt/
[root@lvm vagrant]# cp -aR /home/* /mnt/
[root@lvm vagrant]# rm -rf /home/*
[root@lvm vagrant]# umount /mnt
[root@lvm vagrant]# mount /dev/VolGroup00/LogVol_Home /home/
[root@lvm vagrant]# echo &quot;`blkid | grep Home | awk &apos;{print $2}&apos;` /home xfs defaults 0 0&quot; &gt;&gt; /etc/fstab
[root@lvm vagrant]# touch/home/file{1..20}
bash: touch/home/file1: No such file or directory
[root@lvm vagrant]# touch /home/file{1..20}
[root@lvm vagrant]# ls -al /home
total 0
drwxr-xr-x.  3 root    root    292 Aug 13 14:16 <font color="#005FFF">.</font>
drwxr-xr-x. 18 root    root    239 Aug 13 13:58 <font color="#005FFF">..</font>
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file1
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file10
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file11
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file12
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file13
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file14
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file15
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file16
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file17
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file18
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file19
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file2
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file20
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file3
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file4
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file5
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file6
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file7
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file8
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file9
drwx------.  3 vagrant vagrant  92 Aug 13 13:38 <font color="#005FFF">vagrant</font>
[root@lvm vagrant]# lvcreate -L 100MB -s -n home_snap /dev/VolGroup00/LogVol_Home
  Rounding up size to full physical extent 128.00 MiB
  Logical volume &quot;home_snap&quot; created.
[root@lvm vagrant]# rm -f /home/file{11..20}
[root@lvm vagrant]# ls -al /home
total 0
drwxr-xr-x.  3 root    root    152 Aug 13 14:18 <font color="#005FFF">.</font>
drwxr-xr-x. 18 root    root    239 Aug 13 13:58 <font color="#005FFF">..</font>
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file1
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file10
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file2
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file3
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file4
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file5
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file6
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file7
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file8
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file9
drwx------.  3 vagrant vagrant  92 Aug 13 13:38 <font color="#005FFF">vagrant</font>
[root@lvm vagrant]# umount /home
[root@lvm vagrant]# lvconvert --merge /dev/VolGroup00/home_snap
  Merging of volume VolGroup00/home_snap started.
  VolGroup00/LogVol_Home: Merged: 100.00%
[root@lvm vagrant]# mount /home
[root@lvm vagrant]# ls -al /home
total 0
drwxr-xr-x.  3 root    root    292 Aug 13 14:16 <font color="#005FFF">.</font>
drwxr-xr-x. 18 root    root    239 Aug 13 13:58 <font color="#005FFF">..</font>
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file1
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file10
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file11
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file12
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file13
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file14
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file15
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file16
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file17
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file18
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file19
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file2
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file20
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file3
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file4
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file5
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file6
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file7
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file8
-rw-r--r--.  1 root    root      0 Aug 13 14:16 file9
drwx------.  3 vagrant vagrant  92 Aug 13 13:38 <font color="#005FFF">vagrant</font>
[root@lvm vagrant]# exit
Script done, file is typescript
[root@lvm vagrant]# exit
exit
</pre>
