# HERM Karma Proposals

Este repositório contém todas as contribuições das pessoas, seja elas via Código ou seja ela via Prova de Generosidade.

Ainda não existe um padrão definido, que, antecipo, precisa ser estipulado para que possamos padronizar as propostas na hora do Karma-API iniciar seus respectivos blocos de votação.

Portanto se você abrir uma nova proposta para ser validada quando o sistema estiver na Rede Principal precisa sempre considerar que muita coisa pode mudar e você provavelmente terá que atualizar suas propopostas para seguir o padrão da versão finalizada.

## Criando uma proposta

O primeiro passo é de fato já ter feito a sua boa ação antes de criar uma proposta.

O segundo passo é abrir um novo Merge Request para este repositório com apenas um arquivo em Markdown.

Ele deve possuir o seguinte nome: {{dd-mm-yyyy/hhmm}} + o título da proposta em kebab-case, como por exemplo: `08-09-2023/1904-page-translation.md`

> Você deve criar uma pasta caso não haja, ou apenas incluir seu arquivo lá.

E ele deve seguir um template, que segue de exemplo:

```
### Page Translation

De acordo com a sugestão no rodapé da [página](https://hermetic.surge) eu contribui na tradução de todas coisas possíveis.

#### Prova de Ação:

{{ provas_da_ação }}

Mas eu não sou desenvolvedor, potanto não pude implemetar isso.

#### Pretenção de Bonus: `0.0000500`
#### Wallet: `0x000000000000000000000000`
```

> Ou considere usar duas Wallets também, nos casos adequados.

```
### Page Translation

De acordo com a sugestão no rodapé da [página](https://hermetic.surge) eu contribui na tradução de todas coisas possíveis.

#### Prova de Ação:

{{ proof_of_action }}
{{ url_commit or url_merge_request }}

Mas eu não sou desenvolvedor, mas em parceria com outro usuário implementamos uma flag no Website capaz de alterar, portanto traduzir todo o texto disponível, com exceções de urls extenas.

#### Pretenção de Bonus: `0.0000500`
#### Wallet: `[0x0000000000000000000000000000000000000000, 0x0000000000000000000000000000000000000001]`
```

> O valor será dividido entre todas as contas da lista.

---

## Expectativa

A ideia é que depois que o Karma-API estiver funcional as pessoas possam votar de forma com que escolham opções como:

- Valido
- Invalido
- Valido mas Subfaturado
- Valido mas Superfaturado

E a Karma será responsável por estipular um Bônus baseado nas respostas.