# My Personal Portfolio | Tefo Abigail Gasenna

This is a website I built to show my profile as a **Computer Systems Engineering** student. I wanted a design that looks bold and "techy," so I used a **Red and Black** theme with very large text.



##  My Design Choice
I went for a "Brutalist" look. This means:
* **Bold Colors:** I only used Black, Red, and White to make it look sharp.
* **Big Text:** I used the **Inter** font for headers so they are the first thing you see.
* **Simple Layout:** I kept it clean and didn't add unnecessary decorations.

##  How I Built It

### 1. Text that Changes Size
I didn't want the text to look huge on a laptop but tiny on a phone. I used a CSS trick called `clamp()`. 
**How it works:** This tells the browser to automatically resize the text based on the screen size so it always fits perfectly. This way, I don't have to write different code for every single device.



### 2. Red Hover Effect on Photos
I wanted my photos to look more artistic. I used a CSS setting called `mix-blend-mode`.
* **The Effect:** My photos are black and white. When you move your mouse over them, they blend with the red background behind them.
* **Why:** It makes the site feel interactive without me needing to edit the photos in an external app like Photoshop.

### 3. Side-by-Side Sections
I used the **Bootstrap Grid** to make sure my Education and Skills stay next to each other on big screens. 
* **The Logic:** I divided the row into columns. This keeps the information organized and professional instead of just being one long list.



### 4. Wide Footer Image
At the bottom of the page, I wanted the image to touch both sides of the screen. I used `width: 100%` and `object-fit: cover`. 
* **Result:** The image fills the whole space properly without getting stretched or looking blurry.

### 5. Moving Around the Site
I used "Anchor Tags" (links that point to specific IDs like #about). I added `scroll-behavior: smooth` in my CSS so that when you click a link, the page glides down instead of jumping instantly.



## Files in this Project
* **index.html**: The main structure and text of the site.
* **style.css**: All the colors, fonts, and layout rules.
* **/images**: This folder holds my profile pictures and the background photo.



Author: **Tefo Abigail** 
Course: **Computer Systems Engineering Student**