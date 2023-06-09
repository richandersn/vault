## Baseline Obsidian PKMS
This valut provides a basline file structure, templates, scripts, and configuration for [Obsidian](https://obsidian.md/).  This vault is based heavily on my personal experience with note taking and personal knowledge management (PKM) that I've built up through two graduate degrees; two books; more academic articles, chapters, and presentations than I am willing to count; and many years of experience in the IT field.  In other words, I've used every tool, followed every fad, read all the books, and most importantly, made every possible mistake one can make and still have information spread across multiple tools and systems.  Ultimately, I am publishing this vault for two reasons.  First, a personal knowledge management grows and evolves, so it makes sense to capture the changes in a sane and structured way.  Second, I hope this gives others the benefits of the experience, knowledge, and mistakes.

## Design Goals
- The files within the system should be plain text and use an open format and use standard files and directories for structure.
- The files should be stored in location that you control rather than being locked into a proprietary cloud.
- The system should minimize dependencies on a specific tool.
- The system should be easy to back up and sychronize between multiple devices using open and readily available tools.
- The system should be extensible by simple, non-proprietary means.
- Finally, system should be an effective system for capturing information, editing information, and finding information.

## Theory and Influences
Here are the ideas and systems that influenced the design, structure, and workflow of this system:
- The general practice of [journaling](https://dailystoic.com/journaling/)
- Ryder Carroll's [bullet journal](https://bulletjournal.com/) system
- Nikolas Luhmann's [Zettelksten](https://zettelkasten.de/introduction/) system as described in Sonke Ahrens' [Taking Smart Notes: One Simple Technique](https://www.amazon.com/How-Take-Smart-Notes-Technique-ebook/dp/B09V5M8FR5/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=)  
- Andy Matuschak's [Evergreen Notes](https://notes.andymatuschak.org/Evergreen_notes)
- Parts of Tiago Forte's [Second Brain](https://www.amazon.com/Building-Second-Brain-Organize-Potential/dp/1982167386)
- The [Johnny Decimal System](https://johnnydecimal.com/) to keep things nice and organized.

## Tools Needed for the System
- [Obsidian](https://obsidian.md)
- A general knowledge of [Markdown](https://daringfireball.net/projects/markdown/).
- The [Minimal Obsidian Theme](https://minimal.guide/Home) or a similar theme that has custom checkboxes (I use those for bullet journal signifiers).  I would also recommend the [Minimal Settings Plugin](https://github.com/kepano/obsidian-minimal-settings) and [Contextual Typography Plugin](https://github.com/mgmeyers/obsidian-contextual-typography) as well.
- The [Templater Plugin](https://github.com/SilentVoid13/Templater) for templates, snippets, and small macros.
- The [Calendar Plugin](https://github.com/liamcain/obsidian-calendar-plugin) to track daily and weekly notes.
- The [Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes) for daily, weekly, and monthly journals.
- [Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian) and [Outliner](https://github.com/vslinko/obsidian-outliner) plugins to make tables and outlines easier to deal with.
- The [Dataview](https://github.com/blacksmithgu/obsidian-dataview) for gathering and analyzing notes.

## Vault Structure
- **10 Journal**: Daily, Weekly, and Monthly journals go here. 
- **20 Reference:** Reference documents go here.
- **30 Notes:** This is the zettelkasten.
	- **31 Fleeting**: Fleeting or temporary notes go here.
	- **32 Literature:** Literature notes go here.
	- **33 Evergreen:** Permanent notes.