Creating a PR Template for Your Project
It’s quite easy to generate a PR template for your project. Simply create a file named PULL_REQUEST_TEMPLATE and place it one of three locations:

The root of your project
.github folder
docs folder
An extension is optional, and GitHub supports Markdown (.md) files. I’ve chosen to create a Markdown template so you can use features like Markdown formatting, @-mentions, and task lists.

Once GitHub detects the PULL_REQUEST_TEMPLATE file, it will auto-populate new PRs with the contents.