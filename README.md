# clone-tabnews

implementacao do tabnews para o curso.dev

===

- `nvm ls`
- `nvm use [num]`
- `nvm install lts`
- `node -v`

estes comandos sao usados para verificar e instalar node_modules pelo terminal

===

aplicar `lts` no lugar da versao usada (.nvmrc)

===

- `npm init`

iniciar manifesto (package.json)

===

- `npm install next@13.1.6`

aplicar `lts` no lugar da versao usada

===

- `npm install react@18.2.0`
- `npm install react-dom@18.2.0`

aplicar `lts` no lugar da versao usada

===

![package.json/dependencies](/assets/image.png)

dependencies deve aparecer assim (ou com versao lts)

===

- `"dev": "next dev"`

escrever essa linha dentro de scripts (package.json)

===

- `npm run dev`

inicia servidor next localhost

===

- ports (icone de antena vscode)
- click forward a port
- coluna Port : 3000 (enter)
- right-click, port-visibility, public

como liberar porta de acesso

===

- `ls -la`

lista todos os arquivos e pastas, incluindo ocultos (.git)

===

- `git log`

mostra registros commit

===

- `git log --stat`

retorna memoria do git database (banco de dados)

===

- `git status`

compara tudo que tem diferente desde o ultimo commit

===

- untracked
- modified
- staged
- commited

estagios do diretorio no git

===

- `git add .gitignore`

adiciona ao `staged changes` em source control (alterar nome do arquivo)

===

- `git commit -m chore: create .gitignore`

envia staged changes pra commit acompanhado de mensagem depois do -m (alterar conforme necessario)

===

- `git log --oneline`

mostra commits resumidos

===

- `git diff`

compara versao anterior com versao atual

===

- `git commit --amend`

emenda commit anterior com staged changes

===

- `git push`

empurra commit da local/branch para origin/branch

===

Principle of Least Privilege
(Princípio do Privilégio Mínimo)

pra maior segurança do sistema construido é recomendavel sempre atribuir a menor quantidade de acesso, credencial ou privilegio que uma conta pode ter dentro do sistema

===

Inception

- 48% Muralha Tecnologia
- 48% Muralha Negócios
- 2% Acima da Muralha

===

Concepçao de projeto

- Modelo organico (célula por célula)
- Impressora 3D (camada por camada)

===

- Over Engineering
- Feature Creep

bola de ferro no pé do projeto se escolher impressora 3D

===

- Moral (o que está sentindo na hora)
- Prática (o lixo de uns é tesouro de outros)

===

- Trabalhar pouco
- Ganhar muito

cerebro vem de fabrica com suporte a um calculo especial que é conseguir calcular o **saldo** das coisas -- pra entender se vale a pena continuar ou nao com o que ta sendo feito

- dar 1 passo pra tras pra avançar 2 passos pra frente é saldo positivo
- dar 10 passos pra trás pra avançar 1 passo pra frente é saldo negativo
- quando quer fazer algo e fica patinando, nao sai do lugar, sentimento estranho, pensamentos ruins, quando chega no limite e decide executar, se embaralha todo, toma um tombo e a sensaçao que fica é horrivel

===

nivel 1: ser lembrado individualmente

- menor custo de produçao (energia)
- menor tempo de aquecimento (demora)

nivel 2: ser lembrado em grupo

- checklist
- marca com bolinha progresso intermediario
- marca com check progresso completo

nivel 3: expandir conhecimento

- manual de instruçoes

nivel 4: gerar metricas

- barreira técnica
- barreira de negócio

===

tudo ou nada: saldo de fazer nada é sempre positivo

- issue de inception

pegar a ideia em formato de grafo e converter pra formato linear

- comer pedra

quebrar a ideia em fragmentos menores
a rachadura que se cria é imprevisivel
github: milestones e issues

===

dopamina
estagio 1: inicio
estagio 2: progresso
estagio 3: conclusao

===

.editorconfig

seguir regras de formataçao acontece **antes** de salvar o arquivo (pelo menos em sua maioria)

por padrao o vscode nao sabe ler e respeitar as regras, é necessario instalar extensao EditorConfig

===

Prettier

formatador de código opinado, com flexibilidade para customizar regras

é preciso combinar regras em grupo para que o codigo fique formatado do mesmo jeito

===

- `npm install prettier --save-dev`

instalando no manifesto o CI fica responsavel de verificar formataçao

===

- `"lint:check": "prettier --check ."`

incluir no package.json/scripts

- `npm run lint:check`

lista arquivos com style issues

===

- `"lint:fix": "prettier --write ."`

incluir no package.json/scripts

- `npm run lint:fix`

corrige style issues nos arquivos

===

instalar extensao do Prettier

click settings do vscode

buscar formatter

definir Prettier como padrao (default formatter)

buscar format on save

check format on save

buscar auto save

desligar auto save (off)

===

- `git add --all`

envia tudo o que está modificado na area de trabalho (workspace)

===
