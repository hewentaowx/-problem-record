## 有时候VSCode会出现更新失败的问题

比如: vscodeCould not create temporary directory: 权限被拒绝

解决方式: sudo chown $USER ~/Library/Caches/com.microsoft.VSCode.ShipIt/ 