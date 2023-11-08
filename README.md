# Saezlab analysis templates

This repo contains boilerplate code for common analyses performed in the Saezlab. Folders are used to collect types of analyses, such as `bulk_transcriptomics`. In each folder, there is at least one template to start from in your analyses, or to mix and match the chunks to create new workflows. To use a template, create a new repository from it by clicking the `Use this template` button at the top.

For R code, the template subfolder should contain an `.Rproj` file in order to point to the correct working directory. Markdown is used to knit the analyses to HTML for sharing with collaborators.

If you add your boilerplate(s) to the repo, please update the `.gitignore` to avoid contaminating the templates with local, user-specific files. Templates should be in working order, meaning that all analyses should be runnable (using small scale dummy data) and the knitting of HTML output should succeed.
