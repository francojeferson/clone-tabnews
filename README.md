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

- `git commit --amend -m chore: create .gitignore`

emenda commit anterior com staged changes acompanhado de mensagem depois do -m (alterar conforme necessario)

===
