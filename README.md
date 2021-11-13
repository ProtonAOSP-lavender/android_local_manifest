# ProtonAOSP-lavender

```bash
$ cd WORKSPACE
$ git clone git@github.com:ProtonAOSP-lavender/android_local_manifest.git .repo/private_manifest
$ mkdir -p .repo/local_manifests
$ ln -s $(pwd)/.repo/private_manifest/lavender.xml .repo/local_manifests/lavender.xml
# Let Repo take care of all the hard work
#
# The -j# option specifies the number of concurrent download threads to run.
# 4 threads is a good number for most internet connections.
# You may need to adjust this value if you have a particularly slow connection.
$ repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```
