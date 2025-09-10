
##### Host Os : Parrot Security 
##### Vulnerable machine : [Kioptrix Level 1](https://www.vulnhub.com/entry/kioptrix-level-1-1,22/)


## Setting VM:

### **disable KVM kernel extension**

```bash
sudo rmmod kvm_intel
sudo rmmod kvm
lsmod | grep kvm
```

- Finding the Ip address of the machine 

