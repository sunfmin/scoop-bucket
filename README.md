# zhiyuan

查已授权的高考志愿数据。程序公开下载。没有有效的授权码就拿不到库 key，解不开数据。

macOS 和 Linux：

```sh
brew install sunfmin/tap/zhiyuan
```

Windows：

```sh
scoop bucket add sunfmin https://github.com/sunfmin/scoop-bucket
scoop install zhiyuan
```

然后 `export ZHIYUAN_LICENSE=<授权码>`。不要把授权码放在命令行上。第一次运行要能连上授权服务。把 `zhiyuan skill` 印出的文字存成 `~/.agents/skills/zhiyuan/SKILL.md`。

说明在 `zhiyuan --help`。
