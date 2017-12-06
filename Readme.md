# MkDocs integrate with mermaid, sequence, flowchart

For full documentation visit [mkdocs.org](http://mkdocs.org).

According to [MkDocs的使用-甘特图](https://my.oschina.net/u/3465063/blog/895151 "呼呀拉拉"), Mkdocs using gantt with mermaid. I changed a little configuration and script for mermaid version 7.x.x.


## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml          # The configuration file.
    docs/
        index.md        # The documentation homepage.
        uml.md          # Some UML chart testing page.
    js/
        umlconvert.js   # Integrate external js. Can initial or do some settings hsere.
