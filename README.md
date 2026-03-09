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

## 0.0.1

This first initial step will focus on getting rough components designed for the site. The following components will be required for the first unstable version:

- Semantic Elements (header, footer, nav, main, etc.)
- Page Layouts (Grid, Flex)
- Custom unstyled pre-built components (Cards, Banners)

# 0.0.2

`0.0.2` will focus on matching the design of the website my wife wants. This is heavily inspired by old internet forums and has quite an 'old fashioned' look and feel compared to modern web designs.

- Custom CSS to match the design
- Floating navigation pills on the banner
- Cards with static content

## 0.0.3

`0.0.3` will focus on providing a basic client-side API for setting dynamic content in Vue. This will make use of **Primitives** that `reka-ui` provides to build dynamic UI components.

- Configure existing components to use primitives
- Update styling to make use of props
-
