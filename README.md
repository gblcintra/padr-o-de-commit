# Padrão de commit

Para melhorar e facilitar a identificação dos commits e suas respectivas tarefas, utilizaremos o padrão de commit proposto:

**Formato:**

```<tipo>(<local>): <mensagem em ingles> (<id-da-task>) <emoji>```

**`<tipo>` sendo:**

- feat : ( Um novo recurso. `feature` )
- fix : ( Uma correção de `bugfix` )
- hotfix : ( Uma correção diretamente dentro do ambiente de produção )
- style : ( Um código relacionado ao estilo, formatação, falta de ponto e vírgula, etc; )
- docs : ( Alterações relacionadas à documentação )
- deps : ( Atualização ou downgrade de dependências )
- refac : ( Um código que não corrige bug nem adiciona um recurso. (por exemplo: você pode usar isso quando houver alterações semânticas, como renomear uma variável/nome de função. `refactor`)
- chore : ( Uma alteração de código que o usuário externo não verá (por exemplo: alterar para arquivo .gitignore ou arquivo .prettierrc )
- perf : ( Um código que melhora o desempenho. `performance` )
- update : ( Para atualizações na estrutura do repositório )
- release : ( Para uma publicação )
- exemple : ( Para um exemplo de commit )

**`<local>` sendo:**

Basicamente seria o nome da pasta na qual esta sendo feita a alteração/implementação

- header
- footer
- banner
- checkout
- etc...

**`<icon>` sendo opcional (não obrigatório):**

# Emojis

| Emoji | Código do Emoji | Tipo | Descrição |
| --- | --- | --- | --- |
| ⭐ | ``:star:`` | ```feat``` | add **novo recurso** |
| 🐛 | ```:bug:``` | `fix` | corrigir um **bug** |
| 🔒 | ```:lock:``` | fix | corrigir um problema de **segurança** |
| ⚠️ | ```:warning:``` | fix | recurso **deprecate** |
| 🔙 | ```:back:``` | fix | **reverter** commit |
| 🚧 | ```:construction:``` | feat ou fix | **trabalho em progresso** |
| ♿ | ```:wheelchair:``` | feat ou fix | atualizar ou corrigir **acessibilidade** |
| 🚨 | ```:rotating\_light:``` | refactou fix | remover **linter** /strict/deprecation warnings |
| :ambulance: | ```:ambulance:``` | hotfix | corrigir um hotfix **bug** |
| 📈 | ```:chart\_with\_upwards\_trend:``` | perf | corrigir um problema de **performance** |
| :shirt: | ```:shirt:``` | refac | **refatorar** codigo |
| 📝 | ```:pencil:``` | docs | atualizar **documentação** |
| ©️ | ```:copyright:``` | docs | alteração de **licença** |
| 🆙 | ```:up:``` | update | **outras** atualizações |
| 🚚 | ```:truck:``` | update | **mover** ou **renomear** arquivos, pastas, ... |
| 🔀 | ```:twisted\_rightwards\_arrows:``` | update | resolução dos conflitos de **merge** |
| ➕ | ```:heavy\_plus\_sign:``` | update | **adicionar** arquivos, dependências, ... |
| ➖ | ```:heavy\_minus\_sign:``` | update | **remover** arquivos, dependências, ... |
| 🔛 | ```:on:``` | update | **habilitar** recurso ou algo assim ... |
| 🔧 | ```:wrench:``` | update | atualizar **configurações** |
| 📦 | ```:package:``` | update | **packaging** ou **bundling** ou **building** |
| 🌱 | ```:seedling:``` | update | **inicia** um commit |
| 🔖 | ```:bookmark:``` | update | **marcação** de versionamento |
| ⬆️ | ```:arrow\_up:``` | deps | atualizar **dependências** |
| ⬇️ | ```:arrow\_down:``` | deps | downgrade de **dependências** |
| 🎊 | ```:confetti\_ball:``` | release | release **major** version |
| 🎉 | ```:tada:``` | release | release **minor** version |
| ✨ | ```:sparkles:``` | release | release **patch** version |
| 🚀 | ```:rocket:``` | release | **deploy** em produção |
| 🍭 | ```:lollipop:``` | example | para **examplos** ou **demonstração** de codigos ou commits |

Existe essa exteção no VsCode que facilita na hora de inserir os icons:

[https://marketplace.visualstudio.com/items?itemName=seatonjiang.gitmoji-vscode](https://marketplace.visualstudio.com/items?itemName=seatonjiang.gitmoji-vscode)

Exemplo de commit:
  
```
feat(header): change logo (ICD-XXXX) :star:
^--^ ^----^   ^---------^  ^------^  ^----^
|      |           |           |        +-> Emoji relacionado ao tipo(sendo opcional)
|      |           |           +-> Id da tarefa
|      |           +-> Resumo do que foi feito.
|      +-> local/pasta em que esta sendo feito a alteração/novo recurso
+-------> tipo: feat, fix, docs, style, refactor, etc.
```

feat(header): change logo (ICD-XXXX) :star:
