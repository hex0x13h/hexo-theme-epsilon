# Hexo Theme: Epsilon
![license](https://img.shields.io/github/license/hex0x13h/hexo-theme-epsilon)
![language count](https://img.shields.io/github/languages/count/hex0x13h/hexo-theme-epsilon)
![repo size](https://img.shields.io/github/repo-size/hex0x13h/hexo-theme-epsilon)



Epsilon is a minimal, clean, and highly customizable theme for [Hexo](https://hexo.io/).  
This theme is my first attempt at developing a Hexo theme, so please forgive any shortcomings! 😊  

## 📖 Features

- **Customizable Layout**: Easily configurable sections for your blog, portfolio, or personal projects.
- **Typography**: Supports custom fonts like `IosevkaAile` and `Podkova`.
- **Markdown Rendering**: Includes beautiful code block syntax highlighting with [highlight.js](https://highlightjs.org/).
- **Multilingual Support**: Built-in support for multiple languages via `languages/*.yml` files.
- **Customizable Tags and Projects**: Add and manage highlighted projects and tags through the `_config.yml`.
- **RSS and JSON Feeds**: Automatic generation for RSS and JSON feeds.

## 🖊 Usage

```
npm install --save hexo hexo-cli hexo-server hexo-renderer-ejs hexo-renderer-markdown-it hexo-renderer-stylus hexo-generator-index hexo-generator-archive hexo-generator-category hexo-generator-tag hexo-generator-feed hexo-generator-json-feed hexo-pagination hexo-browsersync hexo-clean-css hexo-generator-sitemap

--- 

mkdir source/blog
touch source/blog/index.md

vim source/blog/index.md
```

```
---
title: Blog
layout: blog
---

```

## 🎨 Custom Fonts

Epsilon includes the fonts IosevkaAile and Podkova. You can add more fonts by updating the source/fonts/ folder and modifying source/css/style.css.

## 🖼 Screenshots
<img width="1354" alt="image" src="https://github.com/user-attachments/assets/5537eabf-622a-4925-affc-6b00a70341bc" />

<img width="1306" alt="image" src="https://github.com/user-attachments/assets/dba6912e-8d41-40c3-8db8-3d7778a4abe3" />

<img width="976" alt="image" src="https://github.com/user-attachments/assets/2098a2c3-6d17-4166-909a-0a54ed058e6d" />

## ✅ Admonition Boxes
In your Markdown file, use this format:
```
<div class="admonition TYPE">
  <p>Your content goes here.</p>
</div>
```
Replace TYPE with one of the following:
	•	info or note
	•	warning or important
	•	danger or critical

These will automatically get styled with colors, borders, shadows, and icon titles like “⚠️ Warning”.

⚠️ Example: Warning Box
```
<div class="admonition warning">
  <p>Do not use development keys in production.</p>
</div>
```


## 🚀 Roadmap
	•	Expand plugin integrations

## 🙏 Acknowledgements
	•	Hexo: A fast, simple & powerful blog framework.
	•	highlight.js: For beautiful syntax highlighting.
	•	Open Source Fonts: IosevkaAile and Podkova.

## ❤️ About Me

Hi there! I’m a beginner in Hexo theme development, and this is my first attempt at building a theme.
Your feedback and suggestions are always welcome! Please report issues or contribute via pull requests.

This theme is modeled after [Xe Iaso](https://xeiaso.net/)).


Thank you for your interest in Epsilon! If you have any questions, feel free to reach out or open an issue.  
Happy blogging! 

