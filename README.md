# P1.schdoc (原理图源文件)

本仓库包含由用户提供的 Altium/Protel schematic (.schdoc) 源文件 P1.schdoc。你已授权我将文件提交到仓库。由于我无法在本环境中运行 Altium 来渲染 schdoc，我已把源文件提交并添加本导出说明，建议在有 Altium Designer 的 Windows 机器上导出高分辨率 PNG。

目标输出
- 文件名: schematic-highres.png
- 分辨率: 300 DPI

在 Altium Designer 中导出高分辨率 PNG（推荐步骤）
1. 在 Windows 上用 Altium Designer 打开 P1.schdoc。
2. 菜单: File → Export → Image...
3. 在导出对话框中，选择 PNG 格式。
4. 设置分辨率/DPI 为 300，或指定宽/高像素值（例如宽 4000 px，或按页大小计算）。
5. 取消选中“导出为透明背景”（如果需要白色背景则选择白色背景）。
6. 确认缩放为 100% 并启用矢量/高质量抗锯齿（若有选项）。
7. 保存为 schematic-highres.png 并将文件推送回仓库的根目录（或替换仓库中的占位文件）。

如果你希望我在仓库中创建一个 GitHub Actions workflow 来自动化（在有 Altium 可用的自托管 Windows runner 时可行），我可以添加该 workflow 的模版。
