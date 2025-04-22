![GitHub stars](https://img.shields.io/github/stars/ECL-Adler400/russian-roulette-bookmarklet)
![GitHub forks](https://img.shields.io/github/forks/ECL-Adler400/russian-roulette-bookmarklet)
![GitHub license](https://img.shields.io/github/license/ECL-Adler400/russian-roulette-bookmarklet)
![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow?logo=javascript)


# Russian Roulette Bookmarklet

> PLAY RUSSIAN ROULETTE IN YOUR BROSER.

---

## 📋 Code
```bash
javascript:(function(){var c=[0,0,0,0,0,0];c[Math.floor(Math.random()*6)]=1;var g=false;alert("Welcome to Russian Roulette!");while(!g){if(!confirm("Pull trigger?"))break;var r=Math.floor(Math.random()*6);if(c[r]){alert("BANG! Game Over.");g=true}else alert("Click! Survived.")}})();
```

---

## 🚀 How to Use

Below are step‑by‑step instructions for Chrome, Edge, and Firefox. You only need to create a new bookmark and paste the code above into its URL field.

### Google Chrome / Microsoft Edge

1. Open the **Bookmarks Manager**:  
   - Chrome: `⋮` → **Bookmarks** → **Bookmark manager**  
   - Edge: `⋯` → **Favorites** → **Manage favorites**  
2. Click **Add new bookmark** (or **Add favorite**).  
3. Give it a name, e.g. `Russian Roulette`.  
4. In the **URL** field, paste the entire snippet from the **📋 Snippet** section above.  
5. Save.  


### Mozilla Firefox

1. Open **Bookmarks** → **Manage bookmarks** (or press `Ctrl+Shift+O`).  
2. Click **Organize** → **New Bookmark…**  
3. Enter **Name**: `Russian Roulette`  
4. In the **Location** (URL) field, paste the snippet from above.  
5. Click **Add**.  


---

### LICENSE

```text
MIT License

Copyright (c) 2025 ECL-Adler400

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
