# Local Manifests for Redmi Note 10 #


```bash

# Grab Local Manifest
curl -o .repo/local_manifests/vanilla_manifests.xml https://raw.githubusercontent.com/boedhack/local_manifest/master/local_manifest.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```
