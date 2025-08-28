# fedora-my4ng
RPM package repository for Fedora

### Package list:

  - [openrazer w/ akmod](https://github.com/openrazer/openrazer)
    - akmod-openrazer
    - openrazer
    - openrazer-daemon
    - python3-openrazer
  - [xwayland-satellite w/ systemd service](https://github.com/Supreeeme/xwayland-satellite)
    - xwayland-satellite
  - [mesa](https://gitlab.freedesktop.org/mesa/mesa/)
    - mesa-dri-drivers
    - mesa-filesystem
    - mesa-libEGL
    - mesa-libEGL-devel
    - mesa-libgbm
    - mesa-libgbm-devel
    - mesa-libGL
    - mesa-libGL-devel
    - mesa-libOpenCL
    - mesa-libOpenCL-devel
    - mesa-tools
    - mesa-va-drivers
    - mesa-vdpau-drivers
    - mesa-vulkan-drivers

### Install [repo file](https://my4ng.dev/repos/fedora-my4ng.repo):

  - DNF5: `sudo dnf config-manager addrepo --from-repofile=https://my4ng.dev/repos/fedora-my4ng.repo`
  - Manual: `sudo curl https://my4ng.dev/repos/fedora-my4ng.repo -o /etc/yum.repos.d/fedora-my4ng.repo`

### GPG signing key fingerprint:

```
ssb   ed25519 2024-11-03 [S] [expires: 2027-11-03]
      D113BEB56A961CB400B9147F2D46C1C2D0F41F63
```

### Issues:

Please direct all issues and suggestions regarding the repository or any package in it to [Issues](https://github.com/my4ng/fedora-my4ng/issues)

### Licenses:

This is _only_ a repository of built RPM packages for redistribution. Consult the respective project licenses for further details.
