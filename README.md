# The Other Stories in Academia


## 多人协作说明

- 在本项目发起一个 issue，补充信息或反馈错误。
- Fork 该项目，进行修改，然后发起 pull request。
- [Git - Book](https://git-scm.com/book/en/v2) (Multi-language docs)
- [Git - 简明指南](http://rogerdudler.github.io/git-guide/index.zh.html)

## 目录

```
.
├── LICENSE
├── persons
│   ├── name0.yaml
│   └── name1.yaml
├── README.md
└── static
    └── template.yaml
```
## Format Requirement

## 数据格式 / Data Format

本项目数据采用 [YAML](https://zh.wikipedia.org/wiki/YAML) 格式。

### Naming
Currently we put everthing in either Chinese and English.

1. The entry **must** be named as `First_Last.yaml` in English or `姓名.yaml`
2. In avoidance of duplicated names, we recommand 1) `First_Middle_Last.yaml` (Chinese people don't have middle name, though) or 2) `First_Last__schoolname.yaml` / `姓名__学校.yaml`. Noticed that there is **one** underscore `_` to separate the first and the last names and **two** underscores to separate the full name and the school name.
3. The extension name `.yaml` should be kept.

### Content
(...)
The most important part of the content is the `suspected` or `believed` sections.

Here we try to illustrate the difference:
1. If there is no external proof from solid source, it is **suspected**. It includes but is not limited to disputations stated by anonymous students **without** official statement or other proof.
2. If there is external proof from solid source, it is **believed**. The solidd sources mainly includes 1) statement by the official, 2) news from recongized authorities, etc.

If there is no content for the `suspected` section or `believed` section (but one of the two is req'ed), please simply leave it alone.

## 学术界 FAQ



## 其他资源

- [导师评价网](https://www.mysupervisor.org/)
- [RateMyProfessors](https://www.ratemyprofessors.com)

## License
The content of this project itself is licensed under the [Attribution-NonCommercial-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-nc-sa/4.0/), and the underlying source code used to format and display that content is licensed under the [GPL-3.0](https://opensource.org/licenses/GPL-3.0).
