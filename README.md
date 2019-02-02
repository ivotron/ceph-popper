# Popper pipelines for Ceph

## Prerequisites
* Popper  
* Python 3  
* CloudLab credentials and put into environmental variables:  
  * CLOUDLAB_USER
  * CLOUDLAB_PASSWORD
  * CLOUDLAB_PROJECT
  * CLOUDLAB_PUBKEY_PATH
  * CLOUDLAB_CERT_PATH ([See here](https://geni-lib.readthedocs.io/en/latest/intro/creds/cloudlab.html))

## Installation 
* Clone the repo:  
``` 
git clone https://github.com/msouppe/Ceph.git
```
  
* Navigate to `Ceph/`  
  
* Run the program:  
```bash
poppper run
```
  
## Pipeline  
* `setup.sh`: Allocate resources (nodes) from CloudLab  
* `run.sh`: Deploy ceph-ansible and deploy CBT (Ceph Benchmarking Tool)
* `analyze-results.sh`:   
* `teardown.sh`:   

## Output
