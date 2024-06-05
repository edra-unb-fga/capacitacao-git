# Capacitação Git\
Repositório dedicado à capacitação dos trainees de 2024/1 ao uso do Git

## Introdução ao Git e Controle de Versão
- **Controle de versão:** Sistema que registra alterações em um arquivo ou conjunto de arquivos ao longo do tempo para que você possa revisitar versões específicas posteriormente.
- **Git:** Sistema de controle de versão distribuído, amplamente usado na indústria de software.
- **Vantagens do Git:** Histórico completo, ramificação e mesclagem eficientes, distribuição e colaboração.

## Instalação e Configuração do Git
### Instalação
- **Windows:** Baixe e instale [Git para Windows](https://gitforwindows.org/).
- **macOS:** Instale via Homebrew (`brew install git`).
- **Linux:** Use o gerenciador de pacotes da sua distribuição (e.g., `sudo apt-get install git` para Debian/Ubuntu).

### Configuração Inicial\
Configurar nome de usuário e e-mail:
```bash
git config --global user.name "Seu Nome"\
git config --global user.email "seuemail@example.com"\
```

## Comandos Básicos do Git
- **`git init`:** Inicializa um novo repositório Git.
- **`git clone`:** Clona um repositório existente.
- **`git status`:** Verifica o status do repositório.
- **`git add`:** Adiciona mudanças ao staging area.
- **`git commit`:** Salva mudanças no repositório.
- **`git log`:** Visualiza o histórico de commits.

## Trabalhando com Branches\
- **Branch:** Uma linha separada de desenvolvimento.
- **Criando uma branch:**
  ```bash
  git branch nome-da-branch
  ```
- **Mudando para uma branch:**
  ```bash
  git checkout nome-da-branch
  ```
- **Mesclando branches:**
  ```bash
  git merge nome-da-branch
  ```
- **Resolvendo conflitos de merge:** Edite os arquivos em conflito e finalize o merge.

## Remotos e Colaboração\
- **Repositórios remotos:** Versões do seu projeto hospedadas na internet ou rede.
- **Adicionando um repositório remoto:**
  ```bash
  git remote add origin https://github.com/usuario/repositorio.git
  ```
- **Atualizando o repositório local:**
  ```bash
  git fetch
  git pull
  ```
- **Enviando mudanças para o remoto:**
  ```bash
  git push origin branch
  ```

## Práticas Recomendadas
- **Mensagens de commit claras e descritivas.**
- **Realizar commits frequentes.**
- **Estrutura de branches:** Utilize branches para novas features, correções e releases.
- **Tags:** Marque releases com tags:
  ```bash
  git tag -a v1.0 -m "Versão 1.0"
  git push origin v1.0
  ```

## Ferramentas Gráficas e Integração com IDEs
- **Ferramentas Gráficas:** GitKraken, SourceTree.
- **Integração com IDEs:** Visual Studio Code, IntelliJ IDEA, Eclipse.

## Recursos Adicionais
- [Documentação Oficial do Git](https://git-scm.com/doc)
- Tutoriais e vídeos no YouTube
- Prática com repositórios de exemplo no GitHub
-
