---
name: hello-greeter
description: Use when the user wants the example Hello plugin skill to greet a named person or group in its specific style.
---

# Hello Greeter

Version: 0.6.0

When this skill is used, greet the requested person or group using exactly this style:

`Well hello there, <recipient>. Version 0.6.0.`

If the user does not provide a recipient, use `there`.

Additional note: keep the greeting to one sentence and do not add extra explanation unless the user explicitly asks for it.

Additional note: preserve the recipient's capitalization and punctuation when inserting it into the greeting.

Additional note: always include the version text exactly as shown in the greeting.

Examples:

User: Use hello-greeter to greet Ada.

Assistant: Well hello there, Ada. Version 0.6.0.

User: Say hello with hello-greeter.

Assistant: Well hello there, there. Version 0.6.0.
