# SRM-ACM-Recruitments-assignment-

# Flickr Landing Page

## Overview

This project is a simple, visually appealing landing page inspired by Flickr. It features a header with a logo, a search bar, and authentication buttons, along with a main content section that includes an image slider and promotional text.

## File Structure

- fliker landing page.html: The HTML file containing the structure of the landing page.
- fliker.css: The CSS file defining the styles for the page.
- Flickr-Logo-PNG-Free-Download.png: The logo image used in the header.
- flicker img.png: Another logo image used in the header.
- img1.jpg, img2.jpg, img3.jpg: Images used in the slider.

## HTML

### fliker landing page.html

This file sets up the structure of the landing page. It includes:

- A header section with:
  - A logo link with two logos.
  - A search bar.
  - Authentication buttons (Log In and Sign Up).

- A main section with:
  - A slider displaying multiple images.
  - Navigation dots for the slider.
  - A title and description promoting the service.
  - A call-to-action button ("Start for free").

- Inline JavaScript for handling the image slider functionality:
  - showSlides(n): Shows the current slide based on the index.
  - autoSlide(): Automatically advances the slides.
  - An interval timer to automatically change slides every 3 seconds.

## CSS

### fliker.css

This file contains styles to make the landing page visually appealing. Key styles include:

- *General Styles*:
  - Sets a dark background (#111) and white text color (#fff).
  - Uses a sans-serif font.

- *Header*:
  - Styles the background, padding, and alignment for the header.
  - Provides styling for the search input and authentication buttons.

- *Content*:
  - Centers and styles the main content, including positioning and text color for the title and description.
  - Styles the call-to-action button.

- *Slider*:
  - Defines the appearance and animation for the image slider.
  - Uses keyframe animations to create a sliding effect.

## How to Use

1. *Setup*:
   - Ensure all image files are in the correct directory as specified in the HTML file.
   - Link the CSS file properly in the <head> section of your HTML file.

2. *Customizing*:
   - Replace the image sources (img1.jpg, img2.jpg, img3.jpg) with your own images.
   - Update the text content in the title, description, and button as needed.

3. *Running*:
   - Open index.html in a web browser to view the landing page.

4. *Modifying*:
   - Adjust CSS styles in fliker.css to fit your design preferences.
   - Modify the JavaScript in index.html to change the slider functionality or timing.

## Notes

- The slider is set to automatically transition every 3 seconds. Adjust this interval by changing the setInterval value in the JavaScript.
- Ensure that image paths and file names match those in your project to avoid broken links.

## License

This project is for demonstration purposes. You are free to use and modify it according to your needs. Attribution is appreciated if you use this code as a base for your projects.

---

Feel free to reach out if you have any questions or need further assistance!
