# Fonts Used in Codidactic Board Game

This document lists all the fonts used in the Codidactic programming board game project, along with information on where to find, download and install them.

## Primary Fonts Used

### 1. Open Sans
- **Usage**: Main display font, used extensively throughout the game materials
- **Weights**: All. Light, Normal, Medium (500), Bold, ...
- **Download**: 
  - Google Fonts: https://fonts.google.com/specimen/Open+Sans
  - Free and open source (SIL Open Font License).

### 2. Public Pixel
- **Usage**: Pixel-art style font for retro/gaming aesthetic
- **Weights**: All. Regular, Bold, ...
- **Download**:
  - Dafont: https://www.dafont.com/public-pixel.font
  - OR Fontspace: https://www.fontspace.com/public-pixel-font-f47870
  - This font are licensed under the Creative Commons Zero v1.0 Universal. You can use them freely in your products & projects print or digital, commercial or otherwise. For more information about Public Pixel, go to https://www.ggbot.net/fonts .

### 3. Arial Family
- **Variants**: 
  - Arial (ArialMT)
  - Arial Bold (Arial-BoldMT)
  - Arial Black
- **Usage**: Programming block text and labels.
- **Where used**: CSS styling in SVG files for block programming elements.
- **Download**: 
  - Pre-installed on Windows systems.
  - For Linux: Install via package manager (fonts-liberation or ttf-mscorefonts-installer).
  - For Mac: Pre-installed.

### 4. System Fonts (Fallbacks)

#### Sans-serif (Generic)
- **Usage**: Fallback font for various text elements
- **Where used**: Mathematical operators (+, -, *, /, %, =), numbers, comparison operators.
- **Note**: Uses system default sans-serif font.

#### Monospace (Generic)
- **Usage**: Programming-related text where fixed-width is important
- **Where used**: 
  - Mathematical operators and symbols.
  - Programming syntax elements.
  - Comparison operators (==, <, >, <=, >=).
  - Variables (x, y).
- **Note**: Uses system default monospace font (typically Courier or similar)

## Font Installation Instructions

### For Complete Project Reproduction:

#### 1. **Install Open Sans** (Essential):

**Windows:**
1. Visit https://fonts.google.com/specimen/Open+Sans
2. Click "Download family" button
3. Extract the ZIP file
4. Select all .ttf files, right-click and choose "Install" or "Install for all users"
5. Alternative: Copy .ttf files to `C:\Windows\Fonts\`

**macOS:**
1. Visit https://fonts.google.com/specimen/Open+Sans
2. Click "Download family" button
3. Extract the ZIP file
4. Double-click each .ttf file and click "Install Font"
5. Alternative: Copy .ttf files to `/Library/Fonts/` or `~/Library/Fonts/`

**Linux:**
```bash
# Ubuntu/Debian:
sudo apt install fonts-open-sans

# Arch Linux:
sudo pacman -S ttf-opensans

# Manual installation:
# Copy .ttf files to ~/.fonts/ or /usr/share/fonts/
```

#### 2. **Install Public Pixel** (Essential for branding):

**Windows:**
1. Download from https://www.dafont.com/public-pixel.font
2. Extract the ZIP file
3. Right-click the .ttf file and select "Install" or "Install for all users"

**macOS:**
1. Download from https://www.dafont.com/public-pixel.font
2. Extract the ZIP file
3. Double-click the .ttf file and click "Install Font"

**Linux:**
1. Download from https://www.dafont.com/public-pixel.font
2. Extract and copy .ttf file to `~/.fonts/` or `/usr/share/fonts/`
3. Run `fc-cache -fv` to refresh font cache

#### 3. **Install Arial fonts** (Recommended):

**Windows:**
- Pre-installed with Windows.
- If missing, available through Microsoft Office installation.

**macOS:**
- Pre-installed with macOS.
- If missing, available through Microsoft Office installation.

**Linux:**
```bash
# Ubuntu/Debian (installs Microsoft Core Fonts including Arial):
sudo apt install ttf-mscorefonts-installer

# Alternative - Liberation fonts (Arial substitute):
sudo apt install fonts-liberation

# Arch Linux:
yay -S ttf-ms-fonts  # or use AUR helper
# Alternative: sudo pacman -S ttf-liberation
```

## General Font Installation Tips

### Windows:
- **Method 1**: Right-click font file → "Install" (current user) or "Install for all users" (admin required).
- **Method 2**: Copy font files to `C:\Windows\Fonts\`
- **Method 3**: Settings → Personalization → Fonts → Drag and drop font files.

### macOS:
- **Method 1**: Double-click font file → "Install Font"
- **Method 2**: Font Book app → File → Add Fonts
- **Method 3**: Copy to `/Library/Fonts/` (all users) or `~/Library/Fonts/` (current user).

### Linux:
- **System-wide**: Copy to `/usr/share/fonts/` or `/usr/local/share/fonts/`
- **User-only**: Copy to `~/.fonts/` or `~/.local/share/fonts/`
- **Refresh cache**: Run `fc-cache -fv` after manual installation.

## Font Hierarchy and Fallbacks

The project uses a hierarchical font system:
1. **Primary**: Open Sans for all main text.
2. **Branding**: Public Pixel for brand identity.
3. **Programming**: Monospace for code-like elements.
4. **Fallback**: System sans-serif for compatibility.

## Notes for Designers/Developers

- All fonts maintain good readability at small sizes used on game components.
- Color coding is used extensively with the typography (red, blue, green, yellow themes).
- Public Pixel font maintains the retro gaming aesthetic crucial to the brand.
- Monospace fonts ensure proper alignment of programming symbols and operators.
- SVG files contain embedded font specifications with proper fallbacks.

## License Considerations

- **Open Sans**: SIL Open Font License (free for commercial use).
- **Public Pixel**: Free for personal use (check license for commercial use).
- **Arial**: Microsoft proprietary (licensing required for distribution).
- **GNU FreeFont**: GPL with font exception (free for all uses).

For commercial reproduction of this board game, ensure proper licensing for all fonts, especially Arial and Public Pixel. 