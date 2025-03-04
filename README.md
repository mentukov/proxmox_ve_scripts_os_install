### For proxmox - install VM cloud-init script
... just run it in proxmox shell ...
### Ubuntu 20.04
```shell
bash -c "$(wget -qLO - https://raw.githubusercontent.com/mentukov/pve_bash_script/main/ubuntu_2004.sh)"
```

### Ubuntu 24.04
```shell
bash -c "$(wget -qLO - https://raw.githubusercontent.com/mentukov/pve_bash_script/main/ubuntu_2404.sh)"
```

### Alma Linux 9
```shell
bash -c "$(wget -qLO - https://raw.githubusercontent.com/mentukov/pve_bash_script/main/alma.sh)"
```

### VE post install
```shell
bash -c "$(wget -qLO - https://raw.githubusercontent.com/mentukov/proxmox_ve_scripts_os_install/refs/heads/main/ve_post_install.sh)"
```
