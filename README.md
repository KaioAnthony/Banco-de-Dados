# Banco de Dados

## Oque são?

O conceito de banco de dados seria a coleta de informações ou dados que são armazenadas em um sistema de computador, normalmente são controlados por um sistema de gerenciamento.

| Pedido_ID | Cliente_nome | Cliente_endereço | Produto_ID | Quantidade | Preço | 

## Banco relacional e não relacional

Existem dois tipos de banco de dados, que são o relacional(SQL) e não relaciona(NoSQL).

__Banco Relacional:__

O banco de dados relacional frequentemente é usado aqueles que trabalha com tabelas relacionais, ou seja, tabelas que são constituidas por linhas e colunas, que lembra muito a estrutura usada pelo Excel.
As tabelas são representadas por uma situação no mundo real, as linhas sãos os registros e as colunas são os atributos.

Exemplo de banco relacional:

![BANCO RELACIONAL](https://blog.debugeverything.com/wp-content/uploads/2021/04/banco-de-dados-relacional-tabela-usuario.jpg)

### 

__Banco não relacional:__

O banco de dados não relacional ou pode ser chamado de NoSQL é um modelo de tabela que não segue o mesmo modelo dos bancos relacionais, ou seja, possuem varios tipos de modelos como o colunar, modelo de grafos, chave-valor e modelo que são usados para documentos. Esses modelos possuem características individuais que é se adéqua para diferentes usos na necessidade de armazenar dados.

Exemplo de banco não relacional:

![](https://blog.debugeverything.com/wp-content/uploads/2021/04/banco-de-dados-nao-relacional-key-value-store.jpg)

### 

## Oque é normalização no banco de dados?

O conceito de normalização é um modelo de dados relacionais para grande banco de dados compartilhados

__Qual é o seu objetivo?__

A normalização se foca na toma medidas contra problem de repetição e atualização de dados, como tomando cuidado com a integridade de dados possuindo "Formas Normais" que seriam regras estruturadas e agrupadas em três niveis:

Primeira forma:

Exige que todos os dados em uma tabela sejam atômicos, ou seja, cada campo deve conter apenas um valor e não listas ou repetições dentro da célula. Isso garante que a tabela esteja organizada de forma simples e clara, com uma estrutura tabular verdadeira.

![](https://media.discordapp.net/attachments/1341900461396988094/1402261144252579870/CE3213B3-401F-4DBB-8C53-E58BB58F72B4.png?ex=689344f5&is=6891f375&hm=8daa4be79450f55b2a13f9c74121eba0f56940ef9ce20c4a478c3f291084b2cc&=&format=webp&quality=lossless)

Segunda forma:

A segunda forma normal (2FN) parte do princípio de que a tabela já está na 1FN e exige que todos os campos que não são chave dependam da chave primária por completo. Isso é especialmente importante quando a chave primária é composta por mais de um campo. Assim, elimina-se a chamada dependência parcial.

![](https://media.discordapp.net/attachments/1341900461396988094/1402262238986768394/D8DA001B-0392-4293-8D95-871313C27561.png?ex=689345fa&is=6891f47a&hm=78b08e452077f0fc991227c8f6e055a010190bbc3c9e698301a688bcbba173c1&=&format=webp&quality=lossless)

Terceira forma:

Também parte da tabela já na 2FN e busca eliminar dependências transitivas, ou seja, quando um campo depende de outro que não é a chave primária. A tabela fica mais enxuta, sem dados redundantes ou mal relacionados.

![](https://media.discordapp.net/attachments/1341900461396988094/1402272288359055401/1A9D4681-D760-4761-93D3-5C6B8A4FFA19.png?ex=68934f56&is=6891fdd6&hm=6c765ca132da12d634ad1406cb7b85f1418317fd8c7a61315c8a7fd29a68dd79&=&format=webp&quality=lossless)

### 

## Modelo não relacional

