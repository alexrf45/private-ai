# Project: Private-AI
Private AI infrastructure hosted on GCP or AWS using open weight models, exposed on a Tailnet
for access via Claude Code

## Code Style/infrastructure tooling
- Terraform (HCL) to the maximum extent
- Reusable modules with the ability to scale as needed
- Python scripts for various utilities and commands

## Rules
- Cloud costs will never exceed $30/month
- Hooks should run before any changes to code from Claude and before commits
- Access to the AI model should never be publicly exposed, only accessed via Tailscale
- See `./.claude/rules/` for additional rules regarding this project as it progresses

## References
- @docs/ contains all internal notes,comments, usage guides, findings, and other development & deployment related commentary and notes
