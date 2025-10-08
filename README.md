# README – Editing Workflow

This is a simple editing workflow that I use to get LLM feedback on my writing. I clone this repo for each piece I want to get feedback on, though I put subsequent drafts in the same repo. 

## Structure

* `drafting/` – various documents I want feedback on, and also where the editing agent can dump its comments. 
* `sources/` – external knowledge where relevant for analytical nonfiction writing.
* `style/` – style guides for fiction and nonfiction writing. When applicable I also add in other documents as style exemplars.
* `CLAUDE.md` – instructions for the editing agent, because I use this setup in Claude Code. You may want to use another editor, in which case I think the convention is to call it `AGENTS.md`? I'm not really clued in on that.

See `CLAUDE.md` for the conventions I use to have the LLM give feedback. In general these instructions are all working around the limitations of using markdown documents. Frankly, I would much rather integrate this setup into Google Docs! If you, reading this, are more technical than I am, you could make a Google Docs-native editing agent that can take an external knowlege base and style guides, and leave comments and suggestions in a Google Doc. I would pay money for that product, and I bet many writers would pay for that too.

## Warning

The instructions in `CLAUDE.md`, `style/fiction-style-guide.md` and `style/nonfiction-style-guide.md` reflect my idiosyncratic beliefs about good writing. If you clone this setup, you should probably edit these documents substantially to reflect your idiosyncratic beliefs. 
