<h1 align="center">Gruvbox Midnight 🌙</h1>

Gruvbox Midnight is a theme for your Discord client that combines the best elements of the popular [Midnight](https://github.com/refact0r/midnight-discord/tree/91c52e4d056f1b2502ebb3709abb59924f0543a4) and [Radial Status](https://github.com/DiscordStyles/RadialStatus/tree/e361ae760dd8b88f6c187efa11a83e9aea3afd83) themes.

![Friends List Preview](Screenshots/Friends_List.png)<br><br><br><br>
<h2 align="center">Installing </h2>

### 🐧 For Linux Users

```bash
# Navigate to BetterDiscord themes folder
cd ~/.config/BetterDiscord/themes/
# Download the theme
wget https://raw.githubusercontent.com/ashdgahsghasahhh/Gruvbox-Midnight/main/Gruvbox.Midnight.theme.css
```

### 🪟 For Windows Users
1. Download the theme file:
[Gruvbox.Midnight.theme.css](https://raw.githubusercontent.com/ashdgahsghasahhh/Gruvbox-Midnight/main/Gruvbox.Midnight.theme.css)  
3. Copy it to BetterDiscord themes folder:  
   `%appdata%\BetterDiscord\themes`  
![Messages Preview](Screenshots/Messages.png)<br><br>
## 🔄 Updating
### Linux users
```bash
cd ~/.config/BetterDiscord/themes/
rm Gruvbox.Midnight.theme.css  # Remove old version
wget https://raw.githubusercontent.com/ashdgahsghasahhh/Gruvbox-Midnight/main/Gruvbox.Midnight.theme.css
```
For Windows: Re-download and replace the theme file.<br><br><br><br>

<h1 align="center">🖼️ Custom Backgrounds</h1>

Want to give your theme a personal vibe?  
**Pick from a selection of built-in backgrounds** by simply uncommenting the one you like and commenting out the others:

```css
--background-image-url: url('...Kurumi-Ebisuzawa.png?raw=true');  // Active background
# --background-image-url: url('...anime-girl.png?raw=true');      // Inactive
```
### 🔍 Preview all available options below — the screenshots will show you exactly how each one looks in Discord.
| ![ex1](Screenshots/ex1.png) | ![ex2](Screenshots/ex2.png) | 
|----------------------------|------------------------------| 
| ![ex3](Screenshots/ex3.png) | ![ex4](Screenshots/ex4.png) |


### 🙌 Not feeling any of them? No worries.
You can add your own custom background. Just find an image you like (preferably a direct link ending in .png, .jpg, etc.) and paste the URL between these two parts:
```css
--background-image-url: url('⬅️ paste_here ➡️?raw=true');
```
Be sure to comment out all the other background lines so yours is the only one left.

### 💡 Pro tip: backgrounds with dark or semi-transparent areas look best, especially with blur enabled (--panel-blur: on).<br><br><br><br>

## 🛠️ Troubleshooting
- **Theme not showing?**  
  Make sure file has `.theme.css` extension
- **Visual glitches?**  
  Disable other themes and restart Discord
- **Still stuck?**  
  [Open an issue](https://github.com/ashdgahsghasahhh/Gruvbox-Midnight/issues) - I'll help! 🤝<br><br><br><br>
## 💖 Enjoying the Theme?
- Star the repo ⭐
- Share with friends
- Contribute improvements!<br><br><br><br>
## 📜 Credits
Special thanks to:
- [Midnight](https://github.com/refact0r/midnight-discord) for the base inspiration
- [Radial Status](https://github.com/DiscordStyles/RadialStatus) for status indicators
- [Gruvbox color palette creators](https://github.com/morhetz/gruvbox)
