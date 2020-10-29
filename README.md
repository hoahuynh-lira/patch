# Hướng Dẫn Patch Checkra1n A10 với A11 iOS 14
by [exploit3d](https://twitter.com/exploit3dguy) 

1. Yêu cầu:
* Bạn phải cài Linux
- Hướng dẫn cài linux song song với Windows: 
<a href="https://thuthuat.taimienphi.vn/cach-cai-ubuntu-song-song-voi-windows-10-8-7-uefi-va-gpt-31617n.aspx
"> 
Cách cài Ubuntu song song với Windows 10, 8, 7 UEFI và GPT</a>
* checkra1n_patch_A10_A11: (<a href="https://github.com/Exploite-d/checkra1n_patch_A10_A11/raw/main/checkra1n_A11_A10_mac.patch">macOS</a>/<a hreff="https://github.com/Exploite-d/checkra1n_patch_A10_A11/raw/main/checkra1n_A10_A11_linux.patch">Linux</a>
* checkra v0.11 Beta: (<a href="https://assets.checkra.in/downloads/macos/d4def982494bc0b99c6df57dc94338c205902aaa8949e9ae046812ed57743ccb/checkra1n%20beta%200.11.0.dmg">macOS</a>/<a href="https://assets.checkra.in/downloads/linux/cli/x86_64/fa08102ba978746ff38fc4c1a0d2e8f231c2cbf79c7ef6d7b504e4683a5b7d05/checkra1n">Linux CLI, x86_64</a>/<a href="https://assets.checkra.in/downloads/linux/cli/arm/d751f4b245bd4071c571654607ca4058e9e7dc4a5fa30639024b6067eebf5c3b/checkra1n">Linux CLI, arm</a>/<a href="https://assets.checkra.in/downloads/linux/cli/arm64/b48774e5d240ce192016a3fa97df7ef855220576f0704c83ed627d092cb2e224/checkra1n">Linux CLI, arm64</a>/<a href="https://assets.checkra.in/downloads/linux/cli/i486/6f3885184dbdb5af4fec8c57e5684f914b9838ce7d6f78db5e9d2687d741b8f1/checkra1n">Linux CLI, i486</a>)
2. Cập nhật và cài patch vào Checkra1n:

 2.1 Đầu tiên bạn mở Terminal và gõ lệnh sau:  "sudo apt install bspatch"
 
 2.2 Tiếp đến bạn gõ lệnh để cài patch vào Checkra1n ( lưu ý gõ " cd ' chọn  thư mục chứa file Checkra1n và file patch'"): "bspatch checkra1n checkra1n_patched 'file patch'"
 
 <img src="https://github.com/hoahuynh-lira/hoahuynh-lira.github.io/raw/master/bspatch.png" width="" height="" />
 + Sau khi cài file patch thành công sẽ xuất hiện file "checkra1n_patched" trong thư mục đã chọn.
 <img src="https://github.com/hoahuynh-lira/hoahuynh-lira.github.io/raw/master/file.png" width="" height="" />
 2.3  bạn phải thiết lập quyền cho Checkra1n: "chmod +x checkra1n-patched"
 <img src="https://github.com/hoahuynh-lira/hoahuynh-lira.github.io/raw/master/chmod.png" width="" height="" />
 2.3  bạn phải thiết lập quyền cho Checkra1n: "chmod +x checkra1n-patched"
 2.4 Tiếp tục gõ lệnh để chạy Checkra1n: "./checkra1n-patched -c" hoặc "./checkra1n --cli"
 <img src="https://github.com/hoahuynh-lira/hoahuynh-lira.github.io/raw/master/checkra1n.png" width="" height="" />
  Chúc bạn thành công!!
