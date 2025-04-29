# Minha Configuração Do VSCode

---

## ⚙️ Aparência e Interface

### Mostra as setas ao lado das pastas no explorador de arquivos
```bash
"symbols.hidesExplorerArrows": false
```

### Abre um novo arquivo em branco ao iniciar o VS Code
```bash
"workbench.startupEditor": "newUntitledFile"
```

### Nível de zoom da janela.
```bash
"window.zoomLevel": 0
```

### Exibe apenas o nome do arquivo na aba (sem o caminho completo)
```bash
"workbench.editor.labelFormat": "short"
```

### Desativa a compactação de pastas com apenas um subnível no Explorer (mostra estrutura mais expandida)
```bash
"explorer.compactFolders": false
```

### Oculta a barra de status inferior do VS Code.
```bash
"workbench.statusBar.visible": false
```

### Usa uma barra de título customizada (estilo integrado ao tema)
```bash
"window.titleBarStyle": "custom"
```

### Oculta o controle de layout (normalmente aparece no canto superior esquerdo)
```bash
"workbench.layoutControl.enabled": false
```

### Remove o botão de comandos rápidos do topo da interface
```bash
"window.commandCenter": false
```

### Evita pedir confirmação ao fechar espaços de trabalho não salvos
```bash
"window.confirmSaveUntitledWorkspace": false
```

---

## 🖋️ Editor de Código

### Define a fonte do editor como JetBrains Mono
```bash
"editor.fontFamily": "JetBrains Mono"
```

### Tamanho da fonte no editor
```bash
"editor.fontSize": 14
```

### Altura entre linhas no editor (mais espaçado que o padrão)
```bash
"editor.lineHeight": 1.8
```

### Destaca a linha atual apenas na margem esquerda (gutter)
```bash
"editor.renderLineHighlight": "gutter"
```

### Ativa ligaduras tipográficas (ex: !==, => se tornam símbolos)
```bash
"editor.fontLigatures": true
```

### Desativa realce semântico (menos cores específicas para variáveis/tipos)
```bash
"editor.semanticHighlighting.enabled": false
```

### Desativa o minimapa (pré-visualização à direita do código)
```bash
"editor.minimap.enabled": false
```

### Oculta as barras de rolagem vertical e horizontal
```bash
"editor.scrollbar.vertical": "hidden",
"editor.scrollbar.horizontal": "hidden"
```

### Formata o código automaticamente ao salvar o arquivo
```bash
"editor.formatOnSave": true
```

### Usa indentação automática completa com base no conteúdo
```bash
"editor.autoIndent": "full"
```

### Quebra linhas longas automaticamente para caber na tela
```bash
"editor.wordWrap": "on"
```

---

## 🧭 Navegação e Organização

### Oculta o caminho de navegação (breadcrumbs) no topo do editor
```bash
"breadcrumbs.enabled": false
```

---

## 🧪 Terminal Integrado

### Tamanho da fonte do terminal
```bash
"terminal.integrated.fontSize": 14
```

### Fonte usada no terminal (versão com ícones Nerd Font)
```bash
"terminal.integrated.fontFamily": "JetBrainsMono Nerd Font"
```

### Define o terminal padrão como o Prompt de Comando (cmd) no Windows
```bash
"terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe"
```

---

## 💻 Extensões e Temas

### Oculta as mensagens informativas do Live Server
```bash
"liveServer.settings.donotShowInfoMsg": true
```

### Define o tema de ícones do VS Code
```bash
"workbench.iconTheme": "Monokai Pro Icons"
```

### Define o tema de cores escuro e vívido chamado "Bearded Theme Vivid Black"
```bash
"workbench.colorTheme": "Bearded Theme Vivid Black"
```

---

## 🔁 AutoSave e Perfil

### Salva arquivos automaticamente após um pequeno tempo de inatividade
```bash
"files.autoSave": "afterDelay"
```

### Aplica essas configurações a todos os perfis ativos do VS Code
```bash
"workbench.settings.applyToAllProfiles": [...]
```

---

## 🧩 Customizações Avançadas (apc)

### Usam a extensão ou modificação apc para alterar visualmente o VS Code: altura dos cabeçalhos, posição dos botões da janela, padding interno dos painéis e estilização da fonte geral (fonte Inter)
```bash
"apc.electron": { ... },
"apc.header": { ... },
"apc.listRow": { ... },
"apc.font.family": "Inter",
"apc.stylesheet": { ... }
```