<h1 align="center" style="font-weight: bold;">Conventional Commits ⛑</h1>

<p align="center">
Conventional Commits é uma convenção sobre mensagens de commit utilizada para criar um histórico explícito e fácil de se desenvolver ferramentas automatizadas em cima
</p>

---
### Sintaxe
	<tipo>(escopo opcional): [descrição]
	[corpo opcional]
	[rodapé opcional]

---
### Palavras chave
Existem dois tipos principais:
* **fix**: correção de bug
* **feat**: introdução de feature  

E tipos secundários:
* chore:
* docs:
* build:
* ci:
* style:
* refactor:
* test:
  

Pode-se introduzir **!** após o tipo para indicar uma Breaking change  
Também pode-se escrever **BREAKING CHANGE** no rodapé para explicar qual funcionalidade pode ser quebrada com o commit.

**Exemplo**: feat(api)!: app now sends sms confirmation before login

[Voltar](../../Readme.md)