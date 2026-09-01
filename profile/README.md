# Supervertaler

**AI translation, terminology and search &ndash; inside Trados Studio and memoQ, and across the rest of Windows**

Supervertaler is professional translation software built by [Michael Beijer](https://beijer.uk/), a Dutch-English patent and technical translator.

### Supervertaler for Trados

A Trados Studio plugin (Studio 2024 and 2026) that brings TermLens inline terminology, an AI Assistant, Batch Translate and AI Proofreader, SuperSearch cross-file search and replace, SuperMemory, and an MCP server for Claude Desktop directly into the Trados editor. MultiTerm `.sdltb` support included.

Source-available, single paid plan, 14-day free trial &ndash; no credit card, no sign-up.

- [Repository](https://github.com/Supervertaler/Supervertaler-for-Trados) &middot; [Documentation](https://docs.supervertaler.com/trados/) &middot; [Install from the RWS AppStore](https://appstore.rws.com/plugin/432) &middot; [supervertaler.com](https://supervertaler.com)

#### SuperMemory

Part of the Trados plugin. A place to write down the things about a client that you cannot look up: which term they insist on, what they rejected last time, how they want things phrased. Each memory bank is three Markdown files you edit yourself &ndash; a brief, a terminology table, and style rules &ndash; plus a shared bank of house defaults that any client bank can override. The AI reads the active bank on every translation, and a bank stays small enough to read start to finish, which is what makes a wrong entry findable.

It complements your termbases and translation memories rather than replacing them: they hold the terms and the wordings, SuperMemory holds the reasoning.

- [Documentation](https://docs.supervertaler.com/trados/ai-assistant/super-memory/)

#### MCP Server

Ships with the plugin. It connects Claude Desktop, and any other MCP client, to the Trados Studio session you have open &ndash; so an AI assistant can read your active project, search your TMs and termbases, run QA checks, and write segments back.

- [Documentation](https://docs.supervertaler.com/trados/mcp-server/)

### Supervertaler for memoQ

A memoQ plugin: an LLM machine-translation engine that learns from the segments you confirm, a terminology provider that puts your own glossary into memoQ&rsquo;s Translation results *and* into the AI&rsquo;s prompt as preferred or forbidden terminology, and an MCP bridge so Claude Desktop can translate your live memoQ project.

Confirm a term once and the rest of the document follows it &ndash; no configuration, no retraining, just your own approved choices fed forward. Bring your own API key (Anthropic, OpenAI or Google) &ndash; or none at all: with Claude Desktop connected, Claude reads the document, stages translations, and they flow into the grid when you press Pre-translate, billed to your Claude subscription. Prompts come from the same library the Trados plugin uses.

memoQ gives a plugin no window and no editor access, so this is a different shape of tool from the Trados plugin: everything happens through memoQ&rsquo;s own MT engine and terminology pane, and Claude&rsquo;s work reaches your document only through your own hands. The docs say plainly which Trados capabilities memoQ can and cannot have.

**Working, pre-release.** Translates, batches, learns, serves terminology and connects to Claude Desktop; distributed as unsigned DLLs until a signed build and installer land.

- [Repository](https://github.com/Supervertaler/Supervertaler-for-memoQ) &middot; [Documentation](https://docs.supervertaler.com/memoq/) &middot; [MCP Server for memoQ](https://docs.supervertaler.com/memoq/mcp-server/)

### Supervertaler Sidekick

The system-wide toolbox. The one Supervertaler tool that does not live inside a CAT tool: press a key anywhere in Windows and act on whatever is selected, in any application &ndash; a CAT editor, a browser, a PDF, an email.

A clipboard manager with searchable history, a snippet library, text expansion and autocorrect, translation through several MT engines and LLMs at once with the results side by side, terminology and web searches, text conversions, and AI prompts over the selection.

Built in AutoHotkey v2. Windows only, no runtime, no install step.

**In early development.** The repository is public and the tool runs, but there is no release yet.

- [Repository](https://github.com/Supervertaler/Supervertaler-Sidekick)

### Help &amp; Documentation

Published at [docs.supervertaler.com](https://docs.supervertaler.com/), and machine-readable for AI agents at [/llms.txt](https://docs.supervertaler.com/llms.txt).

---

### Community

- [GitHub Discussions](https://github.com/orgs/Supervertaler/discussions) &ndash; the main community hub for questions, ideas, and discussion
- [Bug reports &amp; feature requests](https://github.com/Supervertaler/Supervertaler-for-Trados/issues)

### Supervertaler Workbench

A free, open-source standalone CAT tool: editor, AI translation, terminology and translation memory in one place, plus tools that work system-wide in any application &ndash; a clipboard manager, SuperLookup, QuickTrans, and voice dictation.

**No longer actively developed.** It still works and the source is still open, but it is not receiving new features. Its documentation stays online in full.

Its system-wide tools &ndash; the clipboard manager and QuickTrans &ndash; live on in [Supervertaler Sidekick](https://github.com/Supervertaler/Supervertaler-Sidekick).

- [Repository](https://github.com/Supervertaler/Supervertaler-Workbench) &middot; [Documentation](https://docs.supervertaler.com/workbench/) &middot; [PyPI](https://pypi.org/project/Supervertaler/)

### Website

[supervertaler.com](https://supervertaler.com)
