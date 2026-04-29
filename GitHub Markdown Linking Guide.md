# 🔗 GitHub Markdown Linking Guide

This guide shows how to add images and links in a GitHub README.

---

## 📸 1. Display an Image

### Basic image
```md
![alt text](images/photo.jpg)
```

### Description
- `alt text` → description for accessibility, it will show up if image breaks
- `images/photo.jpg` → relative path to image  
- Store images in an `/images` folder  

---

## 2. 🖼️ Resize or Center an Image (HTML)

### Syntax
```html
<p align="center"> <img src="images/photo.jpg" width="400"> </p>
```
### Description
- `width="400"` → controls size
- `width=40%` → also available in percentages
- `align="center"` → centers image

## 3. 🔗 Link to Another Repository
Syntax
```md
[Project Name](https://github.com/yourusername/project-repo)
```

## 4. 📁 Link to a File in This Repository
Syntax
```md
[View Schematic](hardware/schematic.pdf)
```
### Description
- Uses relative path
- Works for PDFs, code, images

## 5. 📂 Link to a Folder in This Repository
Syntax
```md
[Open Images Folder](images/)
```

## 6. 🌐 Link to External Website
Syntax
```md
[Website Name](https://example.com)
```

## 7. 🔗 Make an Image Clickable
Syntax
```md
[![alt text](images/photo.jpg)](https://github.com/yourusername/project)
```

## 8. Make a Guide Like This

Syntax
```md
```md
Thing in the box
```[ignore this]
```
### NOTE
The very fact that this is in .md means displaying .md syntax is hard

So please note the "[ignore this]", this is needed to prevent the file from breaking entirely
