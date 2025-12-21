# KatMere Creations 🎨

The official portfolio and shop website for **KatMere**, a variety streamer and digital artist.

🔗 **Live Site:** [https://katmerecreations.github.io](https://katmerecreations.github.io)

## 📂 Project Structure
* `index.html`: The main code for the website.
* `images/`: Folder containing all stickers, portfolio art, and profile pictures.

## 🛠 How to Update the Site

### 1. Adding New Portfolio Art
1.  Save the new image as a **.png** file inside the `images` folder (e.g., `port17.png`).
2.  Open `index.html`.
3.  Scroll down to the **Portfolio Section**.
4.  Copy the last line and update the number so it matches your new file:
    ```html
    <div class="portfolio-item"><img src="images/port17.png" class="portfolio-img zoomable"></div>
    ```

### 2. Adding New Stickers
1.  Add the new sticker image to the `images` folder.
2.  Open `index.html` and scroll to the **Shop Section**.
3.  Copy one of the existing "Card" blocks (from `<div class="card">` to `</div>`).
4.  Paste it at the bottom of the list and update the **Image Name** and **Title**.

### 3. Changing Commission Status
1.  Open `index.html`.
2.  Search for **"STATUS:"**.
3.  Change the text (e.g., from "CHECK KO-FI" to "CLOSED").

---
*Built with ❤️ for KatMere.*