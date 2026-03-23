# yoyo-skills

Reusable agent skills maintained for personal and team workflows.

## Skills

- `unity-shader-graph-cn`
  - Chinese guidance for Unity Shader Graph effects such as Cel Shading, outline, Fresnel, dissolve, hit flash, and stylized character shaders.
  - Asks for Unity version and render pipeline first.
  - Outputs in a fixed structure with Graph Settings, Node Settings, node connections, formulas, scenario-specific suggestions, and troubleshooting prompts.

## Repository Layout

```text
yoyo-skills/
└── skills/
    └── unity-shader-graph-cn/
        └── SKILL.md
```

## Install

```bash
npx skills add https://github.com/<your-name>/yoyo-skills
```

Install only this skill:

```bash
npx skills add https://github.com/<your-name>/yoyo-skills --skill unity-shader-graph-cn
```

## Notes

- The skill instructions are written in Simplified Chinese.
- Variable names and formula variables remain in English for consistency with Shader Graph usage.
