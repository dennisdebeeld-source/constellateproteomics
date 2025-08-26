# Adding Your Team Photos

## 📸 **How to Add Your Own Team Photos**

### **Step 1: Prepare Your Images**
1. **Save your team photos** in common formats: `.jpg`, `.jpeg`, or `.png`
2. **Recommended size**: 300x300 pixels or larger (they'll be displayed as 120x120px)
3. **Keep file sizes reasonable**: Under 1MB each for faster loading

### **Step 2: File Naming Convention**
Name your files exactly as shown below:
- `sarah_chen.jpg` (or your CEO's name)
- `marcus_berg.jpg` (or your CTO's name)  
- `elena_rodriguez.jpg` (or your R&D head's name)
- `james_wilson.jpg` (or your engineering head's name)
- `priya_patel.jpg` (or your senior scientist's name)
- `alex_thompson.jpg` (or your business dev manager's name)

### **Step 3: Upload to Correct Location**
Place your image files in: `images/team/`

Your file structure should look like:
```
Constellate_site/
├── images/
│   └── team/
│       ├── sarah_chen.jpg
│       ├── marcus_berg.jpg
│       ├── elena_rodriguez.jpg
│       ├── james_wilson.jpg
│       ├── priya_patel.jpg
│       └── alex_thompson.jpg
├── index.html
├── team.html
└── styles.css
```

### **Step 4: Automatic Fallback**
- If an image fails to load, the molecular placeholder will automatically show
- No need to modify code - it's already set up!

### **Step 5: Customize Names (Optional)**
If you want to change the team member names:
1. Edit `team.html`
2. Update the `<h3>` tags with actual names
3. Update the file paths in the `src` attributes to match new filenames

## 🔧 **Alternative: Use Different Filenames**
If you prefer different filenames, simply update the `src` attributes in `team.html`:

Change:
```html
<img src="images/team/sarah_chen.jpg" alt="Dr. Sarah Chen" class="team-photo">
```

To:
```html
<img src="images/team/your_ceo_photo.jpg" alt="Dr. Your CEO Name" class="team-photo">
```

## ✅ **Ready to Deploy**
Once you add your photos, your website is ready for Netlify deployment with real team member photos!

