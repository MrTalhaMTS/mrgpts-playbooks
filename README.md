# MrGPTs Playbooks

Twelve task playbooks from [MrGPTs](https://mrgpts.com), a site of free custom GPTs, packaged as Claude skills. Each playbook is the same written method the matching MrGPTs assistants use: what to deliver, in what order, and which mistakes to avoid. Claude loads a skill only when your request matches its description.

## Skills

| Skill | Use it to |
|---|---|
| `seo-article-writer` | Turn a keyword into a full SEO article with title, meta description, slug, FAQ and schema |
| `resume-and-career-coach` | Rewrite resume bullets, write cover letters, prepare interview answers |
| `code-helper` | Write, debug, review and explain code |
| `math-stem-tutor` | Solve maths and science problems step by step with a check |
| `natural-translator` | Translate naturally, keeping tone and formatting |
| `copywriter` | Write ads, landing pages, product copy and cold emails |
| `rewrite-and-edit` | Proofread and rewrite a draft without changing the meaning |
| `research-helper` | Frame research questions and summarise papers without invented citations |
| `image-prompt-designer` | Turn an idea into detailed image-generation prompts |
| `prompt-improver` | Make any prompt clearer and more reliable |
| `security-learning-guide` | Learn cybersecurity and plan authorised tests, with a defensive focus |
| `productivity-planner` | Turn notes into plans, checklists and action items |
| `working-principles` | Shared honesty, quality and safety rules applied by the others |

## Install

Install it from the Claude plugin directory, or in Claude Code:

```
/plugin install mrgpts-playbooks --marketplace MrTalhaMTS/mrgpts-playbooks
```

Then ask for the task in plain words, for example: "Write an SEO article for 'balcony garden for beginners'".

## What it runs, sends and fetches

Nothing. The plugin contains Markdown instruction files only: no hooks, scripts, MCP servers, network calls or data collection. Everything you share stays in your Claude conversation.

## Notes

These playbooks give general guidance and can make mistakes. Check facts, figures and anything medical, legal or financial with a qualified person or an official source. More about how the playbooks are built and tested: https://mrgpts.com/how-we-test

## Licence

MIT. Maintained by Muhammad Talha, https://mrgpts.com/about
