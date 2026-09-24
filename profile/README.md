<p align="center">
  <img src="looskis.svg" alt="Looskis logo" width="96" height="96">
</p>

# Looskis

**Distribute intelligence.**

Looskis is a collection of open-source tools for Apple silicon: models, device
management, messaging, and anything in between. Each one is small, local, and
inspectable, so capable AI can run on the Macs people already own.

## Tools

| Project                                           | Area         | What it does                                                                     | Install                                                                  |
| ------------------------------------------------- | ------------ | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [scribeski](https://github.com/looskis/scribeski) | Social work  | Transcribes sessions and drafts visit notes on the Mac, then fills the EHR form. | [Download for Mac](https://github.com/looskis/scribeski/releases/latest) |
| [blueski](https://github.com/looskis/blueski)     | iMessage     | Send and receive Messages through a loopback API and CLI. AppleScript only.      | `brew install looskis/tap/blueski`                                       |
| [taski](https://github.com/looskis/taski)         | Reminders    | Turn a private iCloud Reminders list into a durable task inbox for agents.       | `brew install looskis/tap/taski`                                         |
| [gridski](https://github.com/looskis/gridski)     | Excel        | MCP server for reading and editing the workbooks open in Excel for Mac.          | `cargo install --git https://github.com/looskis/gridski`                 |
| [moolaski](https://github.com/looskis/moolaski)   | Agent skills | Financial modeling skills for AI agents, built in Excel.                         | `npx skills add looskis/moolaski`                                        |
| [greenski](https://github.com/looskis/greenski)   | WhatsApp     | Linked-device WhatsApp daemon with blueski's API shape. Unofficial protocol.     | `brew install looskis/tap/greenski`                                      |

Also here: [kueueski](https://github.com/looskis/kueueski), a script-friendly
CLI for BullMQ queues. Homebrew formulae live in
[looskis/homebrew-tap](https://github.com/looskis/homebrew-tap).

## How we build

- **Local by default.** Tools run on your Mac and keep their state there.
- **Apple's own interfaces.** AppleScript, EventKit, and Apple Events. No
  injected libraries or private Apple frameworks.
- **One job each.** Small pieces that compose, installable with Homebrew where
  possible.

## Next

Local models tuned for Apple silicon, device management, and more ways for
agents to work through the apps people already use.

---

Built by [Looski](https://www.loo.ski): private AI on Apple silicon.
