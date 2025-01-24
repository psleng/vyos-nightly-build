[![VyOS nightly build](https://github.com/vyos/vyos-nightly-build/actions/workflows/nightly-build.yml/badge.svg)](https://github.com/vyos/vyos-nightly-build/actions/workflows/nightly-build.yml)

# About

Scheduled VyOS image build - once per day (currently 00:00 UTC).

Successfull builds will be published as GitHub Release and linked on the
official download page https://vyos.net/get/nightly-builds/

## How to check an image signature

Download signature public key

```
wget https://github.com/vyos/vyos-nightly-build/raw/refs/heads/current/minisign.pub
```

Download ISO image and signature file (example):

```
wget https://github.com/vyos/vyos-nightly-build/releases/download/1.5-rolling-202312191154/vyos-1.5-rolling-202312191154-amd64.iso
wget https://github.com/vyos/vyos-nightly-build/releases/download/1.5-rolling-202312191154/vyos-1.5-rolling-202312191154-amd64.iso.minisig
```

Verify signature

```
minisign -Vm vyos-1.5-rolling-202312191154-amd64.iso
```

