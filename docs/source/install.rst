Install
=====

On each node (e.g., VMs), you need to install the required package first. You can refer to the criu project page for detailed information. Here is an example of the packages needed for Ubuntu 20.04:

```
sudo apt install -y libprotobuf-dev libprotobuf-c-dev protobuf-c-compiler \
    protobuf-compiler python-protobuf pkg-config libnl-3-dev libnet-dev \
    libcap-dev libbsd-dev python3-pip cmake
```