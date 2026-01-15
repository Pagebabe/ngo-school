# NGO School Website (GitHub Pages)

This repo hosts a simple fundraising + transparency website.

## Local preview
Open `docs/index.html` in your browser, or run:

```bash
python3 -m http.server 8080 --directory docs
```

Then visit: http://localhost:8080

## GitHub Pages
Enable in GitHub: Settings → Pages → Deploy from a branch → main → /docs

Your site will be live at: https://pagebabe.github.io/ngo-school/

## What's Included

- **index.html** - Main website (all sections on one page)
- **updates.html** - Monthly news & transparency reports
- **style.css** - Complete styling (dark theme, mobile-responsive)
- **assets/images/** - Folder for photos (you need to add these)

## To Do After Upload

### 1. Add Contact Details
In `index.html`, replace:
- `info@childrenshome-cambodia.org` → your real email
- `+855 XX XXX XXXX` → your real phone/WhatsApp
- `@username` → your real Telegram username

### 2. Upload Photos
Add 6 photos to `docs/assets/images/`:
- `school-building.jpg` - School exterior
- `classroom.jpg` - Children in class
- `students.jpg` - Group of students
- `director.jpg` - Portrait of Director Wei Ha
- `teachers.jpg` - Teachers at work
- `needs.jpg` - Current infrastructure needs

Use your phone - honest photos are better than professional ones.

### 3. Monthly Updates
Edit `updates.html` each month to add:
- What happened
- How much was donated
- What you spent money on
- Photos of progress

Just copy the commented template and fill it in.

## Optional Improvements

- Add Google Maps embed for school location
- Add social media links (Facebook, Instagram) when ready
- Upload NGO registration document as PDF
- Create photo gallery with more images

## Support

Questions? Issues? Contact the project team or open a GitHub issue.

---

**Built for**: Children's Home of Education, Siem Reap, Cambodia  
**Purpose**: Fundraising, transparency, volunteer recruitment  
**Tech**: Static HTML/CSS (no framework, fast loading, easy to maintain)
