# 📖 Birthday Wish - Complete Customization Guide
Main html code is added to index.html . So you will find it there.

This guide explains **everything** about customizing your birthday website with detailed examples and step-by-step instructions.

---

## 📚 Table of Contents

1. [Project Overview](#project-overview)
2. [Folder Structure](#folder-structure)
3. [How to Run](#how-to-run)
4. [Customize Page 1 - Greeting](#customize-page-1---greeting)
5. [Customize Page 2 - Photos](#customize-page-2---photos)
6. [Customize Page 3 - Message](#customize-page-3---message)
7. [Add Video](#add-video)
8. [Add Music](#add-music)
9. [File Naming Rules](#file-naming-rules)
10. [Troubleshooting](#troubleshooting)
11. [Advanced Tips](#advanced-tips)

---

## Project Overview

### What This Project Is

Birthday Wish is a **3-page interactive website** designed to celebrate someone's birthday with:
- Animated greeting page
- Photo gallery
- Video and personalized message
- Background music
- Responsive design (works on all devices)

### What Each Page Does

**Page 1: Greeting**
- Shows animated birthday greeting
- Has comic effects and confetti
- Button to go to Page 2

**Page 2: Photo Gallery**
- Displays 2-5 of your photos
- Each photo has a custom caption
- Animated photo pop-in effects
- Navigation buttons

**Page 3: Video & Message**
- Plays your birthday video
- Shows your personalized birthday message
- Text appears with fade-in animation
- Music pauses when video plays

---

## Folder Structure

### Complete Folder Layout

```
birthday-wish/
├── birthday-wish.html          # Main HTML file (DO NOT rename)
├── page2pic1.jpg               # Photo 1 (required - JPG/PNG)
├── page2pic2.jpg               # Photo 2 (required - JPG/PNG)
├── page2pic3.jpg               # Photo 3 (optional - JPG/PNG)
├── page2pic4.jpg               # Photo 4 (optional - JPG/PNG)
├── page2pic5.jpg               # Photo 5 (optional - JPG/PNG)
├── video.mp4                   # Birthday video (optional - MP4)
├── song.mp3                    # Background music (optional - MP3)
├── README.md                   # Quick start guide
└── GUIDELINE.md                # This file
```

### File Requirements

| File | Required? | Format | Min Size | Max Size | Notes |
|------|-----------|--------|----------|----------|-------|
| birthday-wish.html | Yes | HTML | - | - | DO NOT rename |
| page2pic1.jpg | Yes | JPG/PNG | 400×400px | 5MB | For Page 2 |
| page2pic2.jpg | Yes | JPG/PNG | 400×400px | 5MB | For Page 2 |
| page2pic3-5.jpg | Optional | JPG/PNG | 400×400px | 5MB | Show if added |
| video.mp4 | Optional | MP4 | 720p | 50MB | For Page 3 |
| song.mp3 | Optional | MP3 | - | 10MB | For Pages 1-2 |

---

## How to Run

### On Your Computer

1. **Download the repository**
   - Clone: `git clone https://github.com/YOUR-USERNAME/birthday-wish.git`
   - Or download ZIP from GitHub

2. **Open the folder**
   - Find the `birthday-wish` folder you downloaded

3. **Run the website**
   - Double-click `birthday-wish.html`
   - It opens in your default browser

4. **Done!**
   - Website is now running locally

### Features Available Immediately

- ✅ All animations and effects
- ✅ All 3 pages and navigation
- ✅ Default sample text and images
- ✅ No installation needed
- ✅ Works offline

---

## Customize Page 1 - Greeting

### What Page 1 Is

The first page shows:
- A large animated greeting
- Emoji line (🎂🎈🎉🥳🎁)
- "Want to see a surprise?" message
- NEXT button

### How to Edit the Greeting

#### Step 1: Open the HTML File

1. Right-click **`birthday-wish.html`**
2. Select **Open with**
3. Choose **Notepad** (Windows), **TextEdit** (Mac), or **VS Code** (any OS)

#### Step 2: Find the Heading

Press **Ctrl+F** (or **Cmd+F** on Mac) to open Find dialog.

Search for: `Happy Birthday`

You'll find this line (around line 497):
```html
<h1>Happy Birthday<br>Someone</h1>
```

#### Step 3: Edit the Text

The format is:
- Line 1: `Happy Birthday` (or your occasion)
- `<br>` = line break
- Line 2: `Someone` (replace with recipient's name)

#### Step 4: Save and Test

1. Save file: **Ctrl+S** (or **Cmd+S**)
2. Refresh browser: **Ctrl+Shift+R** (hard refresh)
3. Changes appear instantly

### Examples

**Example 1: Simple Name Change**
```html
<!-- Before -->
<h1>Happy Birthday<br>Someone</h1>

<!-- After -->
<h1>Happy Birthday<br>Shikriti</h1>
```
Result:
```
Happy Birthday
Shikriti
```

**Example 2: With Age**
```html
<h1>Happy 25th Birthday<br>Shikriti</h1>
```
Result:
```
Happy 25th Birthday
Shikriti
```

**Example 3: Different Occasion**
```html
<h1>Happy Anniversary<br>Sarah & Mike</h1>
```
Result:
```
Happy Anniversary
Sarah & Mike
```

**Example 4: With Emoji**
```html
<h1>🎉 Happy Birthday 🎉<br>Shikriti</h1>
```
Result:
```
🎉 Happy Birthday 🎉
Shikriti
```

### Important Notes

- Keep the `<h1>` and `</h1>` tags
- Use `<br>` for line breaks
- You can use emojis: 🎂🎈🎉🥳🎁❤️💕
- Don't use special characters like `< > { }`

---

## Customize Page 2 - Photos

### What Page 2 Is

The second page shows:
- Photo gallery (2-5 photos)
- Each photo has a caption
- Photos appear with pop-in animation
- Navigation buttons

### Step 1: Prepare Your Photos

**Requirements:**
- Format: JPG or PNG
- Size: At least 400×400 pixels
- Best: Square images (same width and height)
- File size: Under 5MB each

**Recommended Tools:**
- Crop/Resize: [Pixlr.com](https://pixlr.com) or [Canva.com](https://canva.com)
- Compress: [TinyPNG.com](https://tinypng.com)

### Step 2: Rename Photos EXACTLY

This is **CRITICAL**. Names must be exact (all lowercase, no spaces):

```
page2pic1.jpg
page2pic2.jpg
page2pic3.jpg (if using 3 photos)
page2pic4.jpg (if using 4 photos)
page2pic5.jpg (if using 5 photos)
```

**Wrong names that WON'T work:**
- ❌ `Photo1.jpg` (capital P)
- ❌ `photo 1.jpg` (space in name)
- ❌ `pic1.jpg` (wrong name)
- ❌ `page2pic1.JPG` (capital extension)
- ❌ `page2pic1.jpeg` (wrong extension)

### Step 3: Put Photos in Folder

1. Cut/copy your renamed photos
2. Paste them into the `birthday-wish` folder
3. They should be in the **same folder** as `birthday-wish.html`

Folder should look like:
```
birthday-wish/
├── birthday-wish.html
├── page2pic1.jpg    ← Your photo here
├── page2pic2.jpg    ← Your photo here
├── page2pic3.jpg    ← Your photo here (optional)
└── song.mp3
```

### Step 4: Edit Photo Captions

#### Find the Captions

Open `birthday-wish.html` with Notepad.

Press **Ctrl+F** and search: `Text 1`

You'll find (around line 525):
```html
<p class="photo-label">Text 1</p>
<img src="page2pic1.jpg" alt="Photo 1" class="photo-img">
```

#### Edit Captions

Change `Text 1`, `Text 2`, etc. to your custom captions.

**Example:**
```html
<!-- Before -->
<p class="photo-label">Text 1</p>

<!-- After -->
<p class="photo-label">Our First Coffee ☕</p>
```

### Step 5: Show 2, 3, 4, or 5 Photos

**Default:** Shows 2 photos (Photo 1 and Photo 2)

**To show 3, 4, or 5 photos:**

Search for: `<!-- Photo 3 (Optional`

You'll see commented photos:
```html
<!-- <div class="photo-card">
    <p class="photo-label">Text 3</p>
    <img src="page2pic3.jpg" alt="Photo 3" class="photo-img">
</div> -->
```

**To uncomment (show the photo):**

Remove `<!-- ` at the start and ` -->` at the end:
```html
<div class="photo-card">
    <p class="photo-label">Text 3</p>
    <img src="page2pic3.jpg" alt="Photo 3" class="photo-img">
</div>
```

### Photo Caption Examples

```html
<!-- One line -->
<p class="photo-label">Our First Meeting 💕</p>

<!-- Two lines (use <br> for break) -->
<p class="photo-label">Beach Day 🏖️<br>Summer 2024</p>

<!-- With emoji -->
<p class="photo-label">Laughing Together 😂</p>

<!-- Simple text -->
<p class="photo-label">Best Friends Forever</p>

<!-- Descriptive -->
<p class="photo-label">Remember this crazy moment? 🤪</p>
```

### Photo Tips

1. **Crop to square**: Photos show as 1:1 aspect ratio (square)
2. **Use consistent style**: Try to keep all photos in similar tone
3. **High quality**: Use good resolution photos for better appearance
4. **Test first**: Make sure photos look good before sharing

---

## Customize Page 3 - Message

### What Page 3 Is

The third page shows:
- Your birthday video (optional)
- A heading (e.g., "Happy Birthday, Shikriti!")
- Multiple paragraphs of birthday message
- Each paragraph appears with fade-in animation

### Step 1: Edit the Page 3 Heading

#### Find the Heading

Press **Ctrl+F** and search: `wish-para title`

Around line 575, you'll find:
```html
<p class="wish-para title">Happy Birthday, Someone! ❤️🎂</p>
```

#### Edit the Heading

Replace `Someone` with the recipient's name:

**Examples:**
```html
<!-- Simple -->
<p class="wish-para title">Happy Birthday, Shikriti! ❤️🎂</p>

<!-- With emoji -->
<p class="wish-para title">🎉 Happy Birthday, Sarah! 🎂</p>

<!-- Casual -->
<p class="wish-para title">Happy Birthday to the Best Friend! 💝</p>

<!-- Special -->
<p class="wish-para title">To My Amazing Sister - Happy Birthday! 👯</p>
```

### Step 2: Edit the Birthday Message

#### Find the Message Paragraphs

Search for: `<p class="wish-para">Wishing`

You'll find multiple paragraphs (around line 578+):
```html
<p class="wish-para">Wishing the happiest birthday to...</p>

<p class="wish-para">You're honestly such a funny...</p>

<p class="wish-para">But jokes apart, your childish...</p>

(more paragraphs...)
```

#### How the Message Works

- Each `<p class="wish-para">...</p>` is one paragraph
- Paragraphs appear one after another with fade-in animation
- You can have as many paragraphs as you want
- Don't remove the `class="wish-para"` part

#### Edit the Message

Replace the entire message with your custom text.

**Example 1: Short Message (3 paragraphs)**

Replace all paragraphs with:
```html
<p class="wish-para">Happy Birthday to the most amazing friend!</p>

<p class="wish-para">Shikriti, you bring so much joy and laughter into my life. Your kindness and humor make you truly special.</p>

<p class="wish-para">May this year bring you happiness, success, and all the love you deserve. With all my love! 🎂❤️</p>
```

**Example 2: Personal Message (5 paragraphs)**

```html
<p class="wish-para">Dear Shikriti,</p>

<p class="wish-para">Today is your special day, and I wanted to take a moment to tell you how important you are to me.</p>

<p class="wish-para">You have the most infectious laugh and the kindest heart. Every moment with you is filled with joy and laughter.</p>

<p class="wish-para">Thank you for being an incredible friend. Your support and love have helped me through so much.</p>

<p class="wish-para">I hope this year brings you happiness, success, and all the dreams you deserve. Happy Birthday! 🎂❤️</p>
```

**Example 3: Heartfelt Message (6 paragraphs)**

```html
<p class="wish-para">Happy Birthday to the most wonderful person I know!</p>

<p class="wish-para">You are kind, funny, and genuinely one of the best people in my life.</p>

<p class="wish-para">I love how you always know how to make me laugh, even on the hardest days.</p>

<p class="wish-para">Your dreams are important, and I believe you can achieve anything you set your mind to.</p>

<p class="wish-para">Thank you for being such an amazing friend. I am so grateful to have you in my life.</p>

<p class="wish-para">Wishing you a year filled with love, laughter, and success. You deserve all the happiness in the world! 🎉❤️🎂</p>
```

### Message Tips

- ✅ Each paragraph should be 1-3 sentences
- ✅ Use emojis: 🎂❤️😂🎉🎁💕
- ✅ Keep text inside `>` and `</p>` tags
- ✅ Don't remove `class="wish-para"`
- ✅ Proofread before saving

---

## Add Video

### What You Need

- **Format**: MP4 (most compatible)
- **Resolution**: 720p (1280×720) or higher
- **File Size**: Under 50MB
- **Duration**: 1-5 minutes ideal

### Step 1: Prepare Your Video

If your video is not in MP4 format, convert it using:
- [HandBrake](https://handbrake.fr/) (free, desktop)
- [CloudConvert](https://cloudconvert.com/) (free, online)

To compress if too large:
- Use [HandBrake](https://handbrake.fr/) with lower quality/resolution
- Reduce duration (trim unnecessary parts)

### Step 2: Rename the Video

**IMPORTANT**: Rename to exactly: `video.mp4` (all lowercase)

Wrong names:
- ❌ `Video.mp4` (capital V)
- ❌ `birthday.mp4` (wrong name)
- ❌ `video.MP4` (capital extension)

### Step 3: Put in Folder

Place `video.mp4` in the **same folder** as `birthday-wish.html`

Folder:
```
birthday-wish/
├── birthday-wish.html
├── page2pic1.jpg
├── page2pic2.jpg
├── video.mp4        ← Here
└── song.mp3
```

### Step 4: Test

1. Refresh browser: **Ctrl+Shift+R**
2. Go to Page 3
3. Video should appear
4. Click play to test

### Video Behavior

- User can play, pause, and control volume
- Music automatically pauses when video plays
- Music resumes when video is paused or finished
- User can see video progress bar and duration

---

## Add Music

### What You Need

- **Format**: MP3
- **Duration**: 2-5 minutes (ideal for looping)
- **File Size**: Under 10MB
- **Bitrate**: 128 kbps or higher

### Step 1: Get Your Music

Find royalty-free music:
- [Pixabay Music](https://pixabay.com/music/) (free)
- [Bensound](https://www.bensound.com) (free)
- [YouTube Audio Library](https://www.youtube.com/audiolibrary) (free)
- Your own music files

### Step 2: Convert to MP3 (if needed)

If your music is not MP3:
- [Online-Convert.com](https://online-convert.com/) (free, online)
- [Audacity](https://audacityteam.org/) (free, desktop)

To trim or edit:
- [Audacity](https://audacityteam.org/) (free, desktop)

### Step 3: Rename the Music

**IMPORTANT**: Rename to exactly: `song.mp3` (all lowercase)

Wrong names:
- ❌ `Song.mp3` (capital S)
- ❌ `music.mp3` (wrong name)
- ❌ `song.MP3` (capital extension)

### Step 4: Put in Folder

Place `song.mp3` in the **same folder** as `birthday-wish.html`

Folder:
```
birthday-wish/
├── birthday-wish.html
├── page2pic1.jpg
├── video.mp4
└── song.mp3         ← Here
```

### Step 5: Test

1. Refresh browser: **Ctrl+Shift+R**
2. Go to Page 1
3. Click 🔇 button in top-right
4. Music should start playing

### Music Behavior

- Plays on Pages 1 & 2 only
- Has play/pause button (🔇/🔊) in top-right
- Volume is set to 50% by default
- Continues playing while navigating between pages
- Automatically pauses on Page 3 when video plays
- Resumes when video is paused or finished
- **Note**: Browsers sometimes block autoplay, user may need to click button

---

## File Naming Rules

### Critical Rules

**ALL FILENAMES MUST BE:**
- ✅ All LOWERCASE letters
- ✅ NO SPACES
- ✅ EXACT names

### File Naming Reference

| File Type | Correct Name | Wrong ❌ | Why Wrong |
|-----------|---|---|---|
| Photo 1 | `page2pic1.jpg` | `Photo1.jpg` | Capital letters |
| Photo 1 | `page2pic1.jpg` | `page2pic1.JPG` | Capital extension |
| Photo 1 | `page2pic1.jpg` | `photo1.jpg` | Wrong name |
| Photo 2 | `page2pic2.jpg` | `photo 2.jpg` | Space in name |
| Photo 3 | `page2pic3.jpg` | `3.jpg` | Wrong name |
| Video | `video.mp4` | `Video.mp4` | Capital letter |
| Video | `video.mp4` | `birthday.mp4` | Wrong name |
| Music | `song.mp3` | `Song.mp3` | Capital letter |
| Music | `song.mp3` | `music.mp3` | Wrong name |
| HTML | `birthday-wish.html` | DO NOT RENAME | Breaks website |

### How to Rename Files

**On Windows:**
1. Right-click file
2. Select **Rename**
3. Type new name
4. Press Enter

**On Mac:**
1. Right-click file
2. Select **Rename**
3. Type new name
4. Press Enter

---

## Troubleshooting

### Photos Not Showing

**Problem**: Photos don't appear on Page 2

**Solutions:**

1. **Check filenames**
   - Must be: `page2pic1.jpg`, `page2pic2.jpg`, etc.
   - Must be all lowercase
   - No spaces in names

2. **Check file location**
   - Files must be in SAME folder as `birthday-wish.html`
   - Not in a subfolder

3. **Check format**
   - Must be JPG or PNG
   - Not JPG.jpg or photo.jpeg

4. **Hard refresh browser**
   - Press **Ctrl+Shift+R** (Windows)
   - Press **Cmd+Shift+R** (Mac)

5. **Check photo was uncommented**
   - If using Photo 3+, make sure `<!-- -->` was removed

**Still not working?**
- Close browser completely
- Reopen HTML file
- Try different browser

### Video Not Playing

**Problem**: Video doesn't appear on Page 3

**Solutions:**

1. **Check filename**
   - Must be exactly: `video.mp4`
   - All lowercase

2. **Check file location**
   - Must be in same folder as HTML

3. **Check format**
   - Must be MP4
   - Not video.mp4.mp4

4. **Try converting**
   - Use [HandBrake](https://handbrake.fr/)
   - Use [CloudConvert](https://cloudconvert.com/)

5. **Check file size**
   - Under 50MB?
   - Too large? Compress it

6. **Hard refresh**
   - **Ctrl+Shift+R**

### Music Not Playing

**Problem**: No sound on Pages 1 & 2

**Solutions:**

1. **Check filename**
   - Must be exactly: `song.mp3`
   - All lowercase

2. **Check file location**
   - Must be in same folder as HTML

3. **Check browser autoplay**
   - Browsers often block autoplay
   - Click 🔇 button to start manually

4. **Check file format**
   - Must be MP3
   - Not song.mp3.mp3

5. **Try converting**
   - Use [Online-Convert.com](https://online-convert.com/)
   - Use [Audacity](https://audacityteam.org/)

6. **Hard refresh**
   - **Ctrl+Shift+R**

### Changes Not Showing

**Problem**: Edited text but changes don't appear

**Solutions:**

1. **Save the file**
   - **Ctrl+S** (Windows)
   - **Cmd+S** (Mac)

2. **Hard refresh browser**
   - **Ctrl+Shift+R** (Windows)
   - **Cmd+Shift+R** (Mac)

3. **Clear browser cache**
   - **Ctrl+Shift+Delete**
   - Or use your browser's settings

4. **Close and reopen**
   - Close the browser
   - Close the text editor
   - Reopen both

### Text Looks Broken

**Problem**: HTML shows errors or weird characters

**Solutions:**

1. **Check opening/closing tags**
   - Every `<p>` needs `</p>`
   - Don't delete or modify tags

2. **Don't remove class attribute**
   - Keep `class="wish-para"`
   - Don't change it to anything else

3. **Check for special characters**
   - Avoid `< > { } [ ]` in text
   - Use emojis instead: 🎉❤️😂

4. **Undo your changes**
   - **Ctrl+Z** to undo
   - Try again carefully

---

## Advanced Tips

### Browser Developer Tools

To debug issues:

1. Press **F12** in browser
2. Go to **Console** tab
3. Look for error messages
4. This shows if file paths are wrong

### Use Different Browser

Test on:
- Chrome
- Firefox
- Safari
- Edge

Different browsers may handle files differently.

### Backup Your Work

Before making changes:
1. Copy the entire folder
2. Name it with date: `birthday-wish-backup-2024-11-05`
3. Keep it safe
4. You can always restore if something breaks

### Optimize File Sizes

**Photos:**
- Use [TinyPNG.com](https://tinypng.com/) to compress
- Reduces file size by 50-70%
- No visible quality loss

**Video:**
- Use [HandBrake](https://handbrake.fr/)
- Set to 720p resolution
- Reduces file by 50-80%

**Music:**
- Use [Audacity](https://audacityteam.org/)
- Lower bitrate (128 kbps is fine)
- Trim unused parts

### CSS Customization

If you know CSS, you can change:
- Colors (search for hex codes like `#ff6a00`)
- Fonts (search for `font-family`)
- Animations (search for `@keyframes`)

### Add More Photos Beyond 5

To add 6+ photos:

1. Copy this code:
```html
<div class="photo-card">
    <p class="photo-label">Your Caption Here</p>
    <img src="page2pic6.jpg" alt="Photo 6" class="photo-img">
</div>
```

2. Paste it before `</div>` (end of photos-wrapper)
3. Add `page2pic6.jpg` to folder
4. Repeat for more photos

### Share on Social Media

**Create QR Code:**
1. Use [qr-code-generator.com](https://qr-code-generator.com/)
2. Enter your GitHub Pages link
3. Download QR code
4. Share image on social media

**Share Link:**
- Facebook: Post the link directly
- Instagram: Add link in bio
- WhatsApp: Send link in message
- Email: Send link to recipients

---

## Publishing to GitHub Pages

### Step 1: Create GitHub Account

Go to [github.com](https://github.com) and sign up

### Step 2: Create Repository

1. Click **New** button
2. Name it `birthday-wish`
3. Add description (optional)
4. Click **Create repository**

### Step 3: Upload Files

1. Click **Add file** → **Upload files**
2. Drag and drop all files:
   - `birthday-wish.html`
   - `page2pic1.jpg`, `page2pic2.jpg`, etc.
   - `video.mp4`
   - `song.mp3`
   - `README.md`
   - `GUIDELINE.md`
3. Click **Commit changes**

### Step 4: Enable GitHub Pages

1. Go to **Settings**
2. Click **Pages** (left menu)
3. Under "Source", select **main** branch
4. Click **Save**

### Step 5: Your Site is Live

- Wait 1-2 minutes
- Your site will be at: `https://YOUR-USERNAME.github.io/birthday-wish/`
- Share this link with anyone!

---

## Summary Checklist

Complete this checklist before sharing:

### Content
- [ ] Page 1 heading updated with recipient's name
- [ ] Page 2 photo captions customized
- [ ] Page 3 heading updated with recipient's name
- [ ] Page 3 birthday message customized

### Files
- [ ] Photos added and renamed correctly
- [ ] Video added and renamed (if using)
- [ ] Music added and renamed (if using)
- [ ] All files in same folder as HTML

### Testing
- [ ] Opened website and tested all pages
- [ ] Clicked navigation buttons
- [ ] Checked photos appear correctly
- [ ] Tested video playback (if added)
- [ ] Tested music playback (if added)
- [ ] Hard refreshed browser
- [ ] Tested on mobile (if sharing)

### Deployment
- [ ] Created GitHub repository
- [ ] Uploaded all files
- [ ] Enabled GitHub Pages
- [ ] Tested live link
- [ ] Shared with recipients

---

Made with ❤️ for special birthday moments
