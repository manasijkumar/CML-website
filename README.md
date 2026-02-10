# CML-website
Repository to create markdown-file based lab website.

# Setup

1. Install python and pip
2. Mkdocs setup - https://www.mkdocs.org/getting-started/
3. Material theme for mkdocs - https://squidfunk.github.io/mkdocs-material/getting-started/

# Commands (run in the top level directory of the website repository)

1. To serve the website: `mkdocs serve`
2. To build the website's static files (into the "site/" sub-directory): `mkdocs build`
3. To publish the website (after committing and pushing the code changes to Github): `mkdocs gh-deploy`


# To crop and resize images for the People page

1. 'Start from your content' in Adobe Express
2. Crop the picture with a square frame, centering the middle square on the face of the person. 
3. Create a new page in the project with custom width and height of 300px. 
4. Copy over the picture to the new page, and resize it so it fits the entire 300px square. Make sure it is centered. 
5. Download as a jpeg and save it in the "docs > static > images" folder in this project.