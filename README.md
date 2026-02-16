# HTML-Newspaper-M_WASEEL_22P-9147

# HTML Newspaper Recreation - روزنامہ انقلاب / Daily Inqilab

## Student Information
- Name: M. Waseel  
- Roll Number: 22P9147  
- Section: BSSE 8-A  

## Original Newspaper
- Name: روزنامہ انقلاب (Daily Inqilab)  
- Date: Appears to be a modern/mock front page (dated around 13–15 August 2024 in the recreation)  
- Source: https://en.wikipedia.org/wiki/Daily_Inqilab_(Lahore)  

## Project Description
This project is a digital recreation of a front page from روزنامہ انقلاب (Daily Inqilab), one of Pakistan's prominent Urdu-language newspapers published from Lahore.  
The layout faithfully mimics the traditional newspaper style with a large Nastaliq masthead, multi-column news structure, prominent central headline about dividing Sindh and Balochistan into six districts each, supporting side columns, and boxed news snippets at the bottom — all built using only HTML and inline CSS.  
The design adopts a black-and-white vintage aesthetic with subtle paper texture to give an authentic old newspaper appearance.

## Features Implemented
- Responsive single-page layout using Flexbox (center column dominant, side columns compact)
- Inline CSS only (no external stylesheets or frameworks)
- Vintage newspaper styling: grayscale filter on images, subtle paper texture background, double/separator lines, text shadows, and box shadows
- Hierarchical typography: oversized masthead title, large main headline, smaller supporting headings
- Embedded relevant images: vintage Dawn newspaper scans, Pakistan district map, Maulana Fazlur Rehman portrait (all in grayscale)
- Realistic newspaper elements: price/date/issue bar, dense justified text blocks, bottom news snippets in boxed format
- Right-to-left (RTL) direction support for proper Urdu text rendering (dir="rtl" on html tag)
- Clean, balanced visual hierarchy with the center block significantly larger than side blocks

## Challenges Faced
- Matching the dense, irregular column layout of traditional Urdu newspapers while keeping the center content dominant and side blocks compact (solved using precise flex ratios and padding adjustments).  
- Ensuring good readability of text over the textured background in black-and-white mode (solved by adding semi-transparent overlays and careful contrast/shadow tuning).
