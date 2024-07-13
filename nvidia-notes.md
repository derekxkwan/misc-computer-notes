# cuda not working
- try deviceQuery from [cuda-samples](https://github.com/NVIDIA/cuda-samples)
    - if it works with sudo but not without
    - check to see if nvidia-current-uvm is loaded
    - if not and loadin fixes it, add nvidia-current-nvm to /etc/modules/nvidia.conf
