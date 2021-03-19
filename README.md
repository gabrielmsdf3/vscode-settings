/*{
    "workbench.iconTheme": "material-icon-theme",
    "powermode.enabled": true,
    "powermode.explosionFrequency": 1,
    "powermode.explosionSize": 5,
    "powermode.presets": "flames",
    "workbench.colorTheme": "Dracula Soft",
    "eslint.codeAction.showDocumentation": {

        "enable": false
    },
}*/

{
    // Define o tema do VSCode
    "workbench.colorTheme": "Dracula",
    // Aumenta a fonte do terminal
    "terminal.integrated.fontSize": 14,
    // Define o tema dos icones no sidebar
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    "powermode.enabled": true,
    "powermode.explosionFrequency": 1,
    "powermode.explosionSize": 5,
    "powermode.presets": "flames",
    "editor.fontSize": 18,
    "editor.lineHeight": 30,
    "editor.tabSize": 2,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
  
    "[typescript]": {
      // "editor.formatOnSave": true,
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
  
    "[javascript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    
    "[typescriptreact]": {
      // "editor.formatOnSave": false
    },
    // Retira a funcionalidade das pastas sobrepostas
    "explorer.compactFolders": false,
    // Aplica um sinal visual na esquerda da linha selecionada
    "editor.renderLineHighlight": "none",
    // Desativa as linhas
    // "editor.lineNumbers": "off",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations": true,
    // Desligar a tentativa de importar os arquivos
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",
    // Desliga o minimap do VSCode
    "editor.minimap.enabled": false,
    // Aplica Breadcrumbs no arquivo
    "breadcrumbs.enabled": false,
    // Box de ajuda do VSCode
    "editor.parameterHints.enabled": false,
    // Aplica linhas verticais para lembrar de quebrar linha em códigos muito grandes
    "editor.rulers": [100, 120],
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "emmet.syntaxProfiles": { "javascript": "jsx" },
    "emmet.includeLanguages": { "javascript": "javascriptreact" },
    "editor.codeActionsOnSave": {
      "source.fixAll": true,
      "source.fixAll.eslint": true
    },
  
    "eslint.options": {
      "experimentalDecorators": true
    },
  
    // Usar terminal do zsh no VSCode
    "terminal.integrated.shell.osx": "/bin/zsh",
  
    "files.associations": {
      ".sequelizerc": "javascript",
      ".stylelintrc": "json",
      ".prettierrc": "json",
      ".eslintrc": "json",
    },
  
    "git.enableSmartCommit": true,
  
    "editor.renderControlCharacters": false,
    "workbench.activityBar.visible": false,
    "editor.renderWhitespace": "none",
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  
    "typescript.tsserver.log": "verbose",
    "javascript.suggest.autoImports": true,
    "typescript.suggest.autoImports": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "screencastMode.onlyKeyboardShortcuts": true,
    "material-icon-theme.activeIconPack": "react_redux",
    "material-icon-theme.folders.associations": {
      "infra": "app",
      "infrastructure": "app",
      "entities": "class",
      "schemas": "class",
      "enums": "syntax",
      "exceptions": "error",
      "listeners": "event",
      "typeorm": "database",
      "repositories": "mappings",
      "http": "container",
      "migrations": "tools",
      "start": "core",
      "modules": "components",
      "domains": "components",
      "implementations": "core",
      "dtos": "typescript",
      "dto": "typescript",
      "fakes": "mock",
      "seeds": "dump",
      "interfaces": "include",
    },
  
    "material-icon-theme.files.associations": {
      "ormconfig.json": "database",
      "tsconfig.json": "tune",
      "ormconfig.js": "database",
      "tsconfig.js": "tune",
      "routes.js": "routing",
    },
    "workbench.sideBar.location": "left",
    "editor.largeFileOptimizations": false,
    "eslint.format.enable": true,
    "edge.format.enable": true,
    "prettier.semi": false,
    "[javascriptreact]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "workbench.statusBar.visible": false,
  }
