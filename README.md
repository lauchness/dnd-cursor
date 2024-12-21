# Campaign Management System

This repository serves as a comprehensive management system for our D&D campaign. It uses markdown files for content organization and linking between related elements.

## Folder Structure

### `/characters`

- `/player-characters`: PC information and development
- `/npcs`: Non-player characters
- `/villains`: Antagonists and their schemes

### `/world`

- `/locations`: Places and their descriptions
- `/factions`: Organizations and groups
- `/pantheon`: Deities and religious information
- `/maps`: Map registry and links

### `/gameplay`

- `/sessions`: Session notes and plans
- `/quests`: Main and side quest tracking
- `/encounters`: Combat and social encounter designs

### `/lore`

- `/themes`: Campaign themes and motifs
- `/history`: World history and events
- `/artifacts`: Significant items and artifacts

### `/rules`

- `/house-rules`: Custom rules and modifications
- `/random-tables`: Generated tables for improvisation

## Using This System

### File Naming

- Use lowercase letters
- Separate words with hyphens
- Example: `storm-kings-temple.md`

### Linking Between Files

- Use relative paths: `[Storm King](../../npcs/storm-king.md)`
- Always use relative links to maintain portability

### Templates

Each folder contains a `_template.md` file showing the standard format for that content type.

### Updating Content

1. Use templates for new content
2. Include links to related content
3. Update existing files when new connections form
4. Keep session notes up to date

### Best Practices

1. Regular commits after sessions
2. Update character information as it changes
3. Link new content to existing elements
4. Keep track of unresolved plot threads
