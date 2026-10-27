# Related repositories

```yaml
this: gearsnlevers/e2e-lib

related:
  - role: app
    repo: gearsnlevers/e2e-app
    secret: E2E_APP_ISSUES_TOKEN
    when: |
      When the report is about a command, its arguments, how results are printed, its exit code or its error messages.

notes: |
  This library owns every function that computes a result: the tree walk and the widget list.
  The app owns the command line: reading files, arguments, printing, exit codes and error messages.
  When in doubt, keep the issue here. See AGENTS.md of each repository for the layering.
```
