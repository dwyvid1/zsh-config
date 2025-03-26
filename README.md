# 📜 Minhas Configurações do Zsh

Este repositório contém minhas configurações personalizadas para o **Zsh** no Linux. Aqui estão arquivos de configuração como `.zshrc`, temas, plugins e ajustes para melhorar a produtividade no terminal.

## 🚀 Recursos
- **Prompt Personalizado**: Um tema otimizado para produtividade e estética.
- **Plugins Essenciais**: Melhoram a experiência com sugestões, autocompletar e atalhos.
- **Aliases Úteis**: Comandos encurtados para agilizar tarefas comuns.
- **Integração com Oh My Zsh**: Um poderoso gerenciador de configurações do Zsh.

## 📥 Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seuusuario/zsh-config.git ~/.zsh-config
   ```
2. **Crie um backup do seu .zshrc atual**
   ```bash
   mv ~/.zshrc ~/.zshrc.backup
   ```
3. **Crie um link simbólico para o novo .zshrc**
   ```bash
   ln -s ~/.zsh-config/.zshrc ~/.zshrc
   ```
4. **Reinicie o terminal ou recarregue o Zsh**
   ```bash
   source ~/.zshrc
   ```

## 🔧 Dependências

Se você usa **Oh My Zsh**, pode instalá-lo com:
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Além disso, alguns plugins podem exigir ferramentas como `fzf`, `zsh-autosuggestions` e `zsh-syntax-highlighting`:
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```


