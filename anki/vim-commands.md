TARGET DECK
Vim::VSCode Keybindings

FILE TAGS
vim vscode keybindings

<!--
Archivo generado para Obsidian-to-Anki.
Cada bloque START..END crea una tarjeta "Basic (and reversed card)" en Anki,
que produce 2 cartas: comando -> descripcion y descripcion -> comando.
Fuente: settings.json (keybindings de la extension VSCodeVim).
Leader = <space>
-->

## Insert mode (no recursivo)

START
Basic (and reversed card)
**¿Qué hace `j` `k` en modo insert?**
Back: Sale a modo normal (equivale a `<ESC>`). Útil para no estirar el meñique al Esc.
Tags: insert-mode escape
END

## Normal mode (no recursivo) — atajos personales y Flash

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `p` en modo normal?**
Back: Abre la paleta de comandos de VSCode (`workbench.action.showCommands`).
Tags: normal-mode command-palette
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` (sola, en modo normal)?**
Back: Salta a un símbolo del archivo actual (`workbench.action.gotoSymbol`).
Tags: normal-mode symbol
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `w` en modo normal?**
Back: Guarda todos los archivos abiertos (`:wall`).
Tags: normal-mode save
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `w` `o` en modo normal?**
Back: Guarda solo el archivo actual (`:w`).
Tags: normal-mode save
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `/` en modo normal?**
Back: Quita el resaltado de la última búsqueda (`:noh`).
Tags: normal-mode search highlight
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `q` `a` en modo normal?**
Back: Cierra la ventana de VSCode (`workbench.action.closeWindow`).
Tags: normal-mode window quit
END

START
Basic (and reversed card)
**¿Qué hace `s` en modo normal?**
Back: Activa Flash / EasyMotion para saltar a cualquier lugar del archivo (mapea a `<leader><leader>/`).
Tags: normal-mode flash easymotion motion
END

START
Basic (and reversed card)
**¿Qué hace `S` (mayúscula) en modo normal?**
Back: Activa Flash Treesitter — saltar entre nodos del árbol sintáctico (mapea a `<leader><leader><leader>j`).
Tags: normal-mode flash treesitter motion
END

## Navegación de ventanas (splits)

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `h` en modo normal?**
Back: Mueve el foco a la ventana / split de la izquierda (`<C-W>h`).
Tags: normal-mode window navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `j` en modo normal?**
Back: Mueve el foco a la ventana / split de abajo (`<C-W>j`).
Tags: normal-mode window navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `k` en modo normal?**
Back: Mueve el foco a la ventana / split de arriba (`<C-W>k`).
Tags: normal-mode window navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `l` en modo normal?**
Back: Mueve el foco a la ventana / split de la derecha (`<C-W>l`).
Tags: normal-mode window navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `<Up>` en modo normal?**
Back: Aumenta la altura de la vista actual (`workbench.action.increaseViewHeight`).
Tags: normal-mode window resize
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `<Down>` en modo normal?**
Back: Reduce la altura de la vista actual (`workbench.action.decreaseViewHeight`).
Tags: normal-mode window resize
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `<Left>` en modo normal?**
Back: Reduce el ancho de la vista actual (`workbench.action.decreaseViewWidth`).
Tags: normal-mode window resize
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `<Right>` en modo normal?**
Back: Aumenta el ancho de la vista actual (`workbench.action.increaseViewWidth`).
Tags: normal-mode window resize
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `w` `w` en modo normal?**
Back: Cambia el foco al siguiente grupo de editores / otra ventana (`workbench.action.focusNextGroup`).
Tags: normal-mode window
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `w` en modo normal?**
Back: Cierra todos los editores del grupo actual (`workbench.action.closeEditorsInGroup`).
Tags: normal-mode window close
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `w` `-` en modo normal?**
Back: Divide la ventana hacia abajo (`workbench.action.splitEditorDown`).
Tags: normal-mode window split
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `w` `|` en modo normal?**
Back: Divide la ventana hacia la derecha (`workbench.action.splitEditorRight`).
Tags: normal-mode window split
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `-` en modo normal?**
Back: Divide la ventana hacia abajo — atajo corto (`workbench.action.splitEditorDown`).
Tags: normal-mode window split
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `|` en modo normal?**
Back: Divide la ventana hacia la derecha — atajo corto (`workbench.action.splitEditorRight`).
Tags: normal-mode window split
END

## Buffers

START
Basic (and reversed card)
**¿Qué hace `<Shift>` `h` en modo normal?**
Back: Va al buffer / pestaña anterior (`:bprev`).
Tags: normal-mode buffer navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Shift>` `l` en modo normal?**
Back: Va al buffer / pestaña siguiente (`:bnext`).
Tags: normal-mode buffer navigation
END

