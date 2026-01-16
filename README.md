# Dragon Manual of Berk

A Viking-themed web application for creating your own illustrated dragon compendium with archaic manuscript styling inspired by How to Train Your Dragon.

## Overview

This tool allows you to document dragons with detailed information and compile them into a professionally formatted PDF that looks like an ancient Viking manuscript. Each dragon entry includes classification, physical descriptions, behavioral observations, and known weaknesses - all presented on aged parchment with medieval typography.

## Features

- **Viking/Medieval Aesthetic**: Authentic old-world design with parchment backgrounds, medieval fonts, and hand-drawn styling
- **7 Dragon Classes**: Based on HTTYD classification system
  - Stoker Class (Red)
  - Boulder Class (Brown)
  - Tracker Class (Olive/Yellow-Green)
  - Sharp Class (Green)
  - Tidal Class (Blue)
  - Mystery Class (Purple)
  - Strike Class (Magenta)
- **Comprehensive Dragon Profiles**: Capture all essential information about each dragon
- **PDF Compilation**: Generate a printable manual with archaic manuscript styling
- **Live Preview**: See your dragons listed as you add them
- **Easy Management**: Add or remove dragons before generating the final manual

## How to Use

### Step 1: Open the Website
Simply open `dragon_book.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

### Step 2: Add Dragons
Fill out the form with information about each dragon:

**Required Fields:**
- **Dragon Name**: The name of the dragon species
- **Dragon Class**: Select from 7 HTTYD classes
- **Size Category**: Tiny, Small, Medium, Large, Huge, or Colossal
- **Habitat**: Where the dragon dwells (Mountains, Forests, Caves, etc.)
- **Diet**: Carnivore, Herbivore, Omnivore, or Specialized
- **Danger Level**: From Harmless to Legendary Threat
- **Known Weaknesses**: Any vulnerabilities observed
- **Physical Description**: Detailed appearance notes
- **Behavioral Traits**: How the dragon acts in the wild

**Dynamic Fields:**
- If you select "Other" for Habitat, a text box appears for custom input
- If you select "Specialized" for Diet, a text box appears for details

### Step 3: Add to Your Collection
Click **"Add Dragon to Manual"** to save the dragon to your temporary collection. The dragon will appear in the list at the top of the page.

### Step 4: Manage Your Dragons
- View all added dragons in the list
- Click **"Remove"** next to any dragon to delete it from your collection
- Add as many dragons as you want

### Step 5: Generate Your Manual
When you're finished adding all dragons, click **"Generate PDF Manual"**. The website will:
1. Compile all dragons into a single PDF
2. Format each dragon on its own page with archaic manuscript styling
3. Add color-coded class badges
4. Download the PDF to your computer as `Dragon_Manual_of_Berk.pdf`

## PDF Format

Each dragon page includes:
- **Aged parchment background** (#D4C5A9)
- **Dragon name** as title with hand-drawn wavy underline
- **Color-coded class badge** with class initial
- **Class name** in italics
- **Stats section** with slightly irregular positioning for handwritten feel:
  - Size
  - Habitat
  - Diet
  - Danger Level
  - Known Weaknesses
- **Hand-drawn divider line**
- **"Appearance as witnessed:"** section with physical description
- **"Behavior observed in the wild:"** section with behavioral notes
- **Times Roman font family** for authentic manuscript appearance

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (ES6+)
- jsPDF library for PDF generation

### Fonts
- **MedievalSharp**: Main title font
- **Cinzel**: Headers and labels (serif with historical character)
- **IM Fell English**: Body text (classic manuscript font)
- **Times Roman**: Used in PDF for authentic archaic appearance

### Browser Compatibility
Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

### File Size
- Single HTML file: ~20KB
- No external dependencies except jsPDF (loaded from CDN)
- PDF size depends on content (typically 50-200KB per dragon)

## Important Notes

⚠️ **Data is NOT permanently saved!**
- Dragons are stored temporarily in browser memory only
- Closing the browser or refreshing the page will clear all entries
- Always generate and download your PDF before closing the page
- If you need to save your work, generate the PDF periodically

## Tips for Best Results

1. **Be Descriptive**: The more detailed your descriptions, the better your manual will look
2. **Use Archaic Language**: Write descriptions in old-timey Viking style for authenticity
   - Examples: "Most perilous beast", "Dwells in deep forests", "Take heed"
3. **Review Before PDF**: Check your dragon list for typos before generating
4. **Save Multiple Versions**: Generate PDFs as you go if making a large manual
5. **Print Quality**: The PDF is designed for standard letter-size printing (8.5" × 11")

## Example Dragon Entry

```
Name: Deadly Nadder
Class: Tracker Class
Size: Large
Habitat: Forests & Mountains
Diet: Omnivore - fish and vegetation
Danger: Extremely Dangerous
Weakness: Blind spot directly on snout

Physical Description:
This creature bears scales of vivid blue across its entire form, crowned 
with spikes of brilliant yellow upon head and tail. Most fearsome are the 
razor spines along its back and tail, which it may launch forth as deadly 
arrows...

Behavioral Traits:
Most territorial of beasts! This dragon defends its domain with fierce 
aggression against all who dare trespass. Strange vanity marks this 
creature - many hours spent grooming its pristine scales...
```

## Troubleshooting

**Problem**: PDF doesn't generate
- **Solution**: Make sure you've added at least one dragon before clicking "Generate PDF Manual"

**Problem**: Text appears cut off in PDF
- **Solution**: Keep descriptions reasonable in length (under 500 words per section)

**Problem**: Class badge color doesn't match
- **Solution**: The system uses predefined colors for each class - this is intentional for consistency

**Problem**: Lost all my dragons after refresh
- **Solution**: This is expected behavior - always generate your PDF before closing/refreshing

## Future Enhancements (Not Currently Implemented)

Potential features for future versions:
- Browser localStorage to save dragons between sessions
- Image upload for dragon illustrations
- Export/import dragon data as JSON
- Multiple page templates
- Custom class creation
- Rearrange dragon order before PDF generation

## Credits

Inspired by the "How to Train Your Dragon" franchise and the Book of Dragons from the series.

Dragon classes and classification system based on HTTYD lore.

## License

Free to use for personal projects. Not affiliated with DreamWorks or the HTTYD franchise.

---

**Created for personal dragon documentation and creative writing projects.**

*"This is Berk. It's been here for seven generations, but every single building is new..."*
