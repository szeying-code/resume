# Résumé profile photo asset

This package contains `profile.png`, a circular transparent PNG made from the supplied profile photo.

## Add it to the résumé repository

1. Copy `profile.png` into the repository (for example, `assets/profile.png`).
2. In the HTML where the sphere logo is rendered, replace that logo element with:

```html
<img class="profile-photo" src="assets/profile.png" alt="Choong Sze Ying">
```

3. Add this CSS:

```css
.profile-photo {
  display: block;
  width: 112px;
  height: 112px;
  border-radius: 50%;
  object-fit: cover;
  object-position: center;
  border: 3px solid currentColor;
}
```

Adjust the width and height to match the existing sphere logo size.

## Important

The repository source could not be retrieved in this session, so this package does not contain a modified copy of the website. Replace the actual sphere-logo markup in the repository with the snippet above, and adjust the asset path if you put the image somewhere else.
