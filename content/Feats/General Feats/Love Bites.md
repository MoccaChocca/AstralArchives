---
tags:
  - RAW
  - Feat
feat_type: General Feat
prerequisite: none
---

You gain the following benefits.

***Ability Score Increase.*** Increase one ability score of your choice by 1, to a maximum of 20.

***Endearing Pain.*** Immediately after you damage a creature with a Melee weapon or an Unarmed Strike, you can take a [[Bonus Action]] to give the target the [[Charmed]] condition until the start of your next turn or until you or your allies damage it. Once you use this benefit, you can’t use it again until you finish a [[Resting|Long Rest]].

```meta-bind-button
label: Flag for review
style: primary
action:
  type: inlineJS
  code: |
    await (async () => {
      const tagName = "Flagged_for_review";
      const tag = "#" + tagName;

      const file = app.workspace.getActiveFile();

      if (!file) {
        new obsidian.Notice("No active file found.");
        return;
      }

      const escapeRegex = (text) =>
        text.replace(/[.*+?^${}()|[\]\\]/g, "\\$&");

      const tagRegex = new RegExp(
        "(^|[^A-Za-z0-9_/-])#" + escapeRegex(tagName) + "(?![A-Za-z0-9_/-])",
        "i"
      );

      await app.vault.process(file, (content) => {
        if (tagRegex.test(content)) {
          new obsidian.Notice("Already flagged for review.");
          return content;
        }

        const separator = content.endsWith("\n") ? "" : "\n";

        new obsidian.Notice("Flagged for review.");
        return `${content}${separator}\n${tag}\n`;
      });
    })();
```

