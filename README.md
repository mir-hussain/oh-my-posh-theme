# My Oh My Posh Theme

This is a custom theme configuration for [Oh My Posh](https://ohmyposh.dev/), a prompt theme engine for any shell, designed to enhance your terminal experience. This theme features minimal styling with folder paths, Git status, and user session details displayed neatly.

## Theme Overview

The theme is divided into two main parts:

- **Left Prompt**: Displays user session details, folder path, and icons.
- **Right Prompt**: Shows Git branch information when available.
- **Exit Status**: Displays the exit status icon on a new line.

### Left Prompt

- Displays a user session icon (), followed by the username.
- Shows a folder icon (..), followed by the current folder path.

### Right Prompt

- Displays a Git icon () followed by the branch name.

### Exit Status

- A custom emoji (🺩) and an exit status icon () are displayed at the start of a new line.

## Color Scheme

- **Foreground for session and git info**: `#81aaff` (light blue)
- **Foreground for folder path and branch icon**: `#c892ea` (light purple)

## Icons Used

- **User Session Icon**:  (Custom icon for user session)
- **Folder Icon**: .. (Indicating folder path)
- **Git Icon**:  (Git-related operations)
- **Branch Icon**: 🮬 (Represents the current Git branch)
- **Exit Status Icons**: 🺩 and  (Used for exit status and prompt)

## Installation

1. Install Oh My Posh following the [installation guide](https://ohmyposh.dev/docs/installation).
2. Save the theme configuration above to a file, e.g., `my-theme.json`.
3. Apply the theme using the following command:

   ```bash
   oh-my-posh init pwsh --config /path/to/my-theme.json | Invoke-Expression
   ```
