
<!-- 
- INSTALAR O HUGO (https://gohugo.io/)
- BAIXAR O TEMPLATE INICIAL (https://themes.gohugo.io/minimal-bootstrap-hugo-theme/)
- HOSPEDAR NO NETLIFY (https://minimal-bootstrap-hugo-theme.netlify.com/hugoisforlovers/) -->



# Instalando o HUGO

Para instalar o hugo no windows é necessário baixar o executave no [site](https://github.com/gohugoio/hugo/releases)

Descompacte o executavel em um pasta e adicione o caminho dessa pasta nas variaveis do sistema,

# Inicializando o repositorio

```
hugo new site nome_site
```


# Instalar o thema

Para instalar o tema:
- [encontrar o tema](https://themes.gohugo.io/)
- Baixe o tema do github
- descompacte o tema na pasta themes
- configure o "config.toml"  a variavels theme (E.g. theme = "nome_do_tema")


# Rodando o servidor
Rode o seguinte comando na pasta.
```
hugo server
```


# Criando uma pagina

PAra criar uma nova pagina  digite o comando:
```
hugo new a.md
```


# Gerando um site estatico
Gera os arquivos estatico dentro da pasta public
```
hugo
```