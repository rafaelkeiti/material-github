# Subindo um Projeto ao GitHub

- Criar um repositório no GitHub.

- Abriremos o Projeto e na pasta workspace utilizaremos:
```sh
git clone ${link}
```

- Criaremos uma nova BRANCH para o desenvolvimento do projeto:
```sh
git checkout -b "feature/${nome_da_branch}"
```

- Após realizarmos alterações no arquivos teremos que utilizar o comando:
```sh
git status (ver se o arquivo possui alterações)
```
```sh
git add ${nome_do_arquivo} (adiciona ele caso tenha alterações)
```
```sh
git commit -m "${commit semantico: (modificação realizada)}" (commita a alteração feita)
```

- Para subir o arquivo ao GitHub utilize o comando:
```sh
git push origin ${nome_da_branch_atual}
```

- Criação da PR para verificação das modificações pelo grupo (PR = PULL REQUEST)

- Caso seja feito o merge, devemos voltar ao PROJETO e ir para BRANCH MÃE:
```sh
git checkout ${main/master} 
```
e depois devemos utilizar o comando:
```sh
git pull origin ${nome_da_branch_atual} 
```
para que os arquivos sejam atualizados de acordo 
com o GitHub.

#
**OBS:**

    - Sempre utilizar primeiro o (git clone) na branch mãe e depois criar uma nova BRANCH!!!!

    - O comando (git pull) só atualiza os arquivos locais após ter feito o MERGE no GitHub!!!!


