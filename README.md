为了防止不必要的问题，请在运行mdbook前锁定下列版本
```bash
cargo install mdbook --version 0.4.52 --force
cargo install mdbook-admonish --version 1.20.0 --force
cargo install mdbook-mermaid --version 0.14.0 --force
cargo install mdbook-katex --version 0.3.12 --force
```

并且执行下列来初始化（通常不需要，除非你运行本地预览失败）
```bash
mdbook-admonish install .
mdbook-mermaid install .
```

启动本地预览:
```
mdbook serve --open
```