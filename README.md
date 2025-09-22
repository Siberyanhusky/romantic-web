# The Summer I Turned Team Conrad

A beautiful, responsive web page featuring a heartfelt letter with background music and elegant design.

## 🌟 Features

- **Romantic Design**: Elegant typography with Georgia serif font
- **Background Music**: Auto-playing background music with play/pause controls
- **Responsive Layout**: Optimized for both desktop and mobile devices
- **Image Integration**: Photo positioned alongside the narrative text
- **Modern Styling**: Semi-transparent overlays and smooth transitions

## 📁 File Structure

```
project-folder/
├── index.html              # Main HTML file
├── wallpaper-love.png       # Background image
├── Moment.jpg              # Photo displayed with the letter
├── Cinnamon-Girl.mp3       # Background music
└── README.md               # This file
```

## 🚀 Setup Instructions

1. **Download/Clone** the project files
2. **Prepare Assets**: Make sure you have the following files in your project folder:
   - `wallpaper-love.png` - Background wallpaper image
   - `Moment.jpg` - Photo to display with the letter
   - `Cinnamon-Girl.mp3` - Background music file

3. **Open the Page**: Simply open `index.html` in your web browser

## 🎨 Design Elements

### Layout
- **Header**: Title and subtitle with text shadow effects
- **Main Content**: Two-column layout (desktop) with photo on the left and text on the right
- **Mobile**: Stacked layout for smaller screens

### Styling
- **Background**: Full-screen wallpaper with fallback color
- **Text Container**: Semi-transparent dark overlay for readability
- **Photo**: 300px width with rounded corners and shadow
- **Music Button**: Fixed position with hover effects

### Typography
- **Font Family**: Georgia serif for elegant readability
- **Text Shadow**: Applied to header for better contrast
- **Line Height**: 1.8 for comfortable reading

## 🎵 Music Controls

- **Auto-load**: Music preloads but doesn't auto-play (browser policy)
- **Volume**: Set to 30% by default
- **Controls**: Fixed play/pause button in bottom-right corner
- **Format**: MP3 audio support

## 📱 Responsive Design

### Desktop (>800px)
- Two-column layout with photo beside text
- Full-size elements and spacing

### Mobile/Tablet (≤800px)
- Single-column layout with photo above text
- Optimized font sizes and spacing
- Centered photo alignment

## 🛠️ Customization

### Changing Content
- Edit the text content in the `.narration-content` section
- Replace "Dear Vio," and "Always, Beryan" with your desired names
- Modify paragraphs as needed

### Styling Adjustments
- **Photo Size**: Adjust `.narration-image` width value
- **Colors**: Modify background colors and text colors in CSS
- **Fonts**: Change font-family in the body CSS rule
- **Spacing**: Adjust padding and margins in respective CSS classes

### Assets
- **Background**: Replace `wallpaper-love.png` with your preferred wallpaper
- **Photo**: Replace `Moment.jpg` with your chosen photo
- **Music**: Replace `Cinnamon-Girl.mp3` with your preferred background music

## 🌐 Browser Compatibility

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Audio Support**: MP3 format supported in all modern browsers
- **CSS Features**: Uses modern CSS including Flexbox and media queries

## 📋 Technical Details

### HTML Structure
- Semantic HTML5 structure
- Proper meta tags for responsive design
- Audio element with fallback support

### CSS Features
- Flexbox layout for responsive design
- Media queries for mobile optimization
- CSS transforms and transitions
- Background image handling with fallback

### JavaScript Functionality
- Audio play/pause control
- Error handling for audio playback
- Dynamic button text updates

## 🎯 Usage Tips

1. **Audio Permissions**: Some browsers require user interaction before playing audio
2. **File Paths**: Ensure all asset files are in the same directory as the HTML file
3. **Image Formats**: Use common image formats (JPG, PNG) for broad compatibility
4. **Audio Formats**: MP3 is recommended for broad browser support

## 🔧 Troubleshooting

### Common Issues
- **Audio not playing**: Check browser audio permissions and file path
- **Images not loading**: Verify file names match exactly (case-sensitive)
- **Layout issues**: Check CSS media query breakpoints
- **Font rendering**: Ensure fallback fonts are specified

### Browser Console
Use F12 Developer Tools to check for any error messages in the console.

## 📄 License

This project is open source and available under the MIT License.

---

*Created with love for preserving beautiful memories* ❤️
