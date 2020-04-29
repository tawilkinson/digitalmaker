# Digital Maker

This repository is meant to provide some helpful hints to Explorer (or Scouts) doing the final stage of the [Staged Activity Badge]([https://www.scouts.org.uk/staged-badges/): [Digital Maker](https://members.scouts.org.uk/supportresources/4283).

Explorers are most likely to want to go straight for the final stage of the badge and I felt some pointers (and a basic Git repo structure) might help in running such evenings. The rest of this README assumes you are a young person aiming to carry out Stage 5 of the badge.

## Part 1: Solving a Problem

_Identify a real-life local or global problem and design, build, test, and improve a solution by combining your digital making skills and selecting appropriate software tools, digital devices, components, and materials._

### Where To Start

Your leader will suggest a team size but 3-4 should work well. You want to pick a team that you feel you can work well with and that gives a wide variety of skills. Perhaps one of you is excellent at drawing and can help design the overall look of your solution. If at least one of you have experiencing with a coding language you will find writing a solution easier.

The first step is to identify a real-life problem. Discuss with your leader for some ideas. Some suggestions are below:

#### Local

- You could provide a website solution to a local volunteer organisation.
- Engage with residents in your area to provide a resource for people who are less technologically savvy.
- Design a website to showacse the problems of cyber bullying and how to combat it.

#### Global

- Design a system for organising internet pen pals with other Scouts elsewhere in the world.
- Design an interactive website that highlights a global enviornmental issue.
- Design a tool to distinguish fake news from real news.

### Design

Before you begin writing a single line of code you should think about the problem you are trying to solve. Think of the big picture and best to solve the problem. Prototype some ideas before committing to one approach, this will save you time in the long run.

Think about the tool you will use. You could solve a database problem by using standard spreadsheet software but as you dig into the problem you may realise it is easier to implement something in a programming language\*.

\*Explorers should opt for programming unless they have an exceptional idea that can be implemented using an existing tool.

### Build

Write your code/make your solution! This will be the majority of the badge work. Some suggested tools you could use:

- Python: [https://www.python.org/](https://www.python.org/)
- Jekyll: [https://jekyllrb.com/](https://jekyllrb.com/)
- Jupyter Notebooks: [https://jupyter.org/](https://jupyter.org/)

If you are writing your own code you should think about using version control software. This allows you to revert changes you make if you break your code and is a valuable skill to learn. You can start by downloading [GitHub Desktop](https://desktop.github.com/) and creating a free [GitHub account](https://github.com/join). This provides a GUI tool for using [Git](https://rogerdudler.github.io/git-guide/), a commonly used version control system.

### Test

You should test your solution to make sure it works. At the simplest level this means test various inputs and outputs to your solution. For software you should try many different inputs and ensure you get the result you expect; also make sure to try weird inputs like a `string` to an `int`. For a website you should make sure all links work and images load. While this can all be done manually there are multiple ways to automate your tests:

- [Python `unittest`](https://docs.python.org/3.8/library/unittest.html): a built-in python library that allows building a simple test suite for your code.
- [Google Test](https://github.com/google/googletest): a testing framework for C++ used by Google.
- [Travis CI](https://travis-ci.org/): a continuous integration service that can run automatic tests before deploying.

### Improve

If you encounter any problems in your _test phase_ you should go back to your solution and fix these. You may also think of better ideas while testing and want to incorporate these.

## Part 2: Sharing a Resource

_Create and share a resource that would allow someone else to replicate your project with minimal previous knowledge. This resource should be digital, and it can be any format you like: a video (or a series!), an online (printable) document, an entry on a tutorials website such as Instructables, a blog post...Or meet with people who could benefit from your solution to share how you created it and explain how it can help them._

There are so many ways to share a resource online but here are a few expanded versions of the suggestions above:

### GitHub

In a professional or open source context many coding solutions from websites to scientific software are commited to GitHub for the world to see. Some example projects:

- [Pytudes](https://github.com/norvig/pytudes): Python programs to practice or demonstrate skills.
- [2048](https://github.com/gabrielecirulli/2048): a popular game [running on GitHub pages](https://play2048.co/).

GitHub also provides free websites to projects hosted there. [Guide to GitHub Pages](https://pages.github.com/)

### YouTube

An explanatory video could be shared on YouTube with links in the dooblydoo to your solution.

_N.B.:_ While anyone with a Google account can post to YouTube you should take care. Check the [Scouting Social Media Guidelines](https://members.scouts.org.uk/supportresources/4109/social-media) and [factsheet](https://members.scouts.org.uk/factsheets/FS103011.pdf). Do not share any publically identifiable information about yourself.

### PDF

Remember that this is likely to be in addition to one of the other methods listed here. It is useful to have a reference document but it would be easier to provide code/assets to people. You could create a simple pamphlet in the office software of your choice and distribute a PDF version of it.

### Blog

Ask your Scout Group if you can share a blog post on your group website about your new tool. Alternatively you can set up a free blogging account and create a blog to detail progress on the project and the final result:

- Free blogs with [Blogger](https://www.blogger.com/about/?r=2)
- Free blogs with [WordPress](https://wordpress.com/)

### Sharing in Person

_During the current pandemic this could be done via video conferencing_

While there are many excellent ways to share content online nothing beats a hands-on demonstration of your work. You can talk people through the project at a high level while demonstrating how it works. It also offers an opportunity for questions you may not have envisaged when sharing your work via other means. These may also lead to further improvements to your project.
