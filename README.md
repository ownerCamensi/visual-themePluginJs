# Visual Theme Plugin JS  

A simple JavaScript library to help enhance your gaming website with customizable visual themes.  

## Features  
- Easy-to-use theme customization  
- Light and dark mode support  
- Smooth transitions between themes  
- Works with VS Code, ACode, and other editors that support plugins  

## Installation  

### Method 1: Via Plugin Import (Recommended)  
1. Open **VS Code** or **ACode** editor.  
2. Go to **Settings** > **Plugins** (if supported).  
3. Click **Import Plugin** and paste the repository URL:  
   ```  
   https://github.com/your-repo/visual-themePluginJs  
   ```  
4. Alternatively, copy the URL manually and import it.  

### Method 2: Manual Setup  
1. Clone the repository:  
   ```sh  
   git clone https://github.com/your-repo/visual-themePluginJs.git  
   ```  
2. Include the script in your HTML:  
   ```html  
   <script src="path/to/visual-themePluginJs.js"></script>  
   ```  

## Usage  
- Press **Ctrl + T** (or Cmd + T on macOS) to open the command palette.  
- Search for **"visual-theme"** and select your preferred theme.  
- Alternatively, check your `settings.json` for theme configurations.  

## Available Themes  
- **Dark Mode**  
- **Light Mode**  
- **Gaming Neon**  
- **Retro Pixel**  

## Configuration  
Modify `settings.json` to customize themes further:  
```json  
{  
  "visual-theme": {  
    "defaultTheme": "dark",  
    "animationSpeed": "0.3s"  
  }  
}  
```  

## Support & Contributions  
Feel free to contribute by opening issues or pull requests.  

**Thank you for your support!** 🚀
