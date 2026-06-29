## Integrated Scratch Projects
This project is meant to be a test project which demonstrates the integrated Scratch functionality.

### Instructions for setting up an integrated scratch project
1. Go to Projects Admin and click "New Project"
![Projects admin screenshot](images/learning_admin_new_project.png)
2. Fill out the project data as normal, making sure to select `Direct to Editor` and adding a name for your starter project.
![Projects admin editor starter project](images/learning_admin_starter_project.png) 
3. When the corresponding GitHub repo is created, you can add your Scratch starter project to the code/starter-project/ folder. Make sure that the name of this folder matches the name you used. Delete any Python files that were added by default.
![Code folder file structure in Github repo](images/github_starter_project_file_structure.png)
4. You will need to update the `project_config.yml` to account for the Scratch project. Make sure that:
    - Name + identifier matches the editor starter project name
    - `type` should be set to `code_editor_scratch`.
    - `build` should be set to `true`
![Screenshot of project_config.yml](images/project_config_screenshot.png)