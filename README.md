## **Vim Core Configuration**

### **Basic Settings**
- **Leader Key**: `<Space>` - Your main prefix key for custom commands
- **Search Highlighting**: `vim.hlsearch: true` - Highlights all search matches
- **Line Numbers**: `"editor.lineNumbers": "relative"` - Shows relative line numbers (Vim-style)

---

## **Normal Mode Key Bindings** (`vim.normalModeKeyBindingsNonRecursive`)

### **Buffer Navigation**
- **`Shift+H`**: Go to previous buffer/tab (`:bprevious`)
- **`Shift+L`**: Go to next buffer/tab (`:bnext`)

### **Window/Split Management**
- **`<Space>+v`**: Create vertical split (`:vsplit`)
- **`<Space>+s`**: Create horizontal split (`:split`)

### **Pane Navigation** 
- **`<Space>+h`**: Focus left editor group
- **`<Space>+j`**: Focus editor group below
- **`<Space>+k`**: Focus editor group above  
- **`<Space>+l`**: Focus right editor group

### **File Operations**
- **`<Space>+w`**: Save file (`:w!`)
- **`<Space>+q`**: Quit (`:q!`)
- **`<Space>+x`**: Save and quit (`:x!`)

### **Code Navigation & Actions**
- **`[d`**: Go to previous diagnostic/error
- **`]d`**: Go to next diagnostic/error
- **`<Space>+ca`**: Show quick fix menu (code actions)
- **`gh`**: Show definition preview hover

### **Editor Actions**
- **`<Space>+f`**: Quick open file picker
- **`<Space>+p`**: Format document

---

## **Visual Mode Key Bindings** (`vim.visualModeKeyBindings`)

### **Indentation** (stays in visual mode)
- **`<`**: Decrease indentation of selected lines
- **`>`**: Increase indentation of selected lines

### **Line Movement** (stays in visual mode)
- **`J`**: Move selected lines down
- **`K`**: Move selected lines up

### **Comments**
- **`<Space>+c`**: Toggle comment on selected lines

---

## **Non-Vim VS Code Keybindings** (from keybindings.json)

### **Terminal Management**
- **`Cmd+Shift+A`**: Focus next terminal
- **`Cmd+Shift+B`**: Focus previous terminal
- **`Cmd+Shift+J`**: Toggle panel (terminal/problems/output)
- **`Cmd+Shift+N`**: New terminal (when in terminal)
- **`Cmd+Shift+W`**: Kill terminal (when in terminal)

### **File Explorer** 
- **`Cmd+E`**: Toggle sidebar / Focus file explorer
- **`n`**: New file (when explorer focused)
- **`r`**: Rename file (when explorer focused)
- **`Shift+N`**: New folder (when explorer focused)
- **`d`**: Delete file (when explorer focused)

### **Miscellaneous**
- **`Cmd+Shift+5`**: Match HTML/XML tag
- **`Cmd+Z`**: Toggle zen mode
