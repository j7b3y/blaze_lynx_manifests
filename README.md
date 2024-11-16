```bash
repo init -u https://github.com/crdroidandroid/android.git -b 154.0 --git-lfs
git clone https://github.com/j7b3y/local_manifests .repo/local_manifests -b cr11
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune
```
