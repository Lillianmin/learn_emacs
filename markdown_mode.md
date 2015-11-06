# emacs markdown-mode
- 添加emacs markdown 插件
+ 安装markdown-mode插件
   - sudo apt-get install markdown
   - sudo apt-get install emacs-googies-el
   - 将下载的markdown-mode放在~/.emacs.d/下面
+ 配置.emacs默认使用markdown-mode打开.md,.markdown文件
```
(autoload 'markdown-mode "markdown-mode"
   "Major mode for editing Markdown files" t)
   (add-to-list 'auto-mode-alist '("\\.markdown\\'" . markdown-mode))
   (add-to-list 'auto-mode-alist '("\\.md\\'" . markdown-mode))
```
+ 参考
[http://jblevins.org/projects/markdown-mode/](markdown-mode)


