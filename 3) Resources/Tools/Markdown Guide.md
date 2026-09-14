---
aliases:
  - Guide
  - Obsidian Guide
tags:
  - "#obsidian"
Topic: Obsidian Guide
Start Date: 2026-06-30
Publish Day: 3026-07-04
---

> [!warning]
> - Ignore Properties right now.



`Start From Here`
# What is Markdown?

> [!info] 
> - **Markdown** is a *lightweight markup language* used to format plain text using simple symbols instead of graphical buttons.

> [!info]
> - Rather than clicking **Bold**, **Italic**, or **Heading** like you would in Microsoft Word or Google Docs, you write a *few special characters *==(# - ** > )==, and applications that support Markdown automatically format your text.
> 


# Basic Markdown Syntax

## 1-Headings:
There are six heading levels in Markdown. Use the `#` symbol as the n° of the heading elt.

### Syntax
```md
# Heading 1            ## Heading 2            ###### Heading 6
```
`Try & See`
-># Heading 1( *Don't Forget the space here* )(the biggest one)
->## Heading 2 ... ->###### Heading 6  (the smallest one)


## 2-Bold:
Just put 
```md
**Word** (Without spaces) 
```
`Output` -> **Bold**   VS Bold (Normal)


## 3-Italic:

### Syntax
```md
*Word* (Without spaces) 
```
`Output` ->*italic*  VS italic 


## 4-Bullet Item:

### Syntax
`-`+`space ` 

- Bullet Item 1
	- Nested Item  `Enter` + `Tab`
	- 2...
		- ...
- Bullet Item 2 (2 `Enter` to return)


## 5-Numbered List:
`Write 1. (Number + Dot + Space )`
1. one (Don't Forget space)
2. two ... *Tab Enter & the number List Continue Automatically*
3. ...


## ==6-Links:==

- **Back Links:**
to create link to another note : [[]]
[[BackLinks]]   ` Double Click in the line to see the Syntax `

We can create a link to a note even if it's not exist .
When click on the link it create the note automatically -> [[Create]]
`Click on the link For more Info`  [[BackLinks]]


- **External link:** 
[](here the url)  <-**tab first**  
-> Single braquet and the URL inside ().
[Click in the line to see the Syntax & Try](https://github.com/)


## 7-Highlight Text:

-> ==Text ==between two equals == ==

## 8-Strike Through:
Just do (~~ )& write the text
~~strike through

## 9-CheckBox:
`-`+`space`+`[]`+`[ ]`+`space`
- [ ] CheckBox
- [x] Check

## 10-Tables:
Tables are useful for organizing and comparing information.

### Syntax
```md
| Feature | Obsidian | Notion |
|---------|----------|---------|
| Offline | ✅ | ❌ |
| Markdown | ✅ | Partial |
| Graph View | ✅ | ❌ |
```

### Output

| Feature    | Obsidian | Notion  |
| ---------- | -------- | ------- |
| Offline    | ✅        | ❌       |
| Markdown   | ✅        | Partial |
| Graph View | ✅        | ❌       |


## 11-Images
Markdown allows you to display images from a URL or from your local vault.

### Image from the Internet

```md
![Markdown Logo](https://example.com/image.png)
```

### Image from your Obsidian Vault (Recommended)

```md
![[image.png]]
```

> [!TIP]  
> The `![[image.png]]` syntax is specific to Obsidian and is the easiest way to embed local images.

---

## 12-Videos
You can embed local videos stored inside your Obsidian Vault.

### Local Video

```md
![[video.mp4]]
```

> [!NOTE]  
> Obsidian will display a built-in video player.

### YouTube Video

```md
[Watch on YouTube](https://www.youtube.com/watch?v=VIDEO_ID)
```

> [!INFO]  
> Standard Markdown creates a clickable link. To embed a YouTube player, HTML may be required depending on your Obsidian settings.

---

## 13-Audio Files
Embed audio files directly into your notes.

### Syntax

```md
![[audio.mp3]]
```

or

```md
![[audio.wav]]
```

---

## 14-PDF Files
You can preview PDF files without leaving your note.

### Syntax

```md
![[document.pdf]]
```

> [!TIP]  
> Obsidian supports images, videos, audio files, and PDF documents directly from your Vault.




# Properties:
- Apear in the top of the note (the first line exactly) just tab
`---`+`Enter` & then go to the bottom & see.


- The properties help us add Metadata to the notes:
	- **Aliases :** Means another names to the note, work with links or even in search. [[TEST2]]
	- **Tags :** Help us classify our notes in categories.
		- Like here #obsidian when tab here we see all the note classified in Obsidian theme.
	- **CssClasses:** This we use it when we want to add a style css . 
		- [[Learn more about CssClasses]]



# Obsidian Features (Later)
- Properties
- Backlinks
- Wikilinks (`[[ ]]`)
- Canvas
- Templates
- Graph View
- Tags
- Search
- Command Palette
- Plugins
- Daily Notes
- Attachments 