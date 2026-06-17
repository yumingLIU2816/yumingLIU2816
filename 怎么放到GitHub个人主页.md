# 怎么做成 GitHub 个人主页

这个效果不是普通项目 README，而是 GitHub 的个人主页 README。

## 1. 新建特殊仓库

在 GitHub 新建一个仓库，仓库名必须和你的 GitHub 用户名完全一样。

例如：

- 你的 GitHub 用户名是 `abc123`
- 仓库名就必须叫 `abc123`

GitHub 会自动提示这是一个 special repository。

## 2. 放入 README

把这个文件夹里的 `README.md` 放到那个同名仓库根目录。

## 3. 替换占位符

在 `README.md` 里搜索并替换：

- `YOUR_GITHUB_USERNAME`：换成你的 GitHub 用户名
- `ADD_YOUR_LINKEDIN`：换成你的 LinkedIn
- `ADD_YOUR_EMAIL`：换成你的邮箱
- `ADD_YOUR_PORTFOLIO_LINK`：换成你的博客、作品集或删掉这一行

## 4. 想更像截图的话

截图里那种一排大图标主要靠这行：

```md
![Skills](https://skillicons.dev/icons?i=python,r,sklearn,tensorflow,pytorch,mysql,git,github,vscode,docker,html,css,js&perline=7)
```

你可以增删里面的技能名，比如：

- `java`
- `cpp`
- `react`
- `nodejs`
- `aws`
- `linux`

## 5. 最推荐的改法

如果你只是想求职用，不建议堆太多技术图标。保留你真的能解释的技能就够了，否则面试官点进去看项目时会觉得不匹配。
