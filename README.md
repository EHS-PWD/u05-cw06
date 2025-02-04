### **U06-CW06 - Float Positioning and Overflow Settings**

**Objective:**  
Students will enhance the "Speedy the Russian Tortoise" profile page by applying `float` and `overflow` properties. This assignment introduces `float`, `overflow`, and `clear` to properly position images and manage text flow.

### **1. Open Your Project**

- Open your **`profile.html`** and **`profile-style.css`** files in your text editor.

### **2. Create the Bio Section in HTML**

- Locate the `<body>` tag in **`index.html`**.
- Find the existing `<div class="profile-card">` section.
- Below the closing `</div>`, add a new **bio section** using the following HTML:

```html
<div class="bio-section">
  <img src="speedy.png" alt="Speedy the Russian Tortoise" class="bio-img" />
  <p class="bio-text">
    Speedy is a Russian tortoise with a love for adventure. Whether basking in
    the sun or munching on fresh greens, Speedy enjoys life at a slow, steady
    pace.
  </p>
</div>
```

- Save **`profile.html`**.

### **3. Style the Bio Section Container**

- Open **`profile-style.css`**.
- Add a new CSS rule set called `.bio-section`:
- Ensures the section does not take up the full width by adding a width of 80%
- Prevents it from becoming too wide by setting a max-width of 500px;
- Centers the bio section with a margin of 20px and auto (2 values)
- Give it a padding of 15px
- Adds a visible border that is 2px in thickness, solid styling, and a color of #333333
- Set it to have a background of #ffffff

### **4. Make the Bio Image Float**

- Below the `.bio-section` rule set, add a new rule set called `.bio-img`
- Ensures the image is small by havin it with a width of 120px
- Maintains aspect ratio of the height to auto
- Float the image to the left
- Adds space between the image and text with a margin-right of 15px
- Adds a border around the image that is 3px in thickness, solid styling, and a color of #333333

### **5. Ensure the Text Wraps Properly**

- Below the `.bio-img` rule set, add a new rule set called `.bio-text`
- Prevents text from wrapping awkwardly but setting the overflow to auto

### **6. Test Your Changes**

- Open **`profile.html`** in Google Chrome.
- Verify that:
  - The bio section appears below the profile card.
  - The image floats to the left of the bio text.
  - The text correctly wraps around the image.
  - The section does not collapse due to floating.
- Use the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to check for errors.

### **7. Submit Your Work**

- Once you've confirmed that the styling works, submit the following:
  - Upload your **updated `prolfile-style.css`** file to Google Classroom.
