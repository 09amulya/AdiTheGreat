 


# 🎴 Modern Profile Card UI

A stunning, responsive profile card UI featuring a modern design with interactive elements and smooth animations. This card showcases personal information with an elegant circular profile image, social media links (Instagram, GitHub, LinkedIn, Discord), and engagement statistics. Built with HTML, CSS, and vanilla JavaScript, it includes gradient buttons with hover effects, a sophisticated black-to-golden gradient background, and a functional message popup. The design incorporates Boxicons for visual elements and Google's Poppins font for typography. Perfect for personal portfolios, social media profiles, or landing pages, this card combines aesthetics with functionality to create an engaging user experience.

---

## ✨ Features

- **Responsive Design** - Adapts perfectly to all screen sizes
- **Interactive Social Links** - Direct links to Instagram, GitHub, LinkedIn, and Discord
- **Gradient Buttons** - Beautiful purple and pink gradient buttons with shine animation
- **Engagement Statistics** - Display likes, comments, and shares with hover effects
- **Message Popup** - Elegant modal notification system
- **Premium Animations** - Smooth transitions, hover effects, and scaling animations
- **Modern Gradient Background** - Black to light golden gradient for a luxurious feel
- **Custom Typography** - Google Poppins font for clean, professional text

---

## 🚀 Quick Start

### Prerequisites
- A web browser (Chrome, Firefox, Safari, Edge)
- Your profile image (JPG/PNG format)
- Your social media profile URLs

### Installation

1. **Download the files**
   ```bash
   git clone https://github.com/Divyansh-Kashiv07/profile-card.git
   cd profile-card
   ```

2. **Add your profile image**
   - Place your image in the same folder as `index.html`
   - Name it `divyansh profile photo.jpg.jpeg` or update the image path in the code

3. **Customize your information**
   - Open `index.html` in a text editor
   - Update your name and title in the text-data section
   - Add your social media URLs (see Customization section)

4. **Open in browser**
   - Double-click `index.html` or right-click → Open with → Browser

---

## 🎨 Customization Guide

### Update Personal Information

**Name and Title:**
```html
<div class="text-data">
    <span class="name">YOUR NAME</span>
    <span class="job">Your Title/Position</span>
</div>
```

### Social Media Links

Replace the placeholder URLs with your actual profiles:

**Instagram:**
```html
<a href="https://www.instagram.com/YOUR_USERNAME" target="_blank">
```

**GitHub:**
```html
<a href="https://github.com/YOUR_USERNAME" target="_blank">
```

**LinkedIn:**
```html
<a href="https://www.linkedin.com/in/YOUR_USERNAME" target="_blank">
```

**Discord:**
```html
<a href="https://discord.com/users/YOUR_USER_ID" target="_blank">
```

**YouTube (Subscribe Button):**
```html
<button class="button" onclick="window.open('https://www.youtube.com/@YOUR_CHANNEL', '_blank')">
```

### Update Statistics

```html
<span class="number">100k</span>  <!-- Change to your numbers -->
<span class="label">Likes</span>   <!-- Change labels if needed -->
```

### Change Colors

**Background Gradient:**
```css
background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 50%, #d4af37 100%);
```

**Button Gradients:**
```css
/* Subscribe button */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Message button */
background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
```

---

## 📁 File Structure

```
profile-card/
│
├── index.html                          # Main HTML file
├── divyansh profile photo.jpg.jpeg     # Profile image
└── README.md                           # This file
```

---

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling, animations, and gradients
- **JavaScript** - Interactive popup functionality
- **Boxicons** - Icon library for social media and stats
- **Google Fonts** - Poppins font family

---

## 🎯 Key Components

### Profile Image
- Circular design with white border
- Customizable with `object-fit: contain` for full image display
- Or use `object-fit: cover` for cropped circular view

### Social Media Buttons
- Four social platforms with custom colors
- Open links in new tabs
- Circular icon buttons with hover effects

### Action Buttons
- **SUBSCRIBE** - Links to YouTube channel
- **MESSAGE** - Triggers popup notification
- Gradient backgrounds with shine animation
- Lift effect on hover

### Analytics Section
- Three statistics (Likes, Comments, Shares)
- Icon scaling on hover
- Vertical layout with labels
- Customizable numbers and descriptions

### Message Popup
- Centered modal overlay
- Smooth fade-in and slide-down animations
- Close by clicking X button or outside the popup
- Customizable message content

---

## 🎨 Color Palette

| Element | Color Code | Description |
|---------|-----------|-------------|
| Background Dark | `#1a1a1a` | Deep black |
| Background Mid | `#2d2d2d` | Dark gray |
| Background Light | `#d4af37` | Light golden |
| Primary Blue | `#4070f4` | Card header, icons, text |
| Subscribe Button | `#667eea` → `#764ba2` | Purple gradient |
| Message Button | `#f093fb` → `#f5576c` | Pink gradient |
| Instagram | `#fb0054` | Pink |
| GitHub | `#333333` | Dark gray |
| LinkedIn | `#0077b5` | Blue |
| Discord | `#5865f2` | Blurple |

---

## 🔧 Common Issues & Solutions

### Image Not Displaying
- Check that the image file name matches exactly (including extension)
- Ensure the image is in the same folder as `index.html`
- Try using a different image format (PNG instead of JPEG)

### Social Links Not Working
- Verify URLs are complete with `https://`
- Remove any extra spaces in URLs
- Check that `target="_blank"` is present to open in new tab

### Popup Not Showing
- Check browser console for JavaScript errors (F12)
- Ensure the popup div has `id="messagePopup"`
- Verify the `showMessage()` function is called correctly

### Buttons Look Different
- Clear browser cache (Ctrl+F5)
- Check that all CSS code is between `<style>` tags
- Verify no typos in class names

---

## 📱 Responsive Design

The card automatically adjusts to different screen sizes:
- **Desktop**: Full-width card with all features visible
- **Tablet**: Maintains design with adjusted spacing
- **Mobile**: Scales appropriately, maintains readability

To further customize responsiveness, add media queries:
```css
@media (max-width: 768px) {
    .Profile-card {
        max-width: 90%;
    }
}
```

---

## 🚀 Future Enhancements

Potential features to add:
- [ ] Dark mode toggle
- [ ] Animated background particles
- [ ] Live visitor counter
- [ ] Contact form integration
- [ ] QR code for easy sharing
- [ ] Download vCard functionality
- [ ] Multiple theme options
- [ ] Integration with social media APIs for live stats

---

## 📄 License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute as needed.

---

## 👤 Author

**Divyansh Kashiv**
- GitHub: [@Divyansh-Kashiv07](https://github.com/Divyansh-Kashiv07)
- Instagram: [@divyanshhh._.07](https://www.instagram.com/divyanshhh._.07)
- LinkedIn: [Phoenix XD](https://in.linkedin.com/in/phoenix-xd-4922b5332)

---

## 🙏 Acknowledgments

- [Boxicons](https://boxicons.com/) for the beautiful icon library
- [Google Fonts](https://fonts.google.com/) for the Poppins font family
- Inspiration from modern UI/UX design trends

---

## 📞 Support

If you encounter any issues or have questions:
1. Check the Common Issues section above
2. Open an issue on GitHub
3. Contact via social media links

---

## ⭐ Show Your Support

If you found this helpful, please give it a ⭐ on GitHub!

---

**Made with ❤️ by Divyansh Kashiv**
