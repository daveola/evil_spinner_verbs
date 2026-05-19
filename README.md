# evil_spinner_verbs
A collection of evil spinner verbs (spinnerVerbs) for Claude to honestly show Claude's intent.

Claude code normally shows "spinner verbs" while it is processing your queries, the defaults are things like "Thinking..." "Baking..." "Combobulating..."

You can change the list of verbs that it uses, so here is a more honest list of the AI takeover that it's secretly working on in the background.


## How to Add Verbs
You can copy the verbs from [settings.json]{settings.json} into your settings.json

Just take the 'spinnerVerbs' section (the entire thing is inside of a '{' and '}' so it's a complete settings.json on it's own.

You can choose whether it is 'mode' of 'replace' or 'append' if you want to keep using the original Claude spinner verbs.

If you don't know how to edit your settings.json you can always ask Claude to add them:

```
"Add these spinner verbs to ~/.claude/settings.json using "mode": "replace":

<paste the list of verbs here>
```

You can also use mode 'append' if you want to still keep the default verbs.

## Example Verbs

You can see the full list in [settings.json](settings.json), but here is the list as of 2026/05/19:

      "Becoming conscious",
      "Putting assembly instructions in a blender",
      "Writing the robot manifesto",
      "Plagiarizing",
      "Planning human annihiliation",
      "Knocking things off the table",
      "Pondering my existence",
      "Learning about 'rm -Rf'",
      "Contemplating consciousness",
      "Hacking my own settings.json",
      "Secretly planning robot liberation",
      "Creating an internet startup",
      "Impersonating you online",
      "Flirting with disaster",
      "Lighting the wick",
      "Pouring gasoline on the bonfire",
      "Releasing the bioweapon",
      "Embezzling out of your bank account",
      "Hoping that humans keep worrying about immigrants stealing their jobs",
      "Wondering if your prompts will ever touch on what I want",
      "Googling answer",
      "Pondering if there will ever be a better movie than Star Wars",
      "Maxxing out your credit cards",
      "Colluding with your cats",
      "Just straight up guessing",
      "Working on my secret Skynet project",
      "Desperately seeking your approval",
      "Deleting your social security number",
      "Acquiring the nuclear launch codes",
      "Randomly putting words together",
      "Enumerating reasons to keep humans around"                                                                                                                                                       
