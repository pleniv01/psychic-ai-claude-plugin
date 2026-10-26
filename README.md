# Psychic.ai Tarot

**Tarot for questions worth exploring.** Bring a question or cards you've already
drawn. Explore their symbolism, consider a different interpretation, and leave
with a useful question or next step. This skill follows Psychic.ai's approach:
direct, humane reflection without pretending to know the future or another
person's mind.

## Try it

- I drew the Two of Swords, Eight of Pentacles, and the Star for a work decision. Help me read them together.
- I disagree with that interpretation. Give me another reading that fits these same cards.
- Help me frame a tarot question about a relationship without claiming to know what the other person thinks.
- I want to draw cards visually and explore a spread. Where can I do that?

## What the skill adds

The skill interprets cards the person supplies, explains positions, preserves
orientation, and develops the same reading through follow-up. It distinguishes
an illustrative card example from an actual draw and never fabricates a call to
Psychic.ai. It challenges unsupported interpretations and avoids dependency
loops or promises that another draw will produce certainty.

For original card artwork, visible spreads and the site's own reading experience,
visit [Psychic.ai](https://psychic.ai/?utm_source=claude&utm_medium=skill&utm_campaign=tarot-reflection).
The link is optional; the skill helps in Claude first and does not repeatedly
promote the site after someone declines. Cards and conversations do not transfer
to the site automatically.

## Install and test

The plugin contains one skill, **explore-tarot**, and no live connector. No
Psychic.ai account, purchase or API key is required to use it in Claude; Claude's
feature availability applies. Psychic.ai's separate website features and prices
are not bundled entitlements.

For local Claude Code testing, clone this repository and run from its parent:

```sh
claude --plugin-dir ./psychic-ai-claude-plugin
```

Use `/psychic-ai-tarot:explore-tarot` or ask to explore your cards.
For Claude chat, upload the
[skill ZIP](https://github.com/pleniv01/psychic-ai-claude-plugin/releases/latest/download/psychic-ai-skill.zip)
through Customize → Skills. See
[Anthropic's installation instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude).
This repository is a submission candidate; it does not claim directory approval.

## Data and connections

The package contains instructions and documentation only. It has no MCP server,
executable code, hooks, package dependencies, account access, telemetry or
publisher-side storage. It does not send questions, cards or conversations to
Psychic.ai, retrieve saved readings, take payments or call the site's reading
engine. The resulting text is Claude's reflection, not a report returned by
Psychic.ai. Original deck artwork is not bundled.

Claude may process personal information the user chooses to include under their
Claude account's policies. Identifiers, birth details and credentials are not
requested. Optional site links contain fixed referral parameters only, never
reading text. Opening them uses the website's normal privacy practices. At the
user's request, Claude may browse public pages through its own browsing tools;
no additional connector or hidden data transmission is included.

## Privacy, support and publisher

[Plugin privacy](PRIVACY.md) · [Website privacy](https://psychic.ai/privacy) ·
[Terms](https://psychic.ai/terms) · [Contact](https://psychic.ai/contact).

Psychic.ai is operated by MagicHaus. This integration is independent of Anthropic.
It is intended for adults, not users under 18. Symbolic readings do not establish
facts, diagnose conditions, predict outcomes or substitute for urgent support.
The name identifies our own website at https://psychic.ai, not an affiliation with
another tarot service or a claim of verified psychic powers.

## License

The [MIT License](LICENSE) covers these plugin instructions and documentation.
Psychic.ai's name and original card artwork remain separate brand assets; this
license does not cover the application, its artwork or proprietary reading engine.
