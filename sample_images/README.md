# Sample Images Directory

This directory contains sample images for the Tokyo Toon AI application.

## Naming Convention

Sample images should follow this naming pattern:
- `pose_<name>.<ext>` - For pose reference images
- `character_<name>.<ext>` - For character reference images

## Examples

- `pose_standing.jpg`
- `pose_sitting.png`
- `pose_running.jpg`
- `character_anime_girl.png`
- `character_boy.jpg`
- `character_fantasy_knight.png`

## Adding New Samples

1. Ensure images are properly licensed for use
2. Resize images to reasonable dimensions (max 1024px on longest side)
3. Follow the naming convention above
4. Place files in this directory

The API will automatically serve these images at:
- `/api/v1/images/samples/{filename}`