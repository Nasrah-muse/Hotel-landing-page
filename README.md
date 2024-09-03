# Hotel Landing Page

## Description

This project is a hotel landing page focused on showcasing the various services offered by the hotel, 
including room rentals, a high-end restaurant, meeting rooms, event venues, a fitness center, 
and business amenities like WiFi and a business center. The landing page is designed to be visually appealing and responsive, 
providing an excellent user experience on both desktop and mobile devices.

## Features

- **Hero Section**: Captivating banner with a call to action.
- **Rooms Section**: Comprehensive details on various room types, including pricing, amenities, and availability.
- **Gallery Section**: A visually appealing gallery showcasing high-quality images of the hotel, rooms, and events.
- **Services Section**: Detailed information on room rentals, dining options, event venues, and other services.
- **Review Section**: Testimonials from satisfied customers.
- **Reservation Section**: Easy-to-use reservation form.
- **About Section**: Attractive section highlighting the hotel's history, mission, and unique offerings.
- **Responsive Design**: Optimized for various screen sizes.
- **Interactive Navigation**: Smooth scrolling and dynamic menu highlighting.

## Technologies Used

- **HTML5**: Structuring the content and layout of the page.
- **CSS3**: Styling the webpage, including flexbox and grid layouts for responsive design.
- **JavaScript**: Enhancing user interaction and providing dynamic content updates.
 ## JavaScript Usage
 
 - **Responsive Navigation Links**: Ensured the navigation links are responsive and function smoothly, especially on smartphones.
```javascript
const hamburger = document.querySelector('.hamburger');
const navLinks = document.querySelector(".nav-links");
const icons = document.querySelectorAll("i");

hamburger.addEventListener("click", function (event) {
    const isVisible = navLinks.getAttribute('data-visible');
    if (isVisible == "true") {
        navLinks.setAttribute('data-visible', "false");
        icons[0].setAttribute('data-visible', "true");
        icons[1].setAttribute('data-visible', "false");
    } else if (isVisible == "false") {
        navLinks.setAttribute('data-visible', "true");
        icons[0].setAttribute('data-visible', "false");
        icons[1].setAttribute('data-visible', "true");

    }
});

```
## Color Scheme

The website uses a cohesive and visually appealing color scheme to enhance the user experience. Below is a table listing the colors used:

## Color Scheme

| Color Name          | Hex Code  |
|---------------------|-----------|
| Lavender            | #e6e6fa   |
| Slate Gray          | #8d99af   |
| Light Blue          | #a0c2e2   |
| Charcoal            | #2b2d42   |
| White               | #fff      |


## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Nasrah-muse/hotel-landing-page.git
    ```
2. Navigate to the project directory:
    ```bash
    cd hotel-landing-page
    ```
3. Open `index.html` in your preferred web browser.

## Live Demo 
- `[here](https://hotel-landing-page-five.vercel.app/)
