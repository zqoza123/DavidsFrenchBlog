# My French Adventure Blog

A simple, responsive blog template for documenting your study abroad experience in France.

## Features

- Responsive design that works on all devices
- Modern and clean interface
- Photo gallery section
- Blog post grid layout
- Smooth scrolling navigation
- Lazy loading images
- Social media integration

## Getting Started

1. Clone this repository
2. Replace the placeholder images with your own photos
3. Update the content in `index.html` with your own text
4. Customize the colors and styles in `styles.css` if desired
5. Deploy to your preferred hosting service

## Customization

### Adding New Blog Posts

To add a new blog post, copy the following template and add it to the `post-grid` div in `index.html`:

```html
<article class="post-card">
    <div class="post-image">
        <img src="path-to-your-image.jpg" alt="Post image">
    </div>
    <div class="post-content">
        <div class="post-date">Date</div>
        <h3>Post Title</h3>
        <p>Post content...</p>
        <a href="#" class="read-more">Read More</a>
    </div>
</article>
```

### Adding Photos to Gallery

To add new photos to the gallery, add new `gallery-item` divs to the `gallery-grid` div:

```html
<div class="gallery-item">
    <img src="path-to-your-image.jpg" alt="Gallery image">
</div>
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. 