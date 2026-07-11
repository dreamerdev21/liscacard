# LISCA Youth Convention - Personalized Flyer Generator

A simple web application that allows attendees to create personalized flyers for the King's Seeds LISCA Jalingo Annual Youth Convention.

## 🚀 CRITICAL - Setup Instructions

### **STEP 1: Add Your Flyer Image**

The website needs your actual flyer design as the background. You MUST do this:

1. Save your flyer design image as **`flyer-template.jpg`**
2. Put it in the same folder as `index.html`
3. The image must be named **exactly** `flyer-template.jpg`
4. Use a high-quality image (recommended: 720px x 1280px or similar portrait ratio)

**Without this step, the website won't work!**

### **STEP 2: Adjust Photo and Name Positions (if needed)**

The website overlays the user's photo and name on your flyer. If they don't line up perfectly:

1. Open `index.html` in a text editor
2. Find the CSS in the `<style>` section (around lines 15-35)
3. Adjust these values:

```css
.user-photo {
    top: 37%;          /* Move photo up/down - where the circular photo should be */
    width: 32%;        /* Make photo circle bigger/smaller */
}

.user-name {
    top: 60%;          /* Move name up/down - where "DAVID MALGWI" is */
    font-size: 5.5vw;  /* Make name text bigger/smaller */
}
```

**How to find the right values:**
- Look at your flyer image and estimate where the photo circle is (as percentage from top)
- Look where the name should appear (as percentage from top)
- Adjust the values and refresh your browser to see changes

## 📂 Files You Need

- `index.html` - The website (already created ✓)
- `flyer-template.jpg` - **YOUR FLYER IMAGE (you need to add this!)**
- `README.md` - Instructions (this file)

## 💻 Quick Start

### For You (Setup):
1. **Save your flyer design as `flyer-template.jpg`** and put it in the same folder
2. Open `index.html` in a browser to test
3. Upload a test photo and name to see if they line up correctly
4. If not aligned, adjust the CSS values (see STEP 2 above)
5. Once perfect, host it online and share the link!

### For Attendees (Using the website):
1. Visit the website
2. Click to upload their photo
3. Type their name
4. See the preview
5. Download as PNG or PDF
6. Share on social media!

## 🌐 Hosting Options

You can host this website for FREE on:

### Option 1: Netlify (Easiest - Drag & Drop)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the folder containing all files
3. Get your link instantly!

### Option 2: GitHub Pages (Free Forever)
1. Create a GitHub account
2. Create a new repository
3. Upload all files
4. Enable GitHub Pages in Settings
5. Your link will be: `https://yourusername.github.io/repository-name`

### Option 3: Vercel (Fast & Easy)
1. Go to [https://vercel.com](https://vercel.com)
2. Sign up and create new project
3. Upload your files
4. Get your link!

### Option 4: Local Testing
- Simply open `index.html` in your web browser
- Works offline, but you can't share it with others

## ✨ Features

- ✅ Photo upload with preview
- ✅ Name input with character limit
- ✅ Real-time flyer preview
- ✅ Download as high-quality PNG
- ✅ Download as PDF document
- ✅ Mobile-friendly responsive design
- ✅ Beautiful, modern UI
- ✅ No installation required
- ✅ Works offline after initial load

## 🔧 Technologies Used

- HTML5
- Tailwind CSS (for styling)
- Alpine.js (for interactivity)
- html2canvas (for PNG generation)
- jsPDF (for PDF generation)

## 📱 Browser Support

Works on all modern browsers:
- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## 💡 Tips

- Use square photos for best results
- Keep names under 20 characters for optimal display
- Download in PNG for social media (smaller file size)
- Download in PDF for printing or WhatsApp
- Test the website on mobile devices before sharing

## 🐛 Troubleshooting

**Photo/Name not positioned correctly?**
- Open `index.html` and adjust the `top` and `width` values in the CSS
- The photo position is controlled by `.user-photo` 
- The name position is controlled by `.user-name`
- Change the percentages until it matches your flyer design

**Background image not showing?**
- Make sure your flyer image is named exactly `flyer-template.jpg`
- Make sure it's in the same folder as `index.html`
- Try refreshing your browser (Ctrl+F5 or Cmd+Shift+R)

**Photo not showing in preview?**
- Make sure image is less than 5MB
- Use JPG or PNG format only

**Download not working?**
- Check browser permissions
- Try a different browser
- Make sure photo and name are both filled in

## 📞 Support

For questions or issues, contact your church tech team.

---

**God bless you! Enjoy the Annual Youth Convention! 🙏✨**
