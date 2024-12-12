
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre o Git e GitHub do curso Versionamento de Código com Git e GitHub da DIO

## 📖 Documentação: 
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Aulas:

| Aulas | Link |
|-------|-------- |
| Instalando Git no Windows | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao)
| Instalando Git no Linux | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Configurando Git | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Autenticnado via Token | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Autenticando via SSH | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Criando e Clonando Repositórios | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) | 
| Salvando Alterações no Repositório Local |[Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Desfazendo Alterações no Repositório Local | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Enviando e Baixando Alterações com o Repositório Remoto | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Trabalhando com Branches (Parte 1) | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |
| Trabalhando com Branches (Parte 2) | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) | 
| Dicas e Materiais de Apio | [Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) \ [Materiais de Apio](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao) |

## 📖 Resumo dos Comandos 

| Comando | Resumo |
|---------|--------|
| git init | Este comando cria um repositório Git vazio | 
| git clone URL | Clona um repositório em um diretório recém-criado |
| git status | Verifica o status do arquivo |
| git add nome do arquivo | Rastreia arquivos novos|
| mkdir nome do repositório | Cria um diretório simples no caminho/nome fornecido | 
| cd nome do repositório | É usado para entrar no repositório | 
| git commit -m "Descrição da alteração" | Salva as alterações feitas em determinado arquivo, armazenando em um repositório de controle de versões 
| git log | Exibe os registros de commit |
| touch "pasta do arquivo/nome do arquivo" | Cria um arquivo vazio em uma pasta especifica| 
| echo nome do conteudo > para onde será enviado | Envia um arquivo ou pasta para um lugar especifico |
| echo > pasta/arquivo | Remove o conteudo de uma pasta ou arquivos |
|git add . | Adiciona todos os arquivos na área de preparação | 
| rm -rf .git | Desfaz um repositório Git |
| git restore nome do arquivo | Dezfaz as alterções feitas em um arquivo |
|git commit --amend -m"Descrição do commit" | Altera o descrição do ultimo commit | 
| git reset --soft numero do commit | Isso deixa todos os seus arquivos alterados como "Changes to be committed" (Alterações que serão adicionadas ao commit), como o git status colocaria |
| git reset --mixed numero do commit | Os arquivos alterados são preservados, mas não marcados para um commit e relata o que não foi atualizado | 
| git reset --hard numero do commit | Redefine o índice e a árvore de trabalho. Os arquivo são simplesmente excluídos quando quaisquer arquivos ou diretórios não estejam rastreados no modo de escrita |
| git remote add origin URL | Conecta o repositório local com o repositório remoto |
| git push -u origin main | Envia as alterações do repositório local para o repositório reomoto |
| git pull | Puxa as alterações feitas no repositório remoto para o repesitório local

