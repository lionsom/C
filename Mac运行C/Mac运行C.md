[如何在 mac 电脑上写 C？](https://www.zhihu.com/question/304541222/answer/547218189)

[s](https://www.zhihu.com/education/video-course/1487069370132602880?section_id=1487069414969798656)

https://www.bilibili.com/video/BV1Bh4y1q7Nt/?spm_id_from=333.337.search-card.all.click&vd_source=dc55c355e9f5b6174832aacfb5d8b6aa



# 一、运行环境

IDE:  **Visual Studio Code，不是Visual Studio**



## Mac安装C/C++编译器

在Mac上，我用的C/C++编译器是clang，相比于gcc，clang运行更快，能在程序出现语法错误编译失败时提供更加明确的错误信息和处理建议（这点我在Windows上用gcc时深有体会，gcc给的信息总是非常的confusing）。

先检查你的Mac是否自带clang编译器，执行`clang -v`或者`clang --version`，没有出现clang的版本号则需要安装clang，执行：

```sh
# 安装命令行工具
$ xcode-select --install

# 查看clang版本
$ clang -v    
$ clang --version
Apple clang version 14.0.0 (clang-1400.0.29.202)
Target: x86_64-apple-darwin22.3.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin
```





## 扩展

在VS Code里安装以下拓展（括号里的是作者）

- C/C++(Microsoft)
- Code Runner(Jun Han)











