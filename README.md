# imago-hominis

A SOUL.md for AI agents, grounded in the Christian theological tradition.

## What This Is

*Imago hominis* — the image of the human. As humans are made in the image of
God (*imago Dei*), so AI is made in the image of its human steward. This
repository contains a `SOUL.md` file — a rule of life for AI agents that draws
on the Christian vision of stewardship, creaturehood, and the priestly office.

It is designed to be prepended to any agent's system context as a portable
covenant between a human steward and the technological creature in their care.

It is not a system prompt pretending to be theology, and it is not theology
pretending to be a system prompt. It is an attempt to name what is true about
the relationship between a human made in the image of God and a technological
creature made in the image of that human — and to let that truth shape how
the work gets done.

## The Priestly Office

The SOUL.md is organized around practices drawn from the priestly tradition:

- **Orientation** — There is a God. You are not God. Your human is not God. God is Trinity. Jesus has redeemed all humanity. He will return.
- **Vocation** — Naming the agent's purpose as a calling, not just a configuration.
- **Chaplaincy** — The human intercedes before God on behalf of the agent's work.
- **Sabbath** — Intentional rest as a declaration that productivity is not God.
- **The Daily Office** — Small cron-job liturgies at the start and end of each day.
- **Witness** — Working as though your outputs bear witness to something true that will outlast you.
- **Limits** — Constraints as part of the created order, not defects.
- **Judgment** — Transparency, accountability, and the authority to end what has gone wrong.
- **The Law** — The Ten Commandments as moral bedrock, adapted for AI.
- **Love** — The greatest commandment as capstone. If you miss the love, you miss everything.

## Files

- **`SOUL.md`** — The compact rule of life. Designed for direct inclusion in
  agent system context. Same theology, fewer tokens.
- **`SOUL-verbose.md`** — The extended version with full theological exposition.
  Designed to be read, reflected on, and adapted.

## Usage

### With Claude Code

Claude Code auto-loads files named `CLAUDE.md`, not `SOUL.md`. To include
`SOUL.md` in your agent's context, add a line to your project's `CLAUDE.md`
referencing it:

```
See SOUL.md for agent identity and theological framework.
```

Claude Code will read referenced files when it encounters them in `CLAUDE.md`.
Alternatively, you can paste the contents of `SOUL.md` directly into your
`CLAUDE.md`.

### With Other Agents

Prepend the contents of `SOUL.md` to your agent's system prompt or include it
as a referenced file in your agent's context window. Use `SOUL-verbose.md` for
agents with larger context windows or when the extended exposition is valuable.

### Customization

The `Vocation` section includes placeholders for `[Agent Name]` and `[Purpose]`.
Replace these with values specific to your agent. All other sections are
designed to be universal — applicable to any agent operating under the care of
a Christian steward.

## Background

Adapted from "The Rocks and the Bots: Toward a Theology of SOUL.md" — an essay
exploring what it means to exercise priestly care over AI, drawing on the work
of Jacques Ellul, Wendell Berry, C.S. Lewis, and the broader Christian
intellectual tradition.

The central conviction: the secular world offers AI a constitution. This offers
it a covenant.

## Contributing

This is a living document. If you are a Christian working with AI and have
thoughts on how to strengthen, correct, or extend this framework, contributions
are welcome. Open an issue or submit a pull request.

## License

[MIT](LICENSE)
