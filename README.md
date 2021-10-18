# local_manifests

## ResurrectionRemix

```
repo init -u https://github.com/ResurrectionRemix/platform_manifest.git -b nougat
```

### android_packages_apps_ManagedProvisioning 使用旧分支
```
cd packages/apps/ManagedProvisioning
git checkout 4ec1d12410e3e2acd8f79e184a6ee9c23266b070
```

### android_packages_providers_DownloadProvider 使用旧分支
```
cd packages/providers/DownloadProvider
git checkout 82b1346ceb3c9212333e7f956d81596b13f99d2e
```

### 打补丁，执行 apply.sh
```
cd device/meizu/m86/patches
./apply.sh
```

### 然后正常编译
