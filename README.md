# Fresh Plate - Luxury Hotel & Resort

Welcome to the official repository for **Fresh Plate**, a modern, responsive front-end website for a world-class luxury hotel, resort, and fine dining establishment. Built with clean HTML5, CSS3, and dynamic jQuery plugins, Fresh Plate delivers an elegant and seamless digital experience for prospective guests.

---

## 🍽️ About Fresh Plate

**Fresh Plate** represents the epitome of luxury hospitality and culinary excellence. With properties extending worldwide, Fresh Plate offers guests indulgent stays, complimentary wellness services, world-class amenities, and memorable seaside tranquility.

The website provides an intuitive, user-friendly interface designed for effortless exploration, room browsing, and reservation booking across desktop, tablet, and mobile devices.

---

## 📞 Contact Details & Alternative Information

Fresh Plate maintains open communication channels for reservations, concierge inquiries, and guest support:

| Detail | Primary Information | Alternative Information |
| :--- | :--- | :--- |
| **Brand Name** | **Fresh Plate** | Fresh Plate Hotel & Resort |
| **Physical Address** | 415, Park Avenue, Hawaii | Hilo Coast, HI |
| **Phone Number** | **(211) 9275693451** | **(211) 9275693452** |
| **E-mail Address** | **info@freshplate.com** | **support@freshplate.com** |
| **Concierge / Front Desk** | 24 Hours / 7 Days a week | Reservations Desk |

*All pages feature the complete contact details in the footer, and the dedicated Contact page provides dual contact fields in both the inquiry form and the location card.*

---

## 🌐 Website Pages

The website consists of 5 core web pages:

### 1. Home Page (`index.html`)
- **Hero Image Slider**: Automated and draggable carousel powered by Slick Slider displaying scenic views, relaxing spa facilities, luxury suites, and oceanfront balconies.
- **Suites & Rooms Showcase**: Quick-glance carousel of luxury, deluxe, and premier suites with one-click navigation to room details.
- **Signature Amenities**: Highlights complimentary guest services including 24/7 Room Service, Complimentary Gourmet Breakfast, Free Valet Parking, and Daily In-house Spa sessions.
- **Guest Reviews & Ratings**: Testimonials carousel featuring 5-star guest reviews with star rating indicators.
- **Direct Reservation CTA**: Prominent call-to-action button redirecting guests directly to the booking page.

### 2. Explore Page (`explore.html`)
- A minimalist, visual journey highlighting key resort attractions and amenities:
  - **Luxurious and Spacious Rooms**
  - **In-house Spa & Wellness**
  - **Scenic Swimming Pools**
  - **Indoor Game Room & Recreation**
- Quick reservation banner at the bottom of the page.

### 3. Rooms & Suites Page (`rooms.html`)
- Comprehensive accommodations catalog showcasing:
  - **Luxury Suite** ($1999.99/night) – 2 Beds, Complimentary Liquor, Free Wi-Fi
  - **Delux Suite** ($1599.99/night) – 2 Beds, Luxurious Interior, Free Wi-Fi
  - **Premier Suite** ($1299.99/night) – 2 Beds, Scenic Beach View, Free Wi-Fi
  - **Luxury Room** ($999.99/night) – 2 Beds, Free Wi-Fi, Fresh Towels
  - **Delux Room** ($599.99/night) – 2 Beds, Value Pricing, Fresh Towels
  - **Premier Room** ($399.99/night) – 1 Bed, Value Pricing, Fresh Towels
- **Interactive CSS3 Hover Transitions**: Hovering over any accommodation card smoothly slides up pricing and amenity badges using pure CSS3 linear animations.

### 4. Booking & Reservation Page (`bb.html`)
- Dedicated reservation engine for prospective visitors:
  - **Guest Contact Information**: Fields for Full Name, Primary E-mail, Primary Contact Number, and Alternative Contact Number.
  - **Room Type Selection**: Dropdown menu for all available suites and rooms.
  - **Room & Guest Spinner Counters**: Interactive `+` and `-` quantity selectors powered by the `handleCounter` jQuery plugin.
  - **Date Range Picker**: Arrival and departure date selection powered by the `pickmeup` datepicker plugin.
  - **Proceed Button**: Smooth submission workflow for finalizing bookings.

### 5. Contact Us Page (`contact.html`)
- **Direct Contact Card**: Displays the resort address, primary phone, alternative phone, primary email, and alternative email.
- **Inquiry Form**: Enables visitors to reach customer service with fields for Name, Primary Email, Alternative Email, Primary Phone, Alternative Phone, and Message.
- **Google Maps Integration**: Interactive map centered on the Hawaii resort location (`19.735121, -155.014044`).

