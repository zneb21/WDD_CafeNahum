# Cafe Nahum Website

This is a 5-page static website project for CCS 222 - Web Design and Development. The group chose Cafe Nahum, a local coffee shop in Iloilo City.

## About the Business

Cafe Nahum is a coffee shop that offers coffee drinks, non-coffee drinks, matcha, and fruit tea. One listed branch is located at 18 Commission Civil Street, Barangay Marcelo H. del Pilar, Iloilo City.

The group checked online listings before choosing the business. Cafe Nahum was found on Foodpanda, Facebook, and Instagram, but no separate official website was found. The Foodpanda listing and social media pages are only used as business references.

## Website Pages

1. **Home** - Introduces Cafe Nahum and links to the other pages.
2. **About Us** - Gives background information about the coffee shop.
3. **Products / Services** - Shows the drinks and other products offered.
4. **Gallery** - Shows pictures related to the coffee shop and its products.
5. **Contact Us** - Includes a contact and inquiry form.

## Design

The group used a warm coffee-inspired design with simple navigation. The colors, images, and layout are meant to make the website feel cozy and welcoming.

The website is made with HTML and CSS only. It is a static website and does not use a database.

## Main Features

- **Shared navigation:** Every page includes the Cafe Nahum logo, navigation links, sidebar menu, and footer.
- **Collapsible sidebar:** The menu button uses HTML `<details>` and `<summary>` elements. Clicking the three-line icon opens the sidebar, and clicking it again closes the sidebar.
- **Responsive layout:** CSS media queries adjust the navigation, footer, gallery, forms, and page layouts for smaller screens.
- **Gallery:** The gallery uses a CSS column layout to display nine cafe-related images with captions.
- **Contact form:** The form demonstrates text, email, telephone, password, number, date, time, radio, checkbox, select, textarea, file-upload, submit, and reset controls. It is for demonstration only and does not send data.

## CSS Structure

The styles are separated to keep the project easier to understand and edit.

| CSS File | Purpose |
|---|---|
| `css/universal.css` | Shared body, headings, header, navigation, sidebar, footer, and shared mobile styles |
| `css/home.css` | Home-page hero section, coffee cup, decorations, and buttons |
| `css/about.css` | About-page text, image, mission, vision, and values |
| `css/menu.css` | Menu layout, product sections, prices, and product images |
| `css/gallery.css` | Gallery heading, image cards, captions, and responsive grid |
| `css/contact.css` | Contact details, hours, map design, and inquiry form |

Each HTML page loads `universal.css` first and then its own page stylesheet. This lets the shared design stay consistent while keeping page-specific code separate.

## Why the Group Chose Cafe Nahum

The group chose Cafe Nahum because it is a local coffee shop in Iloilo. It has different drinks and products that can be presented well on a website.

The group also wanted to help make the cafe's information easier for customers to find online.

## Target Audience

The target audience includes coffee drinkers, students, workers, local customers, and people looking for a place to buy drinks or relax.

## Problems the Website Solves

The website gives customers one place to see the cafe's products, pictures, basic business information, and contact form.

It can also help new customers learn about Cafe Nahum before visiting or ordering.

## Group Reflection

The group is most proud of the overall website layout and the way the pages are connected through the navigation menu.

The most difficult part was planning the page content and making the design look consistent on all five pages. The group also had to make sure the contact form included the required HTML input types.

## Files

| File or Folder | Description |
|---|---|
| `index.html` | Home page |
| `about.html` | About Us page |
| `services.html` | Products / Menu page |
| `gallery.html` | Gallery page |
| `contact.html` | Contact Us page |
| `css/universal.css` | Shared website styles |
| `css/home.css` | Home page styles |
| `css/about.css` | About page styles |
| `css/menu.css` | Menu page styles |
| `css/gallery.css` | Gallery page styles |
| `css/contact.css` | Contact page styles |
| `images/` | Website images |

## References

- [Cafe Nahum Foodpanda Listing](https://www.foodpanda.ph/restaurant/ryet/cafe-nahum-commission-civil-street)
- [Cafe Nahum Facebook page](https://www.facebook.com/cafenahumans)
- [Cafe Nahum Instagram page](https://www.instagram.com/cafenahum_)
- [Cafe Nahum TikTok page](https://www.tiktok.com/@cafe.nahum)

The Facebook and Instagram pages can be used to check the cafe's latest posts, products, announcements, and other business information.

The information in this README is for the class project and may change if the business updates its menu, location, or contact details.
