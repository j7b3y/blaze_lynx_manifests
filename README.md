```bash
repo init -u https://github.com/crdroidandroid/android.git -b 15.0 --git-lfs --depth=1
git clone https://github.com/j7b3y/local_manifests .repo/local_manifests -b cr11
repo sync -j`nproc --all` -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune
```
