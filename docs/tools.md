# Ferramentas

Essas são as ferramentas de formatação que estão disponíveis na forma de plugins do mkdocs.  

## Tabelas

| Command | Effect |
| :------- | :------: |
| `mkdocs new [dir-name]` | Create a new project |
| `mkdocs serve` | Start the live-reloading docs server. |
| `mkdocs build` | Build the documentation site. |
| `mkdocs -h` | Print help message and exit. |

## Código

``` py

  """Código radical que faz algum treco"""  
  from alguma_lib import (
      AlgumRepo,
      AlgumaFunc)
  from project.app.port import (
      FazerCoisaRequest,
      FazerCoisaResponse)

  class alguma_classe:

    def __init__():
        self,
        _algum_repo: AlgumRepo = AlgumRepo()
        _alguma_fun: AlgumaFunc = AlgumaFunc()

    def fazer_alguma_coisa(
        request: FazerCoisaRequest
        )->FazerCoisaResponse:
        """ Função que faz uma coisa maneira"""

        # variaveis hardcodadas porque nao tenho medo do perigo
        var_num = 666
        var_str = "corinthians"

        # coisa maneira ocorre
        alguma_coisa = self._alguma_func(
            request.dado_importante_1,
            request.inforacao_critica)

        # o retorno do rei
        return FazerCoisaResponse(
            var_num,
            var_str,
            alguma_coisa)
```

## Content Tabs

This is some examples of content tabs.

=== "Plain text"

    This is some plain text 🦶

=== "Unordered list"

    * First item 😁
    * Second item 🫠
    * Third item 🤪

=== "Ordered list"

    1. First item 🤪
    2. Second item 🫣
    3. Third item 🫥

## Cards

<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

    ---

    Install [`mkdocs-material`](#) with [`pip`](#) and get up
    and running in minutes

    [:octicons-arrow-right-24: Getting started](#)

-   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

    ---

    Focus on your content and generate a responsive and searchable static site

    [:octicons-arrow-right-24: Reference](#)

-   :material-format-font:{ .lg .middle } __Made to measure__

    ---

    Change the colors, fonts, language, icons, logo and more with a few lines

    [:octicons-arrow-right-24: Customization](#)

-   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

    ---

    Material for MkDocs is licensed under MIT and available on [GitHub]

    [:octicons-arrow-right-24: License](#)

</div>