---

## 🛠️ Technology Stack & Libraries

- **Markup & Layout**: HTML5, Semantic Elements
- **Styling**: CSS3 (Flexbox, CSS Transitions, Viewport-relative Units `vw`/`vmax`)
- **Typography**: Google Fonts ([Open Sans](https://fonts.google.com/specimen/Open+Sans))
- **Scripting**: JavaScript (ES6+), jQuery 3.2.1

### Included jQuery Plugins

| Plugin | Purpose | Repository / Reference |
| :--- | :--- | :--- |
| **Slick Slider** | Responsive, draggable image and review carousels | [kenwheeler/slick](https://github.com/kenwheeler/slick) |
| **PickMeUp** | Lightweight, customizable date range picker | [nazar-pc/PickMeUp](https://github.com/nazar-pc/PickMeUp) |
| **Handle Counter** | Quantity increment/decrement spinner controls | [nick-running/handle-counter](https://github.com/nick-running/handle-counter) |
| **jQuery ScrollUp** | Smooth animated scroll-to-top button | [markgoodyear/scrollup](https://github.com/markgoodyear/scrollup) |
| **Google Maps API** | Interactive property location mapping | [Google Maps JavaScript API](https://developers.google.com/maps) |

---

## 📁 Project Structure

```plaintext
Fresh-Plate/
├── index.html                 # Fresh Plate Home page
├── explore.html               # Explore amenities and services
├── rooms.html                 # Room catalog and pricing details
├── bb.html                    # Reservation and booking form
├── contact.html               # Contact details, map, and inquiry form
├── README.md                  # Project documentation
├── css/
│   ├── main.css               # Core styling, layouts, and animations
│   ├── slick.css              # Slick slider primary styles
│   ├── slick-theme.css        # Slick slider optional theme
│   ├── pickmeup.css           # Datepicker plugin styles
│   └── handle-counter.min.css # Spinner counter button styles
├── dist/
│   ├── demo.js                # Initialization scripts for plugins and maps
│   ├── demo2.js               # Secondary script placeholder
│   ├── slick.js               # Slick slider library
│   ├── pickmeup.min.js        # PickMeUp datepicker library
│   ├── handleCounter.js       # Handle Counter library
│   └── jquery.scrollUp.js     # ScrollUp plugin library
└── images/
    ├── fresh_plate_logo.svg   # Fresh Plate vector brand identity
    ├── fresh_plate_logo.png   # High-resolution Fresh Plate logo
    ├── placeholder.png        # Map pin and location icon
    ├── main_slider11.png      # Slider hero image 1
    ├── main_slider12.png      # Slider hero image 2
    ├── main_slider13.png      # Slider hero image 3
    ├── main_slider14.png      # Slider hero image 4
    ├── luxury.png             # Luxury Suite preview
    ├── delux.png              # Delux Suite preview
    ├── premier.png            # Premier Suite preview
    ├── luxuryroom.png         # Luxury Room preview
    ├── deluxroom.png          # Delux Room preview
    ├── premiumroom.png        # Premier Room preview
    ├── fb.png                 # Social icon: Facebook
    ├── G.png                  # Social icon: Google
    ├── twittr.png             # Social icon: Twitter
    ├── insta.png              # Social icon: Instagram
    └── ...                    # Additional icons and graphics
```

---

## 🚀 How to Run Locally

Because this is a pure front-end project (HTML, CSS, JavaScript), no build step, compiler, or database is required.

### Option 1: Direct File Launch
Double-click `index.html` or open it with your favorite web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

### Option 2: Using a Local Development Server
For optimal performance and to ensure Google Maps and external resources load seamlessly without `file://` CORS restrictions:

Using **Node.js** (`npx serve`):
```bash
npx serve .
```

Using **Python** (if installed):
```bash
python -m http.server 8000
```

Using **VS Code Live Server**:
Right-click `index.html` and click **"Open with Live Server"**.

---

## 📱 Browser Compatibility

- Google Chrome (Latest)
- Microsoft Edge (Latest)
- Mozilla Firefox (Latest)
- Apple Safari (Latest)
- Mobile Browsers (iOS Safari, Android Chrome)

---

## 📄 License & Attribution

- Designed and curated for **Fresh Plate**.
- Open-source plugins are licensed under their respective MIT/Open-Source licenses.
