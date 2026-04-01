# Agent Skills Repository

This monolithic repository contains multiple Python-based agent skills. Each skill is isolated in its own sub-directory inside the `skills/` folder.

## Existing Skills

1. **[ima-data-skill](skills/ima-data-skill/SKILL.md)**: Processes and analyzes 'ima' data.
2. **[template-skill](skills/template-skill/SKILL.md)**: A boilerplate template for creating new skills easily.

## Adding a New Skill

To add a new skill to this repository:
1. Copy the `skills/template-skill/` directory and rename it to your new skill name.
2. Update the `SKILL.md` file inside the new directory with specific instructions for your agent.
3. Add your Python scripts in the `scripts/` folder of the new skill.
4. Modify this `README.md` to list your newly added skill.

## Dependencies

Common Python dependencies required across multiple skills are tracked in the root `requirements.txt`. If your skill requires specific libraries, please ensure they are added there.
