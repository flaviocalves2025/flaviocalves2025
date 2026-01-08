# Copilot Instructions

## Project Overview
This is a GitHub profile README repository showcasing professional background and skills. The repository serves as a personal portfolio and introduction for Flávio Cantanhede Alves.

## Repository Purpose
- **Type**: GitHub Profile Repository (appears at github.com/flaviocalves2025)
- **Content**: Personal/professional branding via README.md
- **Primary File**: README.md with HTML/Markdown hybrid content

## Content Strategy

### Profile Sections
The README follows this structure:
1. **Header**: Name and motivational quote
2. **Contact Links**: Email and LinkedIn badges
3. **Professional Summary**: Background in IT and BI
4. **Personal Brand**: First-person narrative highlighting innovation, teamwork, continuous learning
5. **Tools**: Visual icons linking to documentation (VS Code, Python, HTML, CSS, JS, SQL Server)
6. **Skills**: Hard skills (IT frameworks, programming) and soft skills (focus, nature affinity)
7. **GitHub Stats**: Dynamic stats widget

### Formatting Conventions
- Uses HTML tags for alignment (`<h1 align="left">`, `<img align=right>`)
- Badge images from shields.io for social links
- DevIcons CDN for technology logos
- Inline styles for spacing (`style="margin-right: 20px;"`)
- Mix of Markdown and HTML for rich formatting
- Portuguese language (pt-BR) for all content

## Maintenance Guidelines

### When Adding New Skills/Tools
- Add technology icon to "Ferramentas" section using DevIcons CDN pattern:
  ```html
  <a href="[documentation-url]" target="_blank">
    <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/[tech]/[tech]-[variant].svg" 
         width="40" height="40" alt="[documentation-url]" style="margin-right: 20px;"/>
  </a>
  ```
- Keep icons 40x40px for consistency
- Always link to official documentation

### Content Updates
- Maintain first-person, conversational tone with personality (humor, metaphors)
- Use emojis to enhance readability: 👨‍🎓 🤖 🔪 🫣 🧐 ��️ 🤘 🪄 🤝 🎯 🚀
- Keep professional summary current with certifications/education
- Update GitHub stats username if it changes (currently uses "flaviocalves")

### Badge/Link Patterns
- Social badges: shields.io with `style=for-the-badge`
- Target="_blank" for all external links
- Loading="lazy" for all images

## Technical Notes
- No build process required (static README)
- No dependencies or package management
- Profile automatically displayed on github.com/flaviocalves2025
- Consider adding .gitignore if workspace files are accidentally committed

## AI Agent Guidance
- Preserve the unique, personable tone when editing content
- Maintain bilingual capability (Portuguese content, English tech references)
- Keep visual consistency when adding new sections
- Suggest modern profile enhancements: GitHub Actions badges, contribution graphs, pinned repos section
- Recommend accessibility improvements for screen readers
