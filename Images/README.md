Place your image file here so `style1.css` can load it.

Expected filename and path from `HTML_FILES/CLASS3/style1.css`:
- `background-image: url('../../Images/image1.jpeg');`

Notes:
- Filename is case-sensitive on Linux. Use `image1.jpeg` (not `Image1.JPG` etc.).
- If your image uses a `.jpg` extension, either rename it to `.jpeg` or update the CSS path accordingly.

Recommended CSS for `#box1` (in `HTML_FILES/CLASS3/style1.css`):

```css
#box1 {
  position: static;
  background-image: url('../../Images/image1.jpeg'); /* adjust if needed */
  background-size: cover;       /* scale to cover the box */
  background-position: center;  /* center the image */
}
```

After uploading `image1.jpeg` here, reload `http://localhost:5500/index1.html` to verify the background appears.