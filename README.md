# Abhijth's notes

Personal notes and digital garden of Abhijith M.

This site is built using the [Quartz 4](https://github.com/jackyzha0/quartz) project as a base.

## Features

- **Obsidian-Ready**: Manage your blog directly as an Obsidian vault.
- **Modern Design**: Clean, dark-first interface with typography optimized for readability.
- **Fast Build**: Static site generation with Quartz for lightning-fast loading times.

## Setup

1.  **Clone this repository**:
    ```bash
    git clone https://github.com/Blackhawk95/pwolide.git
    cd pwolide
    ```
2.  **Install dependencies**:
    ```bash
    npm install
    ```
3.  **Preview locally**:
    ```bash
    npx quartz build --serve
    ```
4.  **Build for production**:
    ```bash
    npx quartz build
    ```

## Content

All blog posts and pages are stored in the `notes/` directory. You can edit them using any Markdown editor or by opening the folder as an Obsidian vault.

## Deployment

The site is configured for automatic deployment via Netlify.
- **Publish Directory**: `public`
- **Build Command**: `npx quartz build`
