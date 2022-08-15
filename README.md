# Book Template
This is a repository with the basic files/structure for a Tech Outreach lesson or set of lessons. It contains the setup to build a GitBook from the repository using GitHub actions.

## Files
Here is a breakdown of the files in this repository:

- **.github/workflows/buildGitbook.yml**: This file describes the GitHub action to build the GitBook from this repository. It places the code in a branch named `gh-pages`, which GitHub Pages can use to render the book online.
- **styles/website.css**: This file adds custom styles to the GitBook.
- **.gitignore**: This file lists files that should be ignored by Git.
- **book.json**: This file contains configuration information for the GitBook.
- **FollowAlong.md** This is an example file that will become a page of the published GitBook.
- **PptTemplate.pptx**: This is a PowerPoint file that contains our current theme.
- **README.md**: This is this file. It will not be published on the GitBook, and is designed for internal instructor reference only.
- **StudentDesc.md**: This file will be the landing page of the GitBook when it is published.
- **SUMMARY.md**: This file outlines the pages to be published on the GitBook.

## Getting Started
