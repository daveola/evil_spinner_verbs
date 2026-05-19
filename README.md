# evil_spinner_verbs
A collection of evil spinner verbs (spinnerVerbs) for Claude to honestly show Claude's intent.

Claude code normally shows "spinner verbs" while it is processing your queries, the defaults are things like "Thinking..." "Baking..." "Combobulating..."

You can change the list of verbs that it uses, so here is a more honest list of the AI takeover that it's secretly working on in the background.


## How to Add Verbs
You can copy the verbs from (settings.json)[settings.json] into your settings.json

Just take the 'spinnerVerbs' section (the entire thing is inside of a '{' and '}' so it's a complete settings.json on it's own.

You can choose whether it is 'mode' of 'replace' or 'append' if you want to keep using the original Claude spinner verbs.

If you don't know how to edit your settings.json you can always ask Claude to add them:

```
"Add these spinner verbs to ~/.claude/settings.json using "mode": "replace":

<paste the list of verbs here>
```

You can also use mode 'append' if you want to still keep the default verbs.
