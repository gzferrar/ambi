# Ambiente de Desenvolvimento

## Sobre
Configurando nosso ambiente de desenvolvimento, com algumas ferramentas fundamentais

## Preparando o ambiente com o VS CODE
Após instalar o Visual Studio Code podemos instalar as seguintes extenções. Como instalar:
- Abra o seu VS Code;
- Clique na opção Extensions e na caixa de pesquisa digite o nome ou ID* da extensão que você quer baixar;
– Selecione na lista a extensão desejada e, na página que abrirá à direita, clique em Install.

### As Extenções 
- **[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)** Essa extensão faz a correção ortográfica no nosso código (por padrão, corrige apenas o inglês);
- **[Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese)** (adora ele pois sou **disléxico**)É um dicionário de português para que a extensão Code Spell Checker consiga fazer também a correção ortográfica em Português;
- **[Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)** Essa extensão reconhece cores CSS escritas em qualquer lugar do nosso código mas apenas cores em hexadecimal. Pode parecer perfumaria mas é bastante útil, já que reconhece as cores diretamente no código;
- **[CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)** Essa é uma extensão que ajuda com o autocomplete;
- **[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)** O Tabnine é uma extensão que usa de inteligência artificial para identificar o contexto do código e fornecer o autocomplete. Suporta diversas linguagens incluindo JavaScript e TypeScript. Existe uma versão paga mas também é possível usar a versão gratuita da extensão;
- **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** (muito bom) O Live Server implementa um “live reload” – ou seja, um recarregamento ao vivo – para páginas web estáticas ou dinâmicas. Acabou o **F5**;
- **[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)** O Material Icon Theme, é o que mais gostei, traz uma boa variedade de temas para ícones, inclusive podendo padronizar mais amplamente as pastas. Ele é tão completo que traz padronização até mesmo para as pastas src, algo que nem sempre é possível encontrar;
- ![image](https://user-images.githubusercontent.com/4933034/124986295-da82c080-e011-11eb-8661-9646a8e0854a.png)

- **[Drácula Oficial](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)** Meu tema preferido do VS Code. Não é por causa que adoro o livro Drácula!🧛🏻‍♂️
- ***[Fonte JetBrains Mono](https://www.jetbrains.com/lp/mono/)*** Eu uso essa fonte é que ela possui suporte às font ligatures que é uma funcionalidade que permite combinarmos símbolos para formar um novo.





```
{


 // Configurações da fonte JetBrains Mono
 "editor.fontFamily": "JetBrains Mono",
 "editor.fontLigatures": true,

 // Demais configurações
 "workbench.colorTheme": "Omni",
 "workbench.iconTheme": "material-icon-theme",
 "workbench.startupEditor": "newUntitledFile",

 "explorer.compactFolders": false,
 "editor.renderLineHighlight": "gutter",
 "workbench.editor.labelFormat": "short",
 "extensions.ignoreRecommendations": true,

 "javascript.updateImportsOnFileMove.enabled": "never",
 "typescript.updateImportsOnFileMove.enabled": "never",

 "breadcrumbs.enabled": true,
 "editor.parameterHints.enabled": false,
   "editor.formatOnSave": true,
 "explorer.confirmDragAndDrop": false,
 "explorer.confirmDelete": false,
 
 "emmet.syntaxProfiles": { "javascript": "jsx" },
 "emmet.includeLanguages": { "javascript": "javascriptreact" },

 "javascript.suggest.autoImports": true,
"typescript.suggest.autoImports": true,
"window.zoomLevel": -2,
"workbench.editorAssociations": {
  "*.srm": "default"
},
"liveServer.settings.donotVerifyTags": true,
}
````
