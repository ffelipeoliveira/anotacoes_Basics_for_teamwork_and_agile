<h1 align="center" style="font-weight: bold;">BlockChain ⛓</h1>

<p align="center">
Blockchain é um cadeia de blocos que armazena informações de modo seguro, imutável e descentralizado.
</p>

---
### Sumário

1. Contexto Histórico
2. Chaves
3. Rede P2P
4. Bloco
5. Função Hash
6. Proof of Work
7. Mineração
8. Quando usar Blockchain
   
---
### 1. Contexto Histórico
A ideia por trás da **Blockchain** tem raízes por volta do ano de 1494, em um livro de razão chamado _Ledger_, escrito pelo padre Luca Pacioli.  
Na época, consistia em promover o balanço de ativos tangíveis e intangíveis, disponibilizando de forma ordenada várias operações de crédito e débito e a composição de um balanço total.  

---
### 2. Chaves
Existem dois tipos de chaves.
* **Secreta (SK)** 
  * Usada para assinar
  * Deve ser mantida em segredo total
  * Caso alguém obtenha acesso indesejado à chave ele terá também acesso total a tudo que estiver associado a ela.
* **Pública (PK)**
  * Usada para atrelar dados à sua chave secreta
  * Pode ser de conhecimento público
  * Transações relacionadas a ela são somadas para se obter o saldo
  
---
### 3. Rede P2P

A rede ponto-a-ponto ou P2P é uma estrututra de redes de computadores em que não há um servidor definido para armazenamento e compartilhamento de informações.

* Descentralizada
* Distribuída
* Segura
* Compartilhada
  

---
### 4. Bloco

|    Block     |
|--------------|
| Hash         |
| Hash Anterior|
| Nonce        |
| Transações   |

---
### 5. Função Hash

A criptografia Hash permite que, a partir de uma entrada de qualquer tamanho, seja calculada um identificador de tamanho fixo, chamado de **Hash**.

Ao alterar um bloco da Blockchain, o hash desse bloco será alterado completamente, fazendo com que todos os próximos blocos sejam invalidados, pois eles também carregam a informação sobre o bloco anterior.  
Para alterar uma informação já registrada na blockchain todo o resto da blockchain deverá ser alterada também

---
### 6. Proof of Work

**Nonce** é um número usado para decidir quem vai ter o direito de adicionar o próximo bloco à Blockchain, que será aquele que tenha encontado o hash que possui um determinado número de zeros no começo.

* Para fazer isso eles terão de computar diversas vezes esse hash mudando sempre o valor do nonce.
* A quantidade de zeros é chamada de dificuldade e é atualizada de modo que algum minerador consiga encontrar um bloco novo a cada 10 minutos, em média. Ou seja, quando houver poucos mineradores, a dificuldade irá diminuir.

* A mineração não é cumulativa, mas sim aleatória.
  
---
### 7. Mineração
* A **coinbase transaction**, o ato de encontrar o próximo bloco, corresponde à principal forma de remuneração dos mineradores.
  
* A mineração é responsável por 0,16% do consumo de eletricidade. Por isso é bastante criticada.
  
* A mineração é responsável pela segurança da Blockchain. Por causa dela, é praticamente impossível fraudar a Blockchain por que para isso seria necessário tem 51% do processo computacional da rede, o que é impossível para qualquer organização.

* Mesmo que isso se tornasse de alguma forma possível, o preço do Bitcoin despencaria, o que tornaria a fraude inútil.

Pode demorar 1466 anos para um computador encontrar um bloco do Bitcoin, por isso existe os **mining pods**, redes de computadores especalizados em minerar.  
Quando um desses computadores encontra um bloco, a remuneração é dividida entre todos que participaram de proporcionalmente ao esforço empregado.  
Mining pods são automatizados e não mineram apenas uma só criptomoeda.

Para que o preço do Bitcoin não diminua, existe o **Halving**, que é o fato de que de tempos em tempos a recompensa para mineradores cai pela metade. Isso torna a mineração menos lucrativa, reduzindo o número de mineradores e consequentemente o número de blocos que serão produzidos, até chegar a 21 milhões de blocos, o máximo de blocos que o Bitcoin terá.

---
### 8. Quando usar Blockchain

Por conta da propriedade da imutabilidade, blockchain pode ser útil quando precisa-se armazenar dados que não podem ser apagados ou alterados, como por exemplo registros. No entanto também é válido ressaltar que Blockchain é pública, mesmo que em escala menor ou privada, pois o grande número de nós é essencial para a segurança. Então ele deve ser usado somente quando pode-se dar a esse dado um grau elevado de transparência.

[Voltar](../../Readme.md)
