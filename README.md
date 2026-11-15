# Xiaomi Mi 3/4 (cancro) Nura (postmarketOS) 自建镜像

Archived 设备 (armhf→armv7 改造) 的 CI 构建。详情见本地 D:\小米4刷机\README.md。

- 设备包来源: pmaports `device/archived/` (armhf) → 已改 armv7
- 内核: LineageOS cancro 3.4.0 (commit b263a89), sha512 已验证
- 构建: pmbootstrap (gitlab.nura.eco main) + Nura edge 通道 armv7 二进制仓库
- 产物: Actions Artifact `cancro-images` (boot.img + rootfs.img)

手动触发: Actions → build-cancro → Run workflow
