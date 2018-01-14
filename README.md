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
├── events
│   └── event1.yaml
├── README.md
└── static
    └── template.yaml
```
## Format Requirement

## 数据格式 / Data Format

本项目数据采用 [YAML](https://zh.wikipedia.org/wiki/YAML) 格式。

### 命名 / Naming
命名规范如下。**UTF-8** 为默认编码。请尽量使用原名，例如，`John_Doe.yaml` 用于英文名人士，`张三.yaml` 用于中文名人士。如需添加额外的多语言名字，请在文件中附上内容。

The naming conventions are stated as followed. Noticed that **UTF-8** is in use by default, please maintian the name as original as possible, e.g., `John_Doe.yaml` is for some person who is known as his name in English and `张三.yaml` in Chinese. In addition, if you want to create an entry for someone is known for names in multiple languages, please use the most commmon one and add other names in the entry as auxiliary content.

合规名列举
1. `First(_Middle)_Last.yaml`, `(_Middle)` 可选以避免重名; `姓名.yaml`。首字母需要大写。
2. `First(_middle)_Last(__schoolname).yaml`, `schoolname` 应展开作 `Carleton_University`（例子）; 中文形式为`姓名__学校.yaml`。 下划线`_`用来替换` `。
3. 扩展名`.yaml`应保留。

Acceptable naming formats are
1. `First(_Middle)_Last.yaml`, where `(_Middle)` is optional in avoidence of duplicated names; `姓名.yaml`. Noticed that captalized initial letter is required.
2. `First(_middle)_Last(__schoolname).yaml`, where `schoolname` should be expanded as `Carleton_University` for example; it is put as `姓名__学校.yaml` in Chinese. Noticed that the underscore `_` is the replacement of white space ` `.
3. The extension name `.yaml` should be kept.

### 内容 / Content

One of the essential parts in the content is the `suspected` or `believed` sections. 
And we try to illustrate the difference:
1. If there is no external proof from solid source, it is **suspected**. It includes but is not limited to disputations stated by anonymous students **without** official statement or other proof.
2. If there is external proof from solid source, it is **believed**. The solidd sources mainly includes 1) statement by the official, 2) news from recongized authorities, etc.

If there is no content for the `suspected` section or `believed` section (but one of the two is req'ed), please simply leave it alone.

## 学术界 FAQ



## 其他资源

- [导师评价网](https://www.mysupervisor.org/)
- [RateMyProfessors](https://www.ratemyprofessors.com)

## 许可 / License
本项目内容内许可为[署名-非商业性使用-相同方式共享 4.0 国际](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)，用于格式化及展示内容的源代码许可为[GPL-3.0](https://opensource.org/licenses/GPL-3.0)。

The content of this project itself is licensed under the [Attribution-NonCommercial-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-nc-sa/4.0/), and the underlying source code used to format and display that content is licensed under the [GPL-3.0](https://opensource.org/licenses/GPL-3.0).
