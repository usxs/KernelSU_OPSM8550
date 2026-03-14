## 编译指南 (README)

> **重要提示：请务必先阅读本说明**
> * **分支支持：** `main` 分支仅支持 **Android 16**。
> 
> 

### 使用步骤：

1. **Fork 本仓库：** 将本仓库 Fork 到您的账号下（使用前请务必确认已同步至最新代码）。
2. **前往 Actions 页面：** 在您 Fork 后的仓库中，点击顶部的 **Actions** 选项卡。
3. **选择 Clang 版本：** * 针对 **Android 16 QPR0**：请选择 `clang-r547379`。
* 针对 **Android 16 QPR2**：请选择 `clang-r563880` 或 `r563880c`。


4. **选择内核源码 (Kernel Source)：** * 如果您使用的是 PixelOS，请选择 `OnePlus12R-development`。
5. **输入内核分支 (Kernel Branch)：** * 请在您的内核源码仓库中确认分支名称。例如：LineageOS 使用 `lineage-23.2`，crDroid 使用 `16.0`，PixelOS 使用 `sixteen-qpr2`。
6. **选择 KernelSU 及其衍生版本：** * 根据需求选择所需的 KernelSU 或其 Fork 版本。
* *注：SUSFS 目前可能存在兼容性问题（由 simonpunk 维护/控制）。*



### 相关资源：

* **KSU 工具包 (ksu toolkit):** [点击访问](https://github.com/backslashxx/ksu_toolkit)
* **Inferno 编译版本 (包含 ksu, ksunext, sukisu):** [点击访问](https://github.com/inferno0230/kernel_oneplus_sm8550-CI)
