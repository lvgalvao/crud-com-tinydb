# TinyDB

É um banco de dados orientado a documento escrito totalmente em Python. Ele é simples, leve e fácil de usar. O TinyDB não possui nenhuma dependência externa, ou seja, não é necessário instalar nenhum driver ou servidor para utilizá-lo.

O objetivo deste repositório é apresentar o TinyDB e mostrar como utilizá-lo em aplicações Python na área de dados e web.

## Revisão geral

### Banco orientado a documentos

Bancos orientados a documentos são bancos não relacionais que armazenam os dados em documentos no formatos do tipo JSON, BSON, XML, YAML etc. 

### Diferencial de um banco SQL

O diferencial de um banco SQL é que ele não possui um schema definido, ou seja, não é necessário definir a estrutura do documento antes de inserir os dados. Isso permite que os documentos tenham estruturas diferentes, o que é muito útil em aplicações web, pois os dados podem ser inseridos de forma dinâmica.

### Formato Json

O formato JSON é um formato de dados muito utilizado em aplicações web, pois é de fácil leitura e escrita. Um documento JSON é composto por pares de chave e valor, onde a chave é uma string e o valor pode ser um número, string, booleano, array ou outro documento JSON.

```json
{
    "nome": "João",
    "idade": 20,
    "cidade": "São Paulo",
    "telefones": [
        "11999999999",
        "11988888888"
    ]
}
```