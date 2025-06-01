# Documentação do framework DynamoForRevitUtils 📄

Esse projeto usa o [Docfx](https://github.com/dotnet/docfx) para gerar a documentação do framework DynamoForRevitUtils.

# Publicação 🌐

O projeto utiliza o recurso do Github pages para publicação do site, contendo a documentação.

A publicação ocorre automaticamente no link abaixo ao fazer `push` para no branch `master`.

Link do site publicado 👉 https://onbim.github.io/DynamoForRevitUtils-docs/

# Estrutura de pastas 📂

As pastas do projeto estão estruturadas conforme as configurações necessárias para deploy automático no Github pages.

📂 **config** ➡️ Contém as configurações do projeto do Docfx.

📂 **docs** ➡️ Gerada automaticamente. Contém os arquivos do site.

📂 **external-libs** ➡️ Contém as bibliotecas utilizadas no projeto, incluindo **DynamoForRevitUtils.dll** e suas dependências.

Dentro da pasta **config** está um dos arquivos mais importantes, **docfx.json**. Esse arquivo possui as configurações
usadas pelo Docfx para compilar o projeto.

# Compilar o projeto usando o Docfx

Após atualizar o arquivo **DynamoForRevitUtils.dll** ou algum arquivo ***.md** do projeto,

1. Abra o terminal na pasta **config**.
2. Execute o comando `docfx docfx.json`.

Caso queria visualizar um preview do site, execute o comando `docfx docfx.json --serve`. 
Isso criará um servidor local na porta **8080**.

Caso queira especificar uma porta diferente, execute o comando `docfx docfx.json --serve --port <port>`.

**Observação:** Alguns warnings podem aparecer, mas não há problema. Eles são devido às dependências das dependências 
do projeto, as quais são irrelevantes e podem ser desprezadas. Isso ocorre por que o Docfx utiliza Reflection para
buscar toda a hierarquia dos Types associados aos arquivos principais.
