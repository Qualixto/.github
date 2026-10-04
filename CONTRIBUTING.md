# Contributing

How we work on Qualixto repositories. Work is done when it is ready for production, not when the code is written.

---

## Workflow

1. **Start from an issue.** Every change traces back to one.
2. **Branch from `main`** as `<type>/<issue>-<short-description>`, for example `feat/12-add-freshness-checks`.
3. **Commit** using `<type>: <short description>`, with a body explaining *why* when it isn't obvious.
4. **Open a pull request** using the template and link the issue with `Closes #<issue>`.
5. **Merge** once review is approved and CI is green. Nobody commits to `main` directly.

## Commit types

| Type | When to use |
|---|---|
| `feat` | New feature |
| `fix` | Bug fix |
| `refactor` | Restructuring without behaviour change |
| `test` | Adding or updating tests |
| `docs` | Documentation changes |
| `chore` | Maintenance, dependencies, tooling and CI |
| `perf` | Performance improvements |

## Definition of Done

- [ ] Code is merged to the target branch
- [ ] All automated tests pass
- [ ] New behaviour is covered by tests
- [ ] Documentation is updated
- [ ] Monitoring and alerting are in place, where relevant
- [ ] Security checks pass
- [ ] Acceptance criteria are met and verified
- [ ] Peer review is approved
- [ ] No known regressions introduced
