# How to Add Your Profile Picture

## Step 1: Add Your Image File

1. **Copy your profile picture** to this folder (`geraldalbacite-portfolio`)
2. **Rename it** to something simple like:
   - `profile.jpg`
   - `gerald.jpg` 
   - `profile.png`
   - `profile.webp`

## Step 2: Update the CSS

Open `styles.css` and find line 235 (around line 235):

```css
/* background-image: url('profile.jpg'); */
```

**Uncomment and update it:**
```css
background-image: url('profile.jpg');
```

Replace `profile.jpg` with your actual filename.

## Step 3: Add the CSS Class

In the same `styles.css` file, find the `.profile-avatar` section and add the `has-image` class:

```css
.profile-avatar {
    /* existing styles... */
    background-image: url('profile.jpg');
}
```

## Step 4: Update HTML (Optional)

In `index.html`, you can add the `has-image` class to hide the default icon:

```html
<div class="profile-avatar has-image" id="profileAvatar">
    <i class="fas fa-user"></i>
</div>
```

## Complete Example

If your image is named `gerald.jpg`, your CSS should look like:

```css
.profile-avatar {
    width: 300px;
    height: 300px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    backdrop-filter: blur(10px);
    border: 2px solid rgba(255, 255, 255, 0.2);
    position: relative;
    z-index: 2;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-image: url('gerald.jpg');
}
```

And your HTML:
```html
<div class="profile-avatar has-image" id="profileAvatar">
    <i class="fas fa-user"></i>
</div>
```

## Tips

- **Image size**: Use a square image (1:1 aspect ratio) for best results
- **File size**: Keep under 500KB for fast loading
- **Format**: JPG, PNG, or WebP work best
- **Quality**: 400x400px or 500x500px is perfect

After making changes, commit and push to GitHub:
```bash
git add .
git commit -m "Add profile picture"
git push origin main
```
