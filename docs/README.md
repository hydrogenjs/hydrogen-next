# Hydrogen Next Design Document

The goal of this document is to be a mind dump of what I want the next iteration of Hydrogen to be. I developed [Hydrogen](https://github.com/hydrogenjs/hydrogen), the initial first close to 5 years now and that was a long time ago by the JavaScript ecosystem time frame. There is a new framework that is being released and new ways of doing things constantly so Hydrogen is probably far out of the loop in relation to the initial intentions behind the project which was to be the lightest static-site generator out there, which provides just enough utility to allow a developer to make use of it in there workflows for the most simplest of tasks.

I know that there was a team in Denmark that was using it for their style guide but that was years ago, they might have migrated to something else but it is always worth trying to sink my teeth into trying to achieve my goals now that I have gained more experience and knowledge.

## 03 March 2024

### 15:53

When I have a look at tools such as Eleventy, I always feel that they do too much without thinking about the size of the package or they support too much features when it is not necessary. Why give the developer so many options to choose from when it is very simple to have the developer use whatever they need by installing the package and having it integrate with the build tool. I want the next version of Hydrogen to be as streamlined as possible so that it can be integrated into any workflow while providing an entire ecosystem of plugins that can extend the functionality of the core tool.

The core tool should be a programmatic API without a CLI tool that generates the files by consuming a series of files and then spiting them out into HTML files.