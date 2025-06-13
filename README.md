# Speech Signal Process Code Repository
获取代码
由于仓库包含大文件，请使用 ​​Git + LFS​​ 克隆：

git clone git@github.com:Loueor/Speech_Signal_Process_Code.git
cd Speech_Signal_Process_Code
文件合并说明
项目中的 project.zip 已拆分为多个分块文件，合并方法：

## 查看分块文件列表
```bash
ls -lh project_part_*
```
## 合并文件（确保磁盘有足够空间）
```bash
cat project_part_* > project.zip
```
## 验证文件完整性
```bash
md5sum project.zip
```
✅ ​​正确校验和​​：24dae8ac3e251cb431d1833018827bbb

目录结构
```
├── src/                 # 核心源代码
├── docs/                # 项目文档
├── project_part_aa      # 分块文件1 (1.5GB)
├── project_part_ab      # 分块文件2 (1.5GB)
└── ...                  # 其他分块文件
```
注意事项
​​合并前​​ 检查磁盘剩余空间（需 ≥26GB）
若下载中断，可重新运行 git lfs pull
