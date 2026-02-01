# 30-Day Seller Advantage Program - HTML Funnel

## Overview

This package contains 4 professionally designed HTML pages for your complete sales funnel. These pages are ready to upload to ClickFunnels or host on your own domain.

---

## Files Included

### HTML Pages:
1. **page1-lead-magnet.html** - Lead magnet opt-in page (2026 Seller's Playbook)
2. **page2-thank-you.html** - Thank you page with video sales letter
3. **page3-application.html** - Multi-step application form (5 steps)
4. **page4-calendar.html** - Calendar booking confirmation page

### Assets:
- **images/** - All your photos and logos
  - BryanSunspot.jpg
  - maxandIheadshot.jpg
  - RyanandISMALL.jpg
  - serhantlogo.png
  - owningmanhattan.jpg

---

## How to Upload to ClickFunnels

### Method 1: Custom HTML/CSS (Recommended)

1. **Create a New Funnel in ClickFunnels**
   - Log in to ClickFunnels
   - Click "Funnels" → "Create New Funnel"
   - Select "Custom Funnel"

2. **Add Pages**
   - Add 4 steps to your funnel:
     - Step 1: Opt-In Page
     - Step 2: Thank You Page
     - Step 3: Application Page
     - Step 4: Confirmation Page

3. **Upload HTML for Each Page**
   - Click on a page → "Edit Page"
   - Click "Settings" (gear icon) → "Tracking Code"
   - Paste the entire HTML code from each file into the "Head Tracking Code" section
   - OR use the "Custom HTML" element and paste the body content

4. **Upload Images**
   - In ClickFunnels, go to "Settings" → "File Manager"
   - Upload all images from the `images/` folder
   - Copy the URLs for each image
   - Replace the image paths in the HTML:
     - Find: `images/BryanSunspot.jpg`
     - Replace with: `https://your-clickfunnels-url.com/BryanSunspot.jpg`

5. **Connect Pages**
   - Update form actions to point to the next page in your funnel
   - Page 1 form → Page 2
   - Page 2 CTA → Page 3
   - Page 3 form → Page 4

---

### Method 2: Host on Your Own Domain (Alternative)

If you prefer to host these pages independently:

1. **Upload to Your Web Host**
   - Upload all files (HTML + images folder) to your web server via FTP
   - Ensure the folder structure remains intact

2. **Link from ClickFunnels**
   - In ClickFunnels, create redirect pages that point to your hosted URLs
   - OR embed these pages using iframes

---

## Customization Required

### 1. Video Embed (Page 2)
Replace the video placeholder with your actual video:

```html
<!-- Replace this section in page2-thank-you.html -->
<div class="video-wrapper">
    <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
</div>
```

**Video Script Included:** See the copy documents for the full 3-minute video script.

---

### 2. Calendar Integration (Page 4)
Replace the calendar placeholder with your Calendly embed:

```html
<!-- Replace this section in page4-calendar.html -->
<div class="calendly-inline-widget" 
     data-url="https://calendly.com/yourname/30min" 
     style="min-width:320px;height:630px;">
</div>
<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js"></script>
```

**Alternative Calendar Tools:**
- Acuity Scheduling
- Calendly
- ScheduleOnce
- HubSpot Meetings

---

### 3. Form Integration
The forms currently use basic HTML. To capture leads, integrate with:

**Option A: ClickFunnels Native Forms**
- Use ClickFunnels' form builder
- Copy the field names from the HTML
- Style to match the design

**Option B: Third-Party Integration**
- ActiveCampaign
- Mailchimp
- HubSpot
- ConvertKit

Update the form `action` attribute to point to your CRM or email service.

---

### 4. Email Automation
Set up automated emails for:

**After Page 1 (Opt-In):**
- Subject: "Your 2026 Seller's Playbook is Here"
- Attach the PDF playbook
- Include link to Page 2 (Thank You + VSL)

**After Page 3 (Application):**
- Subject: "Application Received - Next Steps"
- Confirm we'll reach out in 24 hours
- Include link to Page 4 (Calendar Booking)

**After Page 4 (Calendar Booking):**
- Subject: "Your Strategy Session with Bryan May is Confirmed"
- Include date, time, Zoom link
- Reminder email 24 hours before

---

## Design Specifications

### Colors:
- **Navy:** #000033
- **Gold:** #C5A059
- **White:** #FFFFFF
- **Gray:** #f8f9fa
- **Green (Success):** #28a745

### Fonts:
- **Headlines:** Playfair Display (Google Fonts)
- **Body:** Lato (Google Fonts)

### Responsive:
- All pages are fully mobile-responsive
- Breakpoint: 768px

---

## Testing Checklist

Before launching, test:

- [ ] All forms submit correctly
- [ ] Images load properly
- [ ] Video plays on Page 2
- [ ] Calendar booking works on Page 4
- [ ] Mobile responsiveness on all pages
- [ ] Email automation triggers
- [ ] Links between pages work
- [ ] Contact information is correct (phone, email)

---

## Support & Customization

If you need help with:
- Custom design changes
- Integration with your CRM
- Advanced tracking setup (Facebook Pixel, Google Analytics)
- A/B testing variations

Contact your web developer or ClickFunnels support.

---

## Next Steps

1. **Create the Lead Magnet PDF**
   - Use the content from your uploaded PDFs
   - Design a professional PDF (Canva, InDesign, or hire a designer)
   - Upload to ClickFunnels or your web host

2. **Record the Video**
   - Use the script provided in the copy documents
   - Record with good lighting and audio
   - Upload to YouTube or Vimeo
   - Embed on Page 2

3. **Set Up Email Sequences**
   - Write 5-7 follow-up emails
   - Nurture leads who don't apply immediately
   - Use the copy documents as a starting point

4. **Launch & Test**
   - Run traffic to Page 1
   - Monitor conversion rates
   - A/B test headlines, CTAs, and images

---

## Conversion Optimization Tips

### Page 1 (Lead Magnet):
- **Target Conversion Rate:** 30-40%
- Test different headlines
- Try exit-intent popup with bonus offer
- Add social proof (testimonial count)

### Page 2 (Thank You + VSL):
- **Target Conversion Rate:** 50-60% (watch video)
- Keep video under 4 minutes
- Add captions for mobile viewers
- Strong CTA at the end

### Page 3 (Application):
- **Target Conversion Rate:** 15-25%
- Keep form fields minimal
- Use progress bar to show completion
- Add testimonials in sidebar

### Page 4 (Calendar Booking):
- **Target Conversion Rate:** 60-70%
- Offer multiple time slots
- Send SMS reminders
- Reduce no-shows with confirmation emails

---

## Legal Disclaimer

Make sure to add:
- Privacy Policy link
- Terms of Service link
- CAN-SPAM compliance (unsubscribe link in emails)
- GDPR compliance (if targeting EU)

---

## Questions?

For technical support or customization requests, contact your web developer or reach out to the Manus team.

**Good luck with your funnel launch!**

---

© 2026 Serhant Real Estate. All Rights Reserved.
