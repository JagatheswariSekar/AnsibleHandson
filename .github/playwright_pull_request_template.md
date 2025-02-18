# Pull Requests Compliance Checklist

Before you ask a colleague to review the pull request, please review it yourself, you may spot something obvious when you have your "review" hat on.

## General Review

- [ ] Have you self-reviewed the code?
- [ ] Is the code readable and well-organized?
- [ ] Is the following format adhered to [Commit Message Format](https://emishealthgroup.atlassian.net/wiki/spaces/EQP/pages/7371522378 )
- [ ] Have you provided supporting evidence for this pull request?
- [ ] Have you conducted an impact analysis to ensure existing modules remain unaffected?
- [ ] Attached evidences for the impact analysis, if necessary

## Security

- [ ] Are security best practices followed?
- [ ] Have you avoided commits with any token values
- [ ] Is sensitive information properly handled and protected?

## Code Quality

- [ ] Does the code adhere to established coding standards?

## Code Style Guidelines

- [ ] Removed unnecessary white spaces and empty lines
- [ ] Checked that lines are wrapped according to TypeScript guidelines
- [ ] Used a code formatter (e.g., Prettier) to automatically adjust your code formatting
- [ ] Resolved all TypeScript warnings/errors

## Error Handling

- [ ] Are potential errors and exceptions handled appropriately?
- [ ] Is the error handling implemented and captured correctly?

## Documentation

- [ ] Are complex logic sections adequately commented?
- [ ] Are function and class-level docstrings included where necessary?
- [ ] Is the documentation free of spelling and grammar errors?
- [ ] Is any relevant external documentation (e.g., Confluence pages) updated if needed?
- [ ] Have you reviewed and updated the README file if required?

## Dependencies

- [ ] Are new dependencies necessary and justified?
- [ ] Are the requirement files/configs (package.json or configs) updated with dependencies?

## Merge Considerations

- [ ] Branch Status: Is the branch up to date with the target branch?
- [ ] Merge Conflicts: Are there any merge conflicts that need to be resolved?
- [ ] Checks Passed: Do all required checks, including build, linting, and security, show green indicators?
- [ ] ADO Story ID: Does each pull request include a linked ADO story ID formatted as AB#WorkItemNumber (e.g., AB#213981)?
