# test-skill

A throwaway Claude Code plugin marketplace with one test plugin, `hello-test`.

## Install

```
/plugin marketplace add adityabansal1010/test-skill
/plugin install hello-test@test-skill
```

Then say "run the hello test" to check it loaded.

## Layout

```
.claude-plugin/marketplace.json     # marketplace manifest
plugins/hello-test/
  .claude-plugin/plugin.json        # plugin manifest
  skills/hello-test/SKILL.md        # the skill itself
```
