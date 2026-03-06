## 目标
- 学习
- 流程掌握
- 魔改
- patch

### 编译问题
- 从哪里下载的
    - build/slang-build/webgpu_dawn-windows-x64
    - build/slang-build/slang-tint-windows-x64
    - build/slang-build/slang-2025.20-windows-x86_64

### git patch
- git cherry -v
    - 查看 获取git中没有上传的commit数量
    - 顺序从旧到新显示

### vscode 配置
- 配置变量 CMake Cache Editor
    - VUK_USE_SLANG
```json
{
    "cmake.generator": "Ninja"
}
```

