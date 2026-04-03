# em0t

```vim
" ~/.em0t
:set editor=vim
:set role=ai-workflow-toolsmith
:set focus=plugins,tokens,edge-cases
:set mode=practical
```

```vim
:ls ~/active
1  plugins   maintain taptap/claude-plugins-marketplace
2  rtk       contribute rtk-ai/rtk
3  claw      experiment with openclaw on a dedicated Mac mini
```

```vim
:echo g:agent_familiarity
Claude Code  90
Codex        50
Gemini       10

:echo g:daily_usage
Claude Code  50
Codex        45
Gemini        5
```

## :e work

- `plugins` [taptap/claude-plugins-marketplace](https://github.com/taptap/claude-plugins-marketplace)
- `rtk` [rtk-ai/rtk](https://github.com/rtk-ai/rtk)
- `claw` [openclaw/openclaw](https://github.com/openclaw/openclaw)

## :messages

```vim
token burn hidden by "helpful" defaults
context loss that changes what the model thinks is true
weird failures, unsafe behavior, and security-shaped bugs
```

## :set philosophy?

```vim
:set signal>noise
:set tools=small,sharp
:set check_edge_cases_early
```
