# 文件加密解密工具使用指南
![License](https://img.shields.io/badge/License-MIT-green)  
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)  
## 工具说明
- 🔒 `加密.exe`：一键加密桌面所有文件
- 🔓 `解密.exe`：一键还原被加密的文件

## 使用步骤

### 加密操作
1. 双击运行`加密.exe`
2. 静默完成以下操作：
   - 自动加密桌面所有文件（包括子文件夹）
   - 在系统目录生成`C:\virus\DECRYPTION_KEY.json`密钥文件

### 解密操作  
1. 双击运行`解密.exe`  
2. 静默完成以下操作：
   - 自动识别并解密所有加密文件
   - 解密完成后自动删除密钥文件

## 注意事项
⚠️ **重要提示**：
- 加密前请确保记住密码（默认为`default_password`）
- 请勿手动删除`C:\virus\DECRYPTION_KEY.json`文件
- 建议加密前备份重要文件
- 部分安全软件可能拦截，使用时请暂时关闭防护

## 常见问题
❓ **如何修改密码？**  
直接运行`加密.exe 新密码`（带参数运行）

❓ **解密失败怎么办？**  
检查是否保留着密钥文件，并使用相同密码重试

❓ **加密后文件后缀会变吗？**  
所有加密文件会自动追加`.enc`后缀
