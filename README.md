# Small Image Tool


I like simple programs that do one thing well and are easy to use. Even better if you don’t have to install anything. Modern browsers are pretty powerful, so here is a **simple one-file web app** for removing single-color image backgrounds, cropping, and erasing.  

It runs entirely in your browser — **no installation required**.  

The main idea is to quickly delete white (or any other solid-color) backgrounds from pictures or plots you want to use in PowerPoint, documents, or elsewhere. You can also crop them or cut out parts of it.

Even better: you can use it **directly online**, since GitHub lets me host static websites:  
👉 [Try the Small Image Tool here](https://berger-lukas.github.io/Small-Image-Tool/)


You can also use it locally of course:

## How to Use

1. **Download** the HTML file from this repository (`index.html`).
2. **Double-click** it — it will open in your default browser (Chrome, Firefox, Safari, Edge).
   - No setup, no Node.js, no Python. Just one file.
3. **Upload an image** with the file selector.
4. Use the tools:
   - **Color Remover** → click on a color in the image, adjust **Threshold** (range of colors) and **Feather** (softness), then **Apply**.
   - **Brush Erase / Restore** → paint transparency or restore parts of the image (hold **Space** to toggle temporarily).
   - **Crop / Delete Rect** → crop the image to a rectangle or make a selected area transparent.
   - **Undo / Redo** → buttons or shortcuts (`Ctrl/Cmd+Z`, `Shift+Ctrl/Cmd+Z`).
5. When you’re done, click **Download PNG** to save your edited image with transparency.

##  Privacy & Security

- Everything runs **locally in your browser**.
- **No images are uploaded** — your files never leave your computer.
- Works offline

## 📋 License


This project is released under the MIT License — see the [LICENSE](LICENSE) file.
