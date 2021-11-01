## How to use this?

```bash
cd <whatever your source is>
git clone git@github.com:ProtonAOSP-lavender/android_local_manifest.git .repo/private_manifest
mkdir -p .repo/local_manifests
ln -s $(pwd)/.repo/private_manifest/lavender.xml .repo/local_manifests/lavender.xml
```
