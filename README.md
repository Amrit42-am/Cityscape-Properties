# Cityscape - Real Estate Website

A modern, responsive real estate website built with HTML and CSS, inspired by Rightmove.co.uk.

## 📁 Project Structure

```
real-estate-project/
├── index.html          # Homepage with featured properties
├── buy.html           # Property listings for sale
├── contact.html       # Contact page with form
├── css/
│   └── style.css      # Complete stylesheet
├── images/            # Property images folder
└── README.md         # This file
```

## 🚀 Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Multiple Pages**: Home, Buy, and Contact pages
- **Search Functionality**: Property search with filters
- **Property Cards**: Beautiful cards with images, prices, and details
- **Contact Form**: Professional contact form with validation
- **Statistics Section**: Company stats and achievements
- **Services Section**: Key services offered

## 🎨 Design Elements

- **Color Scheme**:
  - Primary: #1a1a2e (Dark Blue)
  - Accent: #00d4ff (Cyan)
  - Background: #f8f9fa (Light Gray)
  - White: #ffffff

- **Typography**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif

## 📸 Adding AI-Generated Property Images

To make your website look realistic, you need to add property images. Here are several options:

### Option 1: Free AI Image Generators
1. **Leonardo.ai** (https://leonardo.ai/)
   - Free tier available
   - Generate realistic property images
   - Prompts: "modern house exterior", "luxury apartment interior", "cottage with garden"

2. **Bing Image Creator** (https://www.bing.com/create)
   - Powered by DALL-E
   - Free to use
   - Generate property images with natural descriptions

3. **Craiyon** (https://www.craiyon.com/)
   - Completely free
   - No sign-up required
   - Good for property exteriors

### Option 2: Free Stock Photo Websites
1. **Unsplash** (https://unsplash.com/)
   - Search: "modern house", "apartment", "luxury villa"
   - Completely free, no attribution required

2. **Pexels** (https://www.pexels.com/)
   - Search: "real estate", "house exterior", "property"
   - Free for commercial use

3. **Pixabay** (https://pixabay.com/)
   - Search: "home", "property", "house"
   - Free images and videos

### Required Images

Save these images in the `images/` folder:

1. **property1.jpg** - Modern 3 bedroom house (recommended: 800x600px)
2. **property2.jpg** - Luxury 2 bedroom apartment (recommended: 800x600px)
3. **property3.jpg** - Charming 4 bedroom cottage (recommended: 800x600px)
4. **property4.jpg** - Contemporary 5 bedroom villa (recommended: 800x600px)
5. **property5.jpg** - Spacious 2 bedroom flat (recommended: 800x600px)
6. **property6.jpg** - Executive 4 bedroom detached (recommended: 800x600px)

### AI Image Generation Prompts

Use these prompts to generate appropriate images:

```
Property 1: "Modern contemporary 3 bedroom house with white exterior, large windows, driveway, professional real estate photography"

Property 2: "Luxury modern apartment building exterior, city center, glass facade, professional real estate photography"

Property 3: "Traditional English stone cottage, 4 bedrooms, countryside setting, garden, professional real estate photography"

Property 4: "Contemporary luxury villa with pool, seafront, modern architecture, professional real estate photography"

Property 5: "Modern apartment block, urban setting, balconies, professional real estate photography"

Property 6: "Executive detached house, double garage, landscaped garden, professional real estate photography"
```

## 🌐 Hero Background Image

The hero section uses an Unsplash image URL. This is already set up in the CSS:
```css
url('https://images.unsplash.com/photo-1564013799919-ab600027ffc6?w=1200')
```

This is a beautiful house image that loads directly from Unsplash. You can replace it with your own image by:
1. Downloading a house image
2. Saving it as `hero-bg.jpg` in the `images/` folder
3. Updating the CSS to: `url('../images/hero-bg.jpg')`

## 🛠️ How to Use

1. **Download the project**
   - Ensure all files are in the correct folder structure

2. **Add Images**
   - Generate or download 6 property images
   - Save them as property1.jpg through property6.jpg in the `images/` folder

3. **Open in Browser**
   - Double-click `index.html` to open in your default browser
   - Or right-click and "Open with" your preferred browser

4. **Test Navigation**
   - Click through all pages to ensure links work
   - Test the responsive design by resizing your browser

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Mobile/Tablet: ≤ 768px

## ✨ Key Features by Page

### Homepage (index.html)
- Hero section with search
- Featured properties grid (4 properties)
- Services section
- Statistics section
- Footer with quick links

### Buy Page (buy.html)
- Filter bar for property search
- Property listings grid (6 properties)
- Sort functionality
- Pagination controls

### Contact Page (contact.html)
- Contact information cards
- Contact form with validation
- Map placeholder section

## 🎓 Learning Outcomes

This project demonstrates:
- HTML5 semantic structure
- CSS Grid and Flexbox layouts
- Responsive web design
- Form creation and styling
- Modern CSS techniques (gradients, shadows, transitions)
- Clean and organized code structure

## 📝 Customization Tips

1. **Change Colors**: Update the color variables in `style.css`
2. **Add More Properties**: Copy property card HTML and update details
3. **Modify Layout**: Adjust grid columns in CSS
4. **Add Pages**: Create `rent.html` and `sold.html` following the same structure

## 🔗 Additional Pages to Complete

You can create these additional pages using the same structure:
- `rent.html` - Properties for rent (similar to buy.html)
- `sold.html` - Sold property prices
- `property-detail.html` - Individual property details

## 📄 Browser Compatibility

- Chrome ✓
- Firefox ✓
- Safari ✓
- Edge ✓

## 👨‍💻 Project Information

- **Theme**: Real Estate
- **Reference**: Rightmove.co.uk
- **Technologies**: HTML5, CSS3
- **Phase**: Phase 1 - Static Website
- **Date**: November 2024

## 📧 Support

For questions or issues with this project:
- Review the code comments
- Check browser console for errors
- Ensure all file paths are correct
- Verify images are in the correct folder

## 🎉 Next Steps (Phase 2)

Future enhancements could include:
- JavaScript for interactive features
- Property search functionality
- Image gallery/carousel
- Form submission handling
- Local storage for favorites
- Interactive maps integration

---

**Good luck with your project evaluation!** 🏆
