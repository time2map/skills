# time2map skills

A Claude Code plugin marketplace: a small catalog of the Claude Agent Skills published by [time2map](https://time2map.com).

Add it once, then install whatever you need from it:

```
/plugin marketplace add time2map/skills
```

## What's in it

| Plugin | What it does | Repository |
| --- | --- | --- |
| `brief-interview` | Interviews the client before writing a project brief for development — problem, goals, priority, non-goals, user stories, requirements, acceptance criteria and open questions, containing only what the client confirmed | [claude-brief-interview](https://github.com/time2map/claude-brief-interview) |
| `claude-qa` | A set of QA skills. Currently: `qa-checklist-from-diff` — builds a manual QA checklist from a branch diff against a base branch (full or regression-only, time budget, configurable language and format) | [claude-qa](https://github.com/time2map/claude-qa) |

Install one with:

```
/plugin install brief-interview@time2map
/plugin install claude-qa@time2map
```

Each skill lives in its own repository and is referenced from here, so this catalog stays at one address no matter how the skills move or grow.

## Author

Alexander Semenov — [time2map.com](https://time2map.com)

MIT licensed.
