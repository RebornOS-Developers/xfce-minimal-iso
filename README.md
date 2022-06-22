# RebornOS ISO - Xfce Minimal

EXPERIMENTAL: Please contact shivanandvp@rebornos.org

This upstream is [the official releng config of archiso](https://gitlab.archlinux.org/archlinux/archiso/-/tree/master/configs/releng).
This repository has been created using git subtree. Please keep it updated by git merging with latest upstream changes.

## 1. Cloning

In order to download the source code to your local computer for testing, or for development, you can clone from the remote repository using either SSH, or HTTPS. Below are instructions on how to do so using Gitlab hosted code as remote.

### HTTPS

```bash
git clone https://gitlab.com/rebornos-labs/installer-and-iso/iso/xfce-minimal-iso.git   
```

OR

### SSH

```bash
git clone git@gitlab.com:rebornos-labs/installer-and-iso/iso/xfce-minimal-iso.git
```

## (Optional) Clean-up old packages and directories

You usually do not need to do this unless the build fails.
The build process following cleanup is usually slow because it has to start from scratch.
```bash
sh xfce-minimal-iso/scripts/clean.sh
```

## 2. Build

The below script will build the ISO image (and install any prerequisites).

```bash
sh xfce-minimal-iso/scripts/build.sh
```

## 3. Output

Check the `xfce-minimal-iso/output/` directory