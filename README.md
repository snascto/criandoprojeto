# 🛠️ Criador de Estrutura de Projetos + GitHub CLI

Este é um script Shell interativo que automatiza a criação de projetos com estrutura padrão, inicialização do Git, licenciamento e publicação no GitHub via CLI.

## 🚀 Funcionalidades

- Criação de estrutura base: `README`, `LICENSE`, `CONTACT`, `src/`, `docs/`
- Suporte a subpastas e personalização
- Inicialização do Git local
- Criação de repositório remoto via `gh` CLI
- Push automático via SSH
- Compatível com **Windows (Git Bash)** e **Linux**

## 📦 Requisitos

- Git instalado
- [GitHub CLI (`gh`)](https://cli.github.com/) autenticado via SSH
- Bash Shell (Linux ou Git Bash para Windows)

## 📥 Instalação

```bash
git clone git@github.com:SEU_USUARIO/criador-projeto-github.git
cd criador-projeto-github
chmod +x criador_projeto_estruturado_github.sh
