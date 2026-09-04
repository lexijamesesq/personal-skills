# personal-skills

Lexi James's authorial voice, thinking models, and review rubric, as a Claude Code skill.

Published as the `personal` marketplace — one plugin, `personal@personal`, serving the skills under `skills/`.

```
claude plugin marketplace add lexijamesesq/personal-skills
claude plugin install personal@personal
claude plugin enable personal@personal
```

Releases are cut by CI on push to `main` (`personal--v<version>`) whenever `.claude-plugin/plugin.json`'s version is bumped; a PR that changes content without a bump is blocked by `release-check`.
