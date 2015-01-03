# IT Finishers
Projeto (inicial) do website itfinisher[.github.io|.org].

## Atualização (local) do site
* Se não tiver o [Ruby](http://ruby-lang.org) instalado em tua máquina, instale-o. Dica: utilize o [RVM](http://rvm.io).
* Instale o [Asciidoctor](http://asciidoctor.org)
```bash
gem install asciidoctor
```
* Execute o script a seguir. Ele iniciará um servidor httpd básico.
```bash
./httpd start
```
* Construa o site:
```bash
./build
```
* Abra a URL http://localhost:8000.
* Para editar ou criar qualquer doc utilize seu editor de textos preferido (dica: use o [Vim](http://www.vim.org)) e construa seu documento de acordo com a sintaxe do Asciidoctor. A qualquer momento, execute o script `./build` para gerar o doc no formato HTML.
