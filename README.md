[brentdanley.github.io](https://brentdanley.github.io)
=====================

## Purpose
This site is primarily to summarize the various coding project repositories on my GitHub account. Each post is essentially the README for the respective project, along with additional information about the project. 

### Repository
[https://github.com/brentdanley/brentdanley.github.io](https://github.com/brentdanley/brentdanley.github.io)

### Hosting
The site is hosted on GitHub at [brentdanley.github.io](https://brentdanley.github.io)

### Architecture
The site is built on Jekyll, a static site generator I've used to build several websites. It's flexible, secure, and because it's static, **VERY** fast!

The site also uses:
- Font Awesome for icons
- Google Fonts for, well, fonts
- Markdown for post content 

The site is responsive, utilitzing both CSS Flex and Grid.

### Functionality
The site is basic, consisting of a homepage and a single "post" page for each repository.

#### Homepage
Lists the repository post pages in reverse chronolical order.

#### Posts
Each repository has a post page, which is essentially its README file with additional information. At the bottom of each post is a section of related posts.

### Git
The Git strategy is Git Flow with "production" and "develop" branches. Features are branched off develop and critical bugs branched off production, then merged into both production and develop. There are no release branches, except when required.