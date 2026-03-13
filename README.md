# beehive 

Beehive is a project I am designing for my wife. It is initially going to be built as a static website to display their portfolio work and allow for basic CRUD operations and over time grow into a full-fledged portfolio management system allowing artists to showcase their work and manage their portfolio.

# Dependencies

This project currently uses the following dependencies for a simple static site.

- **Vue 3**
- **JavaScript/TypeScript**
- `reka-ui`

# Installation

To install, simply clone the repository and install the dependencies using your preferred JavaScript package manager (npm, yarn, pnpm, etc.).

```bash
git clone https://github.com/devjacjef/beehive.git
cd beehive
npm install
```

# Roadmap

This is a rough roadmap for `beehive`. The current focus is to create an MVP based off of the designs provided to me by my wife.

# 0.0.1

The first stag will be focused on developing a rough MVP based on the designs provided to me. This can be comprised of non-composed elements to explore what may/may not require composition.

At this stage quickly create basic styling.

- Scaffold Home Page
- Scaffold About Page
- Scaffold Art Gallery Page
- Scaffold Projects Page 
- Scaffold Commissions Page
- Scaffold Blogs Page

There are some brief components that could be created but otherwise, try to just focus on getting place holder content down.

# 0.0.2

For `0.0.2` it would be a good idea to quickly sift through the code and identify the components that require to be composed. Some components that could be quickly moved into Vue components include:

- Navigation Links
- Page Banner
- Page Logo

There are also other UI components that can be explored like Cards however, an external library may be able to provide components fit for that use-case.

# 0.0.3

`0.0.3` should be about refining an MVP into something that looks okay. This should focus on the overall styling on the site, matching the designs rough styling and then making sure to scope these styles accordingly.

# Future Considerations

Since this page is for an artist there are a lot of measures to consider. Firstly, it would be immoral to be use GenAI for any part of this project. Using it to support the developer in terms of documentation is quite alright however, it is important to not let that generate anything.

Another consideration is preventing an AI system from getting access to the page and finding ways to counter-act AI from stealing art work for training data. I would like to explore libraries that may manipulate images to provide something in the background that messes with them. On top of that, it would be fun to explore preventing screenshots or downloads of images directly from the site but that may require a lot of work.
