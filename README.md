# Desafio de Projeto Git/Github-Repositório

**Cronograma de estudos:**

- 5 dias por semana x 4 horas por dia;
- Concomitantemente com outros cursos no youtube: https://www.youtube.com/watch?v=sTX0UEplF54&list=PLHz_AreHm4dkI2ZdjTwZA4mPMxWTfNSpR
- Pesquisa em fóruns 
- Leitura de artigos


**Git/Github**
- Baixar versão compatível Windows ou Linux: https://git-scm.com/
- Realizar cadastro de conta: https://github.com/
- Curso DIO: https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9?back=/track/santander-code-girls&tab=undefined&moduleId=undefined

**Comandos de navegação para Windows:**

- LS Lista as pastas do local;

- CD: Te leva as pastas

- CD .. Volta um nível

- Ctrl+L Limpa

- Tab Completa o que está escrevendo

- MKDIR Cria uma pasta

- ECHO Repete o que for digitado

- DEL Deleta o conteudo da dentro da pasta

- RMDIR /s /q Deleta a pasta

**Configuração**

**Geral**

- Setar usuário
git config --global user.name "ThyessaGoltara"

- Setar email
git config --global user.email thyessagoltara@outlook.com

- Listar configurações
git config --list

- Repositório Local

**Criar novo repositório:**

git init

- Verificar estado dos arquivos/diretórios

git status

- Adicionar arquivo/diretório (staged area)

Adicionar um arquivo em específico

git add meu_arquivo.txt

- Adicionar um diretório em específico

git add meu_diretorio

- Adicionar todos os arquivos/diretórios

git add .	

- Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)

git add -f arquivo_no_gitignore.txt

- Comitar arquivo/diretório

Comitar um arquivo

git commit meu_arquivo.txt

- Comitar vários arquivos

git commit meu_arquivo.txt meu_outro_arquivo.txt

- Comitar informando mensagem

git commit meuarquivo.txt -m "minha mensagem de commit"

- Remover arquivo/diretório

Remover arquivo

git rm meu_arquivo.txt

- Remover diretório

git rm -r diretorio
