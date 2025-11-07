# Plugin Management

## Commands

```
❯ yoda plugin --help
                                                                                                                                                       
 Usage: yoda plugin [OPTIONS] COMMAND [ARGS]...                                                                                                        
                                                                                                                                                       
 Commands to manage plugins                                                                                                                            
                                                                                                                                                       
╭─ Options ───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│ --help          Show this message and exit.                                                                                                         │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│ disable   Disable a plugin                                                                                                                          │
│ enable    Enable a plugin                                                                                                                           │
│ list      List all available plugins                                                                                                                │
│ refresh   Re-discovers all available plugins and enables them                                                                                       │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯

❯ yoda plugin list
    Yoda Plugins    
┏━━━━━━━━┳━━━━━━━━━┓
┃ Name   ┃ Enabled ┃
┡━━━━━━━━╇━━━━━━━━━┩
│ config │ Yes     │
│ plugin │ Yes     │
│ ai     │ Yes     │
│ bye    │ No      │
│ dev    │ Yes     │
│ hi     │ No      │
│ url    │ Yes     │
│ dummy  │ No      │
└────────┴─────────┘
```

## Docs

::: yodapa.core.plugin
