# 角色建模资源

请在本仓库的 **Releases** 页面下载 建模资源压缩包，解压后再按下面步骤在 Unity 中打开查看。

## 如何在 Unity 里打开查看

1. 先保留整个 `character_model` 文件夹结构，不要只单独拷贝某个 `Assets` 文件夹。
2. 打开 **Unity Hub**。
3. 点击 **Projects / 项目** 里的 **Add / Open / Add project from disk**。
4. 选择某个角色对应的 `ExportedProject` 文件夹，例如：

   ```text
   after/A_character_after/aisha/ExportedProject
   ```

   注意：要选择 `ExportedProject` 这个文件夹本身，不是 `ProjectVersion.txt`，也不是里面的 `Assets` 文件夹。

5. 工程打开后，在 Unity 的 Project 面板里看：

   ```text
   Assets/res/assets/player/<角色名>/
   ```

   通常主要模型是 `model.prefab` 或 `model_0.prefab`；贴图/材质也在同目录或子目录里。

6. 2019 版本或 2022 版本的 Unity 均可打开；如果 Unity 提示项目版本不一致，可以选择继续打开。

## 索引说明

- `Unity工程目录`：角色的 `ExportedProject` 文件夹，Unity Hub 应该打开这个目录。
- `角色资源文件`：通常是该角色目录里的 `model.prefab`，适合在 VS Code 里快速定位资源。
- `before data入口`：原始 data 文件。
- 如果 Markdown 预览里点目录链接不跳转，可以复制表格里的相对路径，在 Unity Hub 的 Add/Open 里手动选择。
