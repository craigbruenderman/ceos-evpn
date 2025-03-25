# ceos-evpn
Arista CEOS-based EVPB lab using ContainerLab

# Installing

* Install docker
* Optional: Install vrnetlab for containerizing images
```git clone <https://github.com/hellt/vrnetlab> && cd vrnetlab```
* Fetch CEOS 4.33.2F VMDK from Arista's software downloads
* Import container image and save it under ceos:4.32.0F name
```docker import cEOS64-lab-4.33.2F.tar.xz ceos:4.33.2F```

# Using

* ```clab deploy -t topology.yml```
* SSH to devices and do your thing
