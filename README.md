# .github

Default community health files for notglossy repositories.

GitHub uses the issue templates in [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) for every notglossy
repository that has no `.github/ISSUE_TEMPLATE/` folder of its own. The fallback is all or nothing: a repository
with even one template of its own sees none of these, so copy the ones it needs into its own folder.

`feature-request.yml` comes from
[notglossy/agentic-workflows](https://github.com/notglossy/agentic-workflows/blob/main/issue-templates/feature-request.yml),
whose `feature-triage` workflow reads its section headings. Change it there first, then copy it here.
