
# quick-structure

A CLI tool to quickly create and manage folder/file structures for Next.js applications based on templates. Automate your repetitive tasks with ease!

## Installation

To install `quick-structure` globally, use one of the following commands:

### Using npm:
```bash
npm install -g quick-structure
```

### Using yarn:
```bash
yarn global add quick-structure
```

## Commands

### List Templates
To display all available templates:
```bash
quick-structure list
```

### Create Structure
To create a folder and file structure based on a selected template:
```bash
quick-structure structure [TEMPLATE_ID]
```
Replace `[TEMPLATE_ID]` with the template ID, for example:
```bash
quick-structure structure 1
```

### Force Command
To skip the confirmation and create the structure automatically:
```bash
quick-structure structure 1 --force
```

### Check Version
To check the current version of `quick-structure`:
```bash
quick-structure --version
```

### Help
To display the help message with all available commands:
```bash
quick-structure --help
```
or
```bash
quick-structure -h
```

## Available Templates

- **Default Structure**: Basic structure for a Next.js app.
  - Folders: `src/app/about`, `src/app/contact`, `public/assets/images`, `API/GET`, `API/POST`, `API/PUT`, `API/DELETE`
  - Files: `src/app/about/page.tsx`, `src/app/contact/page.tsx`

- **Blog Structure**: A simple blog structure with posts and dynamic routing.
  - Folders: `src/app/posts`, `public/images`, `API/GET`
  - Files: `src/app/posts/page.tsx`, `src/app/posts/[id].tsx`

