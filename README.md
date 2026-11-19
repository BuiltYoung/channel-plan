# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `channel-plan`

Scores the places your audience can be reached, picks the three channels a small team can keep up, and sets three content pillars with first post ideas.

**How it works**

1. **Ask first.** Audience, payer, region, hours per week and what you can make.
2. **List the candidates** and **score each one** on reach, evidence, cost, time and unique access. A guess scores 1.
3. **Pick three**, with at least one where you have access no one else has.
4. **Check each platform's own age rule** on its terms or help-centre page, with the link and date.
5. **Set three content pillars** and first post ideas for each channel.

Age rules are never taken from a blog or a third-party list.

It is one stage of [gtm-pipeline](https://github.com/BuiltYoung/gtm-pipeline), the GTM super agent, and also works on its own.

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/channel-plan.git ~/.claude/skills/channel-plan
```

Restart Claude Code. The skill loads automatically when your request matches it.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `channel-plan` folder.

---

## Using it

Describe what you need. No command needed:

> *"Our audience is Grade 9 to 12 club executives in Ontario. We have about 5 hours a week. Where should we post?"*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. See [LICENSE](LICENSE). Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
