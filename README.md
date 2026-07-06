# 证件校验码验证

离线工具，校验：

- **18 位中国居民身份证**末位校验码（GB 11643 MOD 11-2）
- **护照 MRZ 第二行**各字段校验位（ICAO Doc 9303）

**在线访问：** https://abudhabi-realestate.github.io/passport-mrz-check/

## 本地使用

双击 `证件校验码验证.html` 或 `index.html`，用浏览器打开即可，无需安装、可离线使用。

## 护照 MRZ 用法

1. 打开页面，切换到「护照 MRZ 校验码」
2. 粘贴护照机读区**最后一行**（44 字符）
3. 点击「验证」，查看护照号、出生日期、有效期等校验位是否合法

## GitHub Pages 部署

1. 新建公开仓库（例如 `passport-mrz-check`）
2. 上传 `index.html` 和 `README.md`
3. **Settings → Pages → Branch**：`main`，文件夹 **`/ (root)`**
4. 访问 `https://abudhabi-realestate.github.io/<仓库名>/`

本工具仅校验算法是否正确，不验证号码是否真实签发。
