# Conventions

## Commits
Commits and commit message shall follow the standards establish by the [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/#summary) specification.

## Branches
Branch naming will follow the same structure for all repositories. The names will contain three sections separated by `/`:
1. the issue number including the `#` (e.g.: `#46`)
2. the task type (following conventional commit types)
3. a short, hyphenated, title describing the changes (e.g.: `auth-bug`)

Example branch names:
```
#10/feat/task-page-ui
#35/docs/update-local-dev-docs
#46/bug/auth-bug 
```

## Pull Requests
### Naming
Pull requests titles should present the same information as the branch names but the structure will be a little different. 
- the issue number will be placed in brackets (e.g.: `[#46]`)
- the PR type should follow conventional commit standards and be followed by a `:` (e.g.: `feat: some title`)
- the description can and should provide more context than the branch's short description
- the description should always begin with a verb in the imperative, present tense (e.g.: "change" not "changed" nor "changes")

Example PR names:
```
[#10] feat: create task page ui 
[#35] docs: update local dev documentation to include PostgresQL commands
[#46] bug: fix authentication not allowing users to signup via google sso 
```


