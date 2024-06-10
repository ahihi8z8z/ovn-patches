ovn-patches
========
Modifies for ovn to paper

Usage
-----
```
git clone https://github.com/ovn-org/ovn.git
cd ovn
branch-22.03
git checkout 47d61c5e7bee9f7e295dc175ef9ab25d1f65745f
wget https://raw.githubusercontent.com/ahihi8z8z/ovn-patches/branch-22.03/bandwidth_reserver.patch
git apply bandwidth_reserver.patch
```