START
Basic (and reversed card)
**¿Qué hace `[` `b` en modo normal?**
Back: Va al buffer anterior (`:bprev`) — versión bracket.
Tags: normal-mode buffer navigation
END

START
Basic (and reversed card)
**¿Qué hace `]` `b` en modo normal?**
Back: Va al buffer siguiente (`:bnext`) — versión bracket.
Tags: normal-mode buffer navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `b` `b` en modo normal?**
Back: Alterna al buffer usado más recientemente — Switch to Other Buffer (`workbench.action.quickOpenPreviousRecentlyUsedEditorInGroup`).
Tags: normal-mode buffer toggle
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `` ` `` (backtick) en modo normal?**
Back: Alterna al buffer usado más recientemente — atajo corto de Switch to Other Buffer.
Tags: normal-mode buffer toggle
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `b` `p` en modo normal?**
Back: Fija (pin) el editor actual cuando no está fijado (`workbench.action.pinEditor`).
Tags: normal-mode buffer pin
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `b` `u` en modo normal?**
Back: Desfija (unpin) el editor actual cuando ya está fijado (`workbench.action.unpinEditor`).
Tags: normal-mode buffer pin
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `b` `P` (mayúscula) en modo normal?**
Back: Cierra todos los editores no fijados — Delete non-pinned buffers (`workbench.action.closeAllEditors`).
Tags: normal-mode buffer close
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `b` `d` en modo normal?**
Back: Cierra el buffer actual — Delete Buffer (`workbench.action.closeActiveEditor`).
Tags: normal-mode buffer close
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `b` `D` (mayúscula) en modo normal?**
Back: Cierra el buffer descartando cambios — Delete Buffer Force (`workbench.action.revertAndCloseActiveEditor`).
Tags: normal-mode buffer close force
END

## Tabs

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<Tab>` `l` en modo normal?**
Back: Salta a la última pestaña del grupo (`workbench.action.lastEditorInGroup`).
Tags: normal-mode tab
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<Tab>` `f` en modo normal?**
Back: Salta a la primera pestaña del grupo (`workbench.action.firstEditorInGroup`).
Tags: normal-mode tab
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<Tab>` `<Tab>` en modo normal?**
Back: Crea una pestaña nueva sin nombre (`workbench.action.files.newUntitledFile`).
Tags: normal-mode tab new
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<Tab>` `]` en modo normal?**
Back: Va a la pestaña siguiente (`workbench.action.nextEditor`).
Tags: normal-mode tab navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<Tab>` `[` en modo normal?**
Back: Va a la pestaña anterior (`workbench.action.previousEditor`).
Tags: normal-mode tab navigation
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<Tab>` `d` en modo normal?**
Back: Cierra la pestaña activa (`workbench.action.closeActiveEditor`).
Tags: normal-mode tab close
END

## LSP / Code

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `d` en modo normal?**
Back: Muestra los diagnósticos / hover de la línea actual — Line Diagnostics (`editor.action.showHover`).
Tags: normal-mode lsp diagnostics
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `l` en modo normal?**
Back: Abre el panel Output con info del LSP (`workbench.action.output.toggleOutput`).
Tags: normal-mode lsp output
END

START
Basic (and reversed card)
**¿Qué hace `g` `d` en modo normal?**
Back: Va a la definición del símbolo bajo el cursor (`editor.action.revealDefinition`).
Tags: normal-mode lsp goto
END

START
Basic (and reversed card)
**¿Qué hace `g` `r` en modo normal?**
Back: Muestra todas las referencias del símbolo (`editor.action.goToReferences`).
Tags: normal-mode lsp references
END

START
Basic (and reversed card)
**¿Qué hace `g` `D` (mayúscula) en modo normal?**
Back: Va a la declaración del símbolo (`editor.action.revealDeclaration`).
Tags: normal-mode lsp goto
END

START
Basic (and reversed card)
**¿Qué hace `g` `I` (mayúscula) en modo normal?**
Back: Va a la implementación del símbolo (`editor.action.goToImplementation`).
Tags: normal-mode lsp goto
END

START
Basic (and reversed card)
**¿Qué hace `g` `y` en modo normal?**
Back: Va a la definición de tipo del símbolo — Type Definition (`editor.action.goToTypeDefinition`).
Tags: normal-mode lsp goto type
END

START
Basic (and reversed card)
**¿Qué hace `K` (mayúscula) en modo normal?**
Back: Muestra el hover (documentación / tipos) del símbolo bajo el cursor (`editor.action.showHover`).
Tags: normal-mode lsp hover
END

START
Basic (and reversed card)
**¿Qué hace `g` `K` (mayúscula) en modo normal?**
Back: Muestra Signature Help / hints de parámetros de la función actual (`editor.action.triggerParameterHints`).
Tags: normal-mode lsp signature
END

START
Basic (and reversed card)
**¿Qué hace `g` `w` en modo normal?**
Back: Busca la palabra bajo el cursor en el archivo (mapea a `*`).
Tags: normal-mode search word
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `f` en modo normal?**
Back: Formatea el documento entero — Format Document (`editor.action.formatDocument`).
Tags: normal-mode lsp format
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `F` (mayúscula) en modo normal?**
Back: Formatea solo el rango seleccionado — Format Range (`editor.action.formatSelection`).
Tags: normal-mode lsp format
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `a` en modo normal?**
Back: Muestra Code Actions / Quick Fix para el símbolo actual (`editor.action.quickFix`).
Tags: normal-mode lsp code-action
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `A` (mayúscula) en modo normal?**
Back: Muestra Source Action / Quick Fix (`editor.action.quickFix`).
Tags: normal-mode lsp code-action
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `c` `r` en modo normal?**
Back: Renombra el símbolo bajo el cursor en todo el proyecto (`editor.action.rename`).
Tags: normal-mode lsp rename
END

## Diagnostics

START
Basic (and reversed card)
**¿Qué hace `]` `d` en modo normal?**
Back: Salta al siguiente diagnóstico (error/warning) en el archivo (`editor.action.marker.next`).
Tags: normal-mode diagnostics
END

START
Basic (and reversed card)
**¿Qué hace `[` `d` en modo normal?**
Back: Salta al diagnóstico anterior en el archivo (`editor.action.marker.prev`).
Tags: normal-mode diagnostics
END

START
Basic (and reversed card)
**¿Qué hace `]` `e` en modo normal?**
Back: Salta al siguiente error (`editor.action.marker.next`).
Tags: normal-mode diagnostics error
END

START
Basic (and reversed card)
**¿Qué hace `[` `e` en modo normal?**
Back: Salta al error anterior (`editor.action.marker.prev`).
Tags: normal-mode diagnostics error
END

START
Basic (and reversed card)
**¿Qué hace `]` `w` en modo normal?**
Back: Salta al siguiente warning (`editor.action.marker.next`).
Tags: normal-mode diagnostics warning
END

START
Basic (and reversed card)
**¿Qué hace `[` `w` en modo normal?**
Back: Salta al warning anterior (`editor.action.marker.prev`).
Tags: normal-mode diagnostics warning
END

START
Basic (and reversed card)
**¿Qué hace `]` `q` en modo normal?**
Back: Siguiente quickfix / item de Trouble — usa el navegador de markers (`editor.action.marker.next`).
Tags: normal-mode quickfix
END

START
Basic (and reversed card)
**¿Qué hace `[` `q` en modo normal?**
Back: Quickfix / item de Trouble anterior (`editor.action.marker.prev`).
Tags: normal-mode quickfix
END

## UI Toggle

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `s` en modo normal?**
Back: Activa/desactiva el corrector ortográfico (`cSpell.toggleEnableSpellChecker`).
Tags: normal-mode ui-toggle spell
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `w` en modo normal?**
Back: Activa/desactiva Word Wrap (`editor.action.toggleWordWrap`).
Tags: normal-mode ui-toggle wrap
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `d` en modo normal?**
Back: Activa/desactiva Error Lens — diagnósticos inline (`errorLens.toggle`).
Tags: normal-mode ui-toggle diagnostics
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `h` en modo normal?**
Back: Activa/desactiva Inlay Hints (`editor.action.toggleInlayHints`).
Tags: normal-mode ui-toggle hints
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `r` en modo normal?**
Back: Recarga la ventana de VSCode (`workbench.action.reloadWindow`).
Tags: normal-mode ui-toggle reload
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `n` en modo normal?**
Back: Limpia todas las notificaciones (`notifications.clearAll`).
Tags: normal-mode ui-toggle notifications
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `u` `C` (mayúscula) en modo normal?**
Back: Abre el selector de tema con preview (`workbench.action.selectTheme`).
Tags: normal-mode ui-toggle theme
END

## Git

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `g` `g` en modo normal?**
Back: Abre la vista Source Control / SCM — Lazygit root (`workbench.view.scm`).
Tags: normal-mode git
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `g` `G` (mayúscula) en modo normal?**
Back: Abre la vista Source Control / SCM — Lazygit cwd (`workbench.view.scm`).
Tags: normal-mode git
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `g` `c` en modo normal?**
Back: Abre la vista de commits / SCM (`workbench.view.scm`).
Tags: normal-mode git commits
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `g` `s` en modo normal?**
Back: Abre la vista de status / SCM (`workbench.view.scm`).
Tags: normal-mode git status
END

## Quit / Sessions

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `q` `q` en modo normal?**
Back: Cierra completamente VSCode — Quit all (`workbench.action.quit`).
Tags: normal-mode quit
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `q` `s` en modo normal?**
Back: Restaura una sesión anterior — abre lista Recent (`workbench.action.openRecent`).
Tags: normal-mode session
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `q` `l` en modo normal?**
Back: Reabre el editor cerrado más recientemente — Restore Last Session (`workbench.action.reopenClosedEditor`).
Tags: normal-mode session
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `L` (mayúscula) en modo normal?**
Back: Muestra las release notes / changelog de VSCode (`update.showCurrentReleaseNotes`).
Tags: normal-mode info
END

## Terminal

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `t` en modo normal?**
Back: Crea una terminal nueva como editor — Terminal root (`workbench.action.createTerminalEditor`).
Tags: normal-mode terminal
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `T` (mayúscula) en modo normal?**
Back: Crea una terminal nueva como editor — Terminal cwd (`workbench.action.createTerminalEditor`).
Tags: normal-mode terminal
END

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `/` en modo normal?**
Back: Muestra/oculta el panel de terminal (`workbench.action.terminal.toggleTerminal`).
Tags: normal-mode terminal toggle
END

## Files / Explorer

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `n` en modo normal?**
Back: Crea un archivo nuevo sin título (`workbench.action.files.newUntitledFile`).
Tags: normal-mode file new
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `e` en modo normal?**
Back: Revela el archivo activo en el Explorer — Neo-tree root (`workbench.files.action.showActiveFileInExplorer`).
Tags: normal-mode explorer
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `E` (mayúscula) en modo normal?**
Back: Alterna la visibilidad del Explorer — Neo-tree cwd (`workbench.explorer.fileView.toggleVisibility`).
Tags: normal-mode explorer
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `e` (sola) en modo normal?**
Back: Revela el archivo activo en el Explorer — atajo corto Neo-tree root (`workbench.files.action.showActiveFileInExplorer`).
Tags: normal-mode explorer
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `E` (mayúscula sola) en modo normal?**
Back: Alterna la visibilidad del Explorer — atajo corto Neo-tree cwd (`workbench.explorer.fileView.toggleVisibility`).
Tags: normal-mode explorer
END

## Búsqueda y Telescope (Find/Quick Open)

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `<space>` en modo normal?**
Back: Abre Find Files / Quick Open desde la raíz del proyecto (`workbench.action.quickOpen`).
Tags: normal-mode search files
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `f` en modo normal?**
Back: Find Files (root dir) — abre Quick Open (`workbench.action.quickOpen`).
Tags: normal-mode search files
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `F` (mayúscula) en modo normal?**
Back: Find Files (cwd) — abre Quick Open (`workbench.action.quickOpen`).
Tags: normal-mode search files
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `b` en modo normal?**
Back: Buffers — abre Quick Open con la lista de buffers (`workbench.action.quickOpen`).
Tags: normal-mode search buffer
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `r` en modo normal?**
Back: Recent — abre la lista de archivos recientes vía Quick Open (`workbench.action.quickOpen`).
Tags: normal-mode search recent
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `R` (mayúscula) en modo normal?**
Back: Recent (cwd) — abre la lista de archivos recientes vía Quick Open (`workbench.action.quickOpen`).
Tags: normal-mode search recent
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `f` `p` en modo normal?**
Back: Projects — abre la lista de proyectos recientes (`workbench.action.openRecent`).
Tags: normal-mode search project
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `:` en modo normal?**
Back: Abre la paleta de comandos / historial de comandos (`workbench.action.showCommands`).
Tags: normal-mode command-palette
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `g` en modo normal?**
Back: Grep en el proyecto (root dir) — Find in Files (`workbench.action.findInFiles`).
Tags: normal-mode search grep
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `G` (mayúscula) en modo normal?**
Back: Grep en cwd — Find in Files (`workbench.action.findInFiles`).
Tags: normal-mode search grep
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `w` en modo normal?**
Back: Busca la palabra bajo el cursor en el proyecto — Word root (`workbench.action.findInFiles`).
Tags: normal-mode search word
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `W` (mayúscula) en modo normal?**
Back: Busca la palabra bajo el cursor en cwd — Word cwd (`workbench.action.findInFiles`).
Tags: normal-mode search word
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `b` en modo normal?**
Back: Busca / reemplaza dentro del buffer actual (`editor.action.startFindReplaceAction`).
Tags: normal-mode search buffer
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `r` en modo normal?**
Back: Replace in files (Spectre) — Find & Replace (`editor.action.startFindReplaceAction`).
Tags: normal-mode search replace spectre
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `s` en modo normal?**
Back: Goto Symbol del archivo actual (`workbench.action.gotoSymbol`).
Tags: normal-mode search symbol
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `S` (mayúscula) en modo normal?**
Back: Goto Symbol del workspace entero (`workbench.action.showAllSymbols`).
Tags: normal-mode search symbol workspace
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `C` (mayúscula) en modo normal?**
Back: Lista de comandos — abre la paleta (`workbench.action.showCommands`).
Tags: normal-mode search command-palette
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `d` en modo normal?**
Back: Document Diagnostics — abre la vista Problems (`workbench.actions.view.problems`).
Tags: normal-mode search diagnostics
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `D` (mayúscula) en modo normal?**
Back: Workspace Diagnostics — abre la vista Problems (`workbench.actions.view.problems`).
Tags: normal-mode search diagnostics
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `h` en modo normal?**
Back: Help Pages — abre la documentación de VSCode (`workbench.action.openDocumentationUrl`).
Tags: normal-mode help
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `k` en modo normal?**
Back: Key Maps — abre la paleta de comandos (`workbench.action.showCommands`).
Tags: normal-mode keybindings
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `n` `l` en modo normal?**
Back: Noice Last Message — abre/oculta el panel Output (`workbench.action.output.toggleOutput`).
Tags: normal-mode noice output
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `n` `h` en modo normal?**
Back: Noice History — abre/oculta el panel Output (`workbench.action.output.toggleOutput`).
Tags: normal-mode noice output
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `s` `n` `a` en modo normal?**
Back: Noice All — abre/oculta el panel Output (`workbench.action.output.toggleOutput`).
Tags: normal-mode noice output
END

## Treesitter selection

START
Basic (and reversed card)
**¿Qué hace `<Ctrl>` `<space>` en modo normal?**
Back: Expande la selección semánticamente — Increment selection (`editor.action.smartSelect.expand`).
Tags: normal-mode selection treesitter
END

START
Basic (and reversed card)
**¿Qué hace `<BackSpace>` en modo normal?**
Back: Reduce la selección semánticamente — Decrement selection (`editor.action.smartSelect.shrink`).
Tags: normal-mode selection treesitter
END

## Lazy / Extensions

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `l` en modo normal?**
Back: Abre la vista de Extensiones — Lazy (`workbench.view.extensions`).
Tags: normal-mode extensions
END

## Vim-illuminate (referencias de palabra)

START
Basic (and reversed card)
**¿Qué hace `]` `]` en modo normal?**
Back: Salta a la siguiente referencia / aparición de la palabra bajo el cursor (`editor.action.wordHighlight.next`).
Tags: normal-mode reference illuminate
END

START
Basic (and reversed card)
**¿Qué hace `[` `[` en modo normal?**
Back: Salta a la referencia anterior de la palabra bajo el cursor (`editor.action.wordHighlight.prev`).
Tags: normal-mode reference illuminate
END

## Debug (DAP)

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `B` (mayúscula) en modo normal?**
Back: Pone un breakpoint condicional en la línea actual (`editor.debug.action.conditionalBreakpoint`).
Tags: normal-mode debug breakpoint
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `b` en modo normal?**
Back: Activa/desactiva un breakpoint en la línea actual (`editor.debug.action.toggleBreakpoint`).
Tags: normal-mode debug breakpoint
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `c` en modo normal?**
Back: Continue — sigue la ejecución del debugger (`workbench.action.debug.continue`).
Tags: normal-mode debug
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `C` (mayúscula) en modo normal?**
Back: Run to Cursor — ejecuta hasta la línea del cursor (`editor.debug.action.runToCursor`).
Tags: normal-mode debug
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `i` en modo normal?**
Back: Step Into — entra dentro de la función (`workbench.action.debug.stepInto`).
Tags: normal-mode debug step
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `l` en modo normal?**
Back: Run Last — inicia la última configuración de debug (`workbench.action.debug.start`).
Tags: normal-mode debug
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `o` en modo normal?**
Back: Step Out — sale de la función actual (`workbench.action.debug.stepOut`).
Tags: normal-mode debug step
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `O` (mayúscula) en modo normal?**
Back: Step Over — pasa a la siguiente línea sin entrar a funciones (`workbench.action.debug.stepOver`).
Tags: normal-mode debug step
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `p` en modo normal?**
Back: Pause — pausa la ejecución del debugger (`workbench.action.debug.pause`).
Tags: normal-mode debug
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `r` en modo normal?**
Back: Toggle REPL del debugger (`workbench.debug.action.toggleRepl`).
Tags: normal-mode debug repl
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `t` en modo normal?**
Back: Terminate — detiene la sesión de debug (`workbench.action.debug.stop`).
Tags: normal-mode debug
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `u` en modo normal?**
Back: Abre la vista de Debug — Dap UI (`workbench.view.debug`).
Tags: normal-mode debug ui
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `d` `e` en modo normal?**
Back: Eval — manda la selección al REPL del debugger (`editor.debug.action.selectionToRepl`).
Tags: normal-mode debug eval
END

## Tests (Neotest)

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `t` en modo normal?**
Back: Run File — corre los tests del archivo actual (`testing.runCurrentFile`).
Tags: normal-mode test
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `T` (mayúscula) en modo normal?**
Back: Run All Test Files (`testing.runAll`).
Tags: normal-mode test
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `r` en modo normal?**
Back: Run Nearest — corre el test bajo el cursor (`testing.runAtCursor`).
Tags: normal-mode test
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `s` en modo normal?**
Back: Toggle Summary — abre la vista Testing (`workbench.view.testing`).
Tags: normal-mode test ui
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `o` en modo normal?**
Back: Show Output — muestra el output más reciente de tests (`testing.showMostRecentOutput`).
Tags: normal-mode test
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `S` (mayúscula) en modo normal?**
Back: Stop — cancela la ejecución de tests (`testing.cancelRun`).
Tags: normal-mode test
END

START
Basic (and reversed card)
**¿Qué hace `<Leader>` `t` `d` en modo normal?**
Back: Debug Nearest — debuggea el test bajo el cursor (`testing.debugAtCursor`).
Tags: normal-mode test debug
END

## Visual mode

START
Basic (and reversed card)
**¿Qué hace `<` (menor que) en modo visual?**
Back: Desindenta el bloque seleccionado y mantiene la selección (mapea a `<gv`). Permite desindentar varias veces seguidas.
Tags: visual-mode indent
END

START
Basic (and reversed card)
**¿Qué hace `>` (mayor que) en modo visual?**
Back: Indenta el bloque seleccionado y mantiene la selección (mapea a `>gv`). Permite indentar varias veces seguidas.
Tags: visual-mode indent
END
