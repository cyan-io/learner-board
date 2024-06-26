<center><h1>Learner-Board</h1></center>

<center>为老师和助教开发的 <a  href="https://www.learnerhub.net">知士荟</a> issue面板</center>

## FEATURE

- 适用于所有space
- 快速分析待解决的问题、精华内容
- 使用`pip`安装，可在任意终端运行

## EXAMPLE

```shell
# lboard 478
```

```text
+---+---------+------------------------------------------------------------+
| S |   Date  |                           Title                            |
+---+---------+------------------------------------------------------------+
| ? | 03/24 7 |                 如何计算某年某月一日是周几                 |
|   |         |  🔗 https://www.learnerhub.net/#/spaces/478/issues/13035   |
| ? | 03/23 6 |   犯二的程度-只有一个测试集过不了，想知道问题出现在哪里    |
|   |         |  🔗 https://www.learnerhub.net/#/spaces/478/issues/13033   |
|   |         |                            + 1                             |
| ? | 03/22 5 |                      关于三角函数计算                      |
|   |         |  🔗 https://www.learnerhub.net/#/spaces/478/issues/13031   |
|   |         |                            + 4                             |
| ✔ | 03/21 4 |                  递归函数和循环有啥区别？
……
```

`?` 尚未解决的问题

`✔` 加精内容

`+n` +n已解决且未加精的问题数量


## INSTALL

```shell
pip install learner-board -i https://pypi.org/simple
```

## USAGE

```shell
lboard -p <space id>
```

specifically

```text
lboard -h
usage: lboard [-h] [-p PAGE_COUNT] spaceid

positional arguments:
  spaceid               you can find it in space's url, generally a
                        number

options:
  -h, --help            show this help message and exit
  -p PAGE_COUNT, --page_count PAGE_COUNT
                        pages to fetch
```

how to find `space id` ？

https://www.learnerhub.net/#/spaces/<spaceid>/

