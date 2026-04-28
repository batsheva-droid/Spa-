# 🌸 Spa & Beauty Salon - Booking Website

Welcome to the Spa & Beauty Salon booking website! A beautiful, modern, and responsive website for booking appointments.

## 📋 Features

✨ **Elegant Design**
- Luxury spa aesthetic inspired by the original flyer
- Warm gold, bronze, and cream color palette
- Smooth animations and transitions

📱 **Fully Responsive**
- Mobile-first design
- Adapts perfectly to all screen sizes
- Touch-friendly interface

🎯 **Key Sections**
- **Home/Hero** - Eye-catching introduction with tagline "CLEAN. LIFE. LOVE."
- **Services** - Display of all services (Facials, Waxing, Tinting, Skincare, Education)
- **About** - Information about the salon
- **Booking Form** - Easy appointment scheduling
- **Contact** - Phone number and social media links

⚙️ **Interactive Features**
- Smooth scroll navigation
- Form validation
- Hover animations on service cards
- Scroll-triggered animations
- Phone number auto-formatting

## 📁 Files

- `index.html` - Main website structure
- `styles.css` - All styling and responsive design
- `script.js` - Interactive functionality and form handling

## 🚀 Getting Started

1. Clone or download the repository
2. Open `index.html` in your web browser
3. Customize as needed:
   - Update phone number in contact section
   - Add social media links
   - Modify colors in CSS variables
   - Add your own logo/images

## 🛠️ Customization

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-gold: #a89968;
    --primary-brown: #6b5344;
    --primary-bronze: #8b7355;
    --cream: #f5ede5;
    --light-beige: #e8ddd3;
}
```

### Update Contact Information
Edit the phone number and location in `index.html`:
```html
<p><i class="fas fa-phone"></i> YOUR-PHONE-NUMBER</p>
<p><i class="fas fa-map-marker-alt"></i> Your Location</p>
```

### Add Social Media Links
Update the social links in the contact section:
```html
<a href="https://facebook.com/yourpage" title="Facebook"><i class="fab fa-facebook"></i></a>
```

## 📧 Backend Integration

To make the booking form fully functional, you'll need to:

1. **Set up a backend service** to handle form submissions
2. **Connect to an email service** (SendGrid, Mailgun, etc.) for confirmations
3. **Integrate a calendar system** to manage availability
4. **Add payment processing** if needed

### Example: Using FormSubmit
You can use a free service like FormSubmit to handle emails:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="booking-form">
    <!-- form fields -->
</form>
```

## 📱 Social Media Links

Update these in the HTML:
- Facebook: `https://facebook.com/yourbusiness`
- Instagram: `https://instagram.com/yourbusiness`
- Email: `mailto:contact@example.com`

## 🎨 Design Inspiration

This website is designed to match the aesthetic of your spa flyer:
- Luxury spa feel
- Elegant typography
- Soft, calming colors
- Professional layout
- Easy-to-use booking interface

## 📝 License

This website is created for Spa & Beauty Salon. All rights reserved.

## 💬 Support

For any questions or modifications, feel free to reach out!

---

**Enjoy your new spa booking website! 🌸✨**
