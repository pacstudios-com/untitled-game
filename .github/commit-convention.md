# commit convention

format: <type>: <short description>

types:
  feat      new feature or system
  fix       bug fix
  refactor  cleanup, no behavior change
  docs      documentation only
  chore     tooling, ci, config
  wip       work in progress (never merge to main)

rules:
  - lowercase always
  - no period at the end
  - present tense ("add hitbox" not "added hitbox")
  - reference issue number where relevant: "feat: add sword swing hitbox, closes #4"
  - keep subject under 72 characters
  - if more detail needed, leave a blank line then write a body

examples:
  feat: add stagger system to enemy base class
  fix: head detach not triggering on decapitation threshold
  refactor: split combat_manager into attack and hitbox components
  docs: update GDD with phase 2 task list
  wip: dagger special ability camera lerp (not functional yet)
