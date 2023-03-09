Olá esse projeto ensina você a usar o Git.

Realizando uma alteração!



# Sobre o projeto

Anotações feitas dos vídeos da Rafaella Ballerini 
https://www.youtube.com/watch?v=DqTITcMq68k&t=1s
https://www.youtube.com/watch?v=UBAX-13g8OM&t=1652s

Praticando Git e GitHub

# PASSO-A-PASSO GIT E GITHUB

- Usando um clone de um repositório remoto:

```bash
# No local acessar a pasta onde o clone será realizado
cd (Nome da pasta)

# Clonando um repositório - Lembrando que aqui a branch atual será a “main” ou a principal que estiver sendo usada atualmente
git clone link do repositório

# Aqui vamos acessar o repositório que clonamos
cd nome do repositório que acabamos de clonar

# Iniciando um repositório
git init

# Criar uma nova branch apenas se necessário, do contrário realizar as modificações direto na branch atual(Com sabedoria);
git checkout -b “Nome da nova branch”

# Verificando o status dos arquivos
git status

# Adicionando os arquivos no staging (aguardando commit)
git add .

# Aqui estamos commitando e preparando os arquivos para upload
git commit -m “Título do arquivo”

- No momento do Merge local:

# Aqui mudamos a branch para a main (Branch principal - produção)
1 - git checkout main

# Aqui vamos atualizar o local para nos certificar que estamos com o código atualizado no momento atual
2 - git pull

# Aqui vamos mergiar a branch que fizemos as modificações novas com a main (Ou com qualquer outra branch que seja a principal no momento do desenvolvimento)
3 - git merge “Branch com as novas alterações”

# Aqui vamos subir os arquivos para o repositório remoto
4 - git push origin “Branch com as novas alterações”

```


# PASSO-A-PASSO GIT E GITHUB

- Criando um repositório local e vinculando/referenciando o mesmo a um repositório remoto:

```bash
# Criando uma pasta local para o projeto
mkdir "nome da pasta"

# Aqui vamo acessar a pasta que acabamos de criar
cd (Nome da pasta criada)

# Iniciando um repositório
git init

# Aqui vamos vincular/referenciar um repositório local a um repositório remoto
git remote add origin (link do repositório do github)

# Criar uma nova branch apenas se necessário, do contrário realizar as modificações direto na branch atual(Com sabedoria);
git checkout -b “Nome da nova branch”

# Verificando o status dos arquivos
git status

# Adicionando os arquivos no staging (aguardando commit)
git add .

# Aqui estamos commitando e preparando os arquivos para upload
git commit -m “Título do arquivo”

- No momento do Merge local:

# Aqui mudamos a branch para a main (Branch principal - produção)
1 - git checkout main

# Aqui vamos atualizar o local para nos certificar que estamos com o código atualizado no momento atual
2 - git pull

# Aqui vamos mergiar a branch que fizemos as modificações novas com a main (Ou com qualquer outra branch que seja a principal no momento do desenvolvimento)
3 - git merge “Branch com as novas alterações”

# Aqui vamos subir os arquivos para o repositório remoto
4 - git push origin “Branch com as novas alterações”

```

# Autor

Kira Oliveira
