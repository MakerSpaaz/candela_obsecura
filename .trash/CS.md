---
multiSelect2: []
---
![[800px-Candela_Obscura_wordmark-2532188816.png|250]]
Name : `INPUT[text:exampleProperty]`

Pronouns: `INPUT[inlineSelect(option(She/Her), option(He/Him), option(They/Them)):exampleProperty]`

Circle: `INPUT[text:exampleProperty]`



  
option 1

option 2

option 3

option 3

option 2

`[INPUT[multiSelect(   option(option 1),   option(option 2),   option(option 3),   option(option 3),   option(option 2),   showcase   ):multiSelect2]](https://www.moritzjung.dev/obsidian-meta-bind-plugin-docs/reference/inputfields/multiselect/)`






```meta-bind-button
style: destructive
label: Light Mode
id: light-mode
hidden: true
actions:
  - type: command
    command: theme:use-light
```

```meta-bind-button
style: primary
label: Dark Mode
id: dark-mode
hidden: true
actions:
  - type: command
    command: theme:use-dark
```