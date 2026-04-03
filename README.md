# Site Owner’s Manual: Forest Therapy with Lori

Welcome to the backend of your website! Because your site is custom-built and lightweight, there is no clunky software to log into. You own the actual code. 

Your site lives in a repository (a digital folder) on GitHub. Making changes is as easy as editing a Word document, provided you know where to look.

---

## 1. How to Access Your Site’s Code
1. **Log in** to your GitHub account.
2. [cite_start]**Navigate** to your website repository: [https://github.com/Vitro-Media-Lab/Forest-Therapy-With-Lori](https://github.com/Vitro-Media-Lab/Forest-Therapy-With-Lori) [cite: 47]
3. **Click** on the file named `index.html`. This file contains all the text and layout for your website.
4. In the top right corner of the file viewing box, **click the Pencil Icon** (Edit this file).

## 2. The Golden Rule of Editing
When you are looking at the code, you will see a lot of symbols, brackets `< >`, and CSS styling. **Only edit the regular text.** If you accidentally delete a `<p>` or a `</div>`, the layout might break. 

> **Pro-Tip:** Use `Ctrl + F` (Windows) or `Cmd + F` (Mac) to search for the exact sentence you want to change.

## 3. How to Change Text
If you want to update your "About" section or add a new service, simply find that text in the document and type over it.

**Example:**

HTML
```
<h2>The Wisdom of the Forest.</h2>
<p>Forest therapy is more than a walk in the woods...</p>

<h2>Your New Title Here</h2>
<p>Your new paragraph text goes here...</p>
```
## 4. How to Swap Images

Your images are stored in a folder called assets. To change a photo (like your headshot or the background tree canopy):

**Step A: Upload the new photo**
1. Go back to your main repository page.
2. Click on the assets folder.
3. Click "Add file" (top right) -> "Upload files".
4. Upload your new image (e.g., new-headshot.jpg) and click Commit changes to save it.

**Step B: Update the code**
1. Open index.html and click the Pencil Icon.
2. Search for the old image name (e.g., 1000038680.jpg).
3. Carefully replace the old file name with the new one.

- Before: ```<img src="./assets/1000038680.jpg" alt="Lori Young">```
- After: ```<img src="./assets/new-headshot.jpg" alt="Lori Young">```

## 5. How to Update Google Forms

If you create a new Google Form for a specific walk or retreat, you can easily swap the links.
1. In index.html, search for google.com/forms.
2. You will find a link that looks like this: src="https://docs.google.com/forms/d/e/YOUR-LONG-FORM-LINK/viewform?embedded=true"
3. Carefully delete the old link inside the quotation marks " " and paste your new Google Form link.
4. Ensure it ends with /viewform?embedded=true so it fits nicely in the box.

## 6. Saving & Publishing Your Changes

When you are done making edits in the index.html file, your changes are not live until you save them.
1. Scroll to the top right of the page and click the green Commit changes... button.
2. A small box will pop up. You can write a brief note to yourself (like "Updated summer walk dates").
3. Click the green Commit changes button to confirm.
4. **That’s it!** GitHub will automatically rebuild your site. It usually takes about 1–3 minutes for the changes to appear on your live website.
