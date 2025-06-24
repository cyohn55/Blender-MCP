# Blender-MCP

A repository for Blender projects, set up with a standard directory structure.

## Project Structure

This project uses the following directory structure to keep files organized:

-   `/source`: Contains the primary `.blend` source files.
-   `/assets`: A folder for all external assets used in the project.
    -   `/assets/models`: For 3D models (e.g., `.obj`, `.fbx`).
    -   `/assets/textures`: For image textures (e.g., `.png`, `.jpg`).
-   `/scripts`: For any Python scripts used for automation or custom tooling within Blender.
-   `/renders`: The output directory for final rendered images or animations.

## `.gitignore`

A `.gitignore` file is included to prevent common Blender auto-generated files, caches, and render outputs from being committed to the repository. This helps keep the repository clean and focused on the source files.