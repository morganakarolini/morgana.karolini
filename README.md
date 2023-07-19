# Documentação do Morgana.Karolini

## Visão Geral

Este projeto é um repositório pessoal mantido por Morgana Karolini. Ele contém os artigos e recursos relacionados ao
site www.morganakarolini.adv.br.

## Tabela de Conteúdos

- [Utilizando GoHugo e o Tema Blist Hugo](#utilizando-gohugo-e-o-tema-blist-hugo)
- [Licença](#licença)

## Utilizando GoHugo e o Tema Blist Hugo

Este projeto utiliza o GoHugo, um popular gerador de sites estáticos de código aberto, juntamente com o Tema Blist Hugo.
O GoHugo permite construir sites estáticos de forma rápida e fácil, enquanto o Tema Blist Hugo oferece um layout bonito
e responsivo para o seu site criado com Hugo.

Para utilizar o GoHugo e o [Tema Blist Hugo](https://github.com/apvarun/blist-hugo-theme):

1. Instale o GoHugo seguindo o [guia oficial de instalação](https://gohugo.io/getting-started/installing/).
2. Crie um novo site do Hugo:

```bash
hugo new site mysite
```

3. Acesse o diretório do site recém-criado:

```bash
cd mysite
```

4. Inicialize um novo repositório Git:

```bash
git init
```

5. Adicione o Tema Blist Hugo como um submódulo do Git:

```bash
git submodule add https://github.com/apvarun/blist-hugo-theme.git themes/blist
```

6. Configure o tema no arquivo `config.toml` do seu site:

```toml
theme = "blist"
```

Você também pode personalizar outras configurações do Hugo e do tema neste arquivo.

7. Crie conteúdo usando arquétipos do Hugo e a sintaxe Markdown.

8. Construa seu site:

```bash
hugo
```

9. Seu site gerado estará disponível no diretório `public/`.

Para obter instruções mais detalhadas sobre como usar o GoHugo e o Tema Blist Hugo, consulte a documentação respectiva.

10. Para rodar localmente, execute o comando:

```bash
hugo server -D
```

## Licença

O conteúdo deste projeto está licenciado sob a [Licença MIT](LICENSE). Por favor, revise o arquivo de licença para obter
mais informações sobre as permissões e limitações que ela oferece.
