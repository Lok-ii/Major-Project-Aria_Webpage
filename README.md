# Major-Project-Aria_Webpage

Hosted Link:- https://lok-ii.github.io/Major-Project-Aria_Webpage/


![Screenshot 2023-08-28 193028](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/5f259338-c3cf-404e-ae02-2925c1dcd3ab)

    Primary Navigation Bar:

        This is the main navigation bar at the top of the page.
        It contains a logo image on the left.
        To the right of the logo, there's an unordered list of navigation items.
        Each navigation item is a link with text, such as "Home," "Intro," "Services," etc.
        Some navigation items have icons (e.g., a down arrow) next to them.
        When you hover over links or icons, they change color to a light green.
        The navigation bar has a dark green background with white text.
        
    Secondary Navigation Bar:
        
        This is a secondary navigation bar, likely intended for mobile or small screens.
        It also contains a logo image on the left.
        On the right, there is a bars icon (typically used to indicate a menu).
        The secondary navigation is initially hidden (display: none;) but can be toggled to display, perhaps for mobile navigation.


    Explanation:
        1. Primary Navigation Bar:

            <nav class="primary">: This HTML tag represents the primary navigation bar.
            
            CSS properties applied:
                display: flex;: Displays the navigation bar as a flex container.
                flex-direction: row;: Sets the flex direction to a horizontal row.
                gap: 5px;: Adds a gap of 5 pixels between child elements.
                position: fixed;: Fixes the navigation bar position on the viewport.
                justify-content: space-between;: Distributes space between the logo and navigation items.
                align-items: center;: Vertically centers items within the navigation bar.
                width: 100%;: Sets the width to 100% of the viewport.
                background-color: var(--dark-green);: Sets the background color to a dark green shade.
                padding: 1rem 3rem;: Adds padding to the top and bottom (1rem) and left and right (3rem).
                color: var(--white);: Sets the text color to white.
                z-index: 100;: Places the navigation bar above other elements.
            
            <img src="...">: This HTML tag represents the logo image.
            
            CSS properties applied:
                height: 2rem;: Sets the height of the logo image to 2 rem units.
            
            <ul class="nav-items">: This HTML tag represents an unordered list of navigation items.
            
            CSS properties applied:
                display: flex;: Displays the list items as a flex container.
                flex-direction: row;: Arranges the items in a horizontal row.
                list-style: none;: Removes the default list bullet points.
                align-items: center;: Vertically centers items within the list.
                gap: 1rem;: Adds a gap of 1 rem between list items.
                font-size: 0.9rem;: Sets the font size for the list items.
                font-weight: 600;: Sets the font weight to 600 (semi-bold).
            
            <li> and <a>: These HTML tags represent list items and anchor links respectively for the navigation items.
            
            CSS properties applied to <a>:
                text-decoration: none;: Removes underline from anchor links.
                font-family: var(--Opensans);: Applies a custom font family (assuming it's defined elsewhere).
                transition: color 0.3s ease-in-out;: Adds a smooth color transition effect.
                color: var(--white);: Sets the default text color for links.
                CSS properties applied to <a:active> and <a:hover>:
                color: var(--light-green);: Changes the text color on active and hover states.
            
            .with-icon and .fa-sort-down: These classes are used to add an icon next to a navigation item.
            
            CSS properties applied to .with-icon:hover i:
                color: var(--light-green);: Changes the color of the icon on hover.
            
        2. Secondary Navigation Bar:
            
            <nav class="secondary">: This HTML tag represents the secondary navigation bar.
            CSS properties applied:
                display: none;: Initially hides the secondary navigation bar.
            <i class="fa-solid fa-bars"></i>: This HTML tag represents an icon (likely a hamburger menu icon).
        

![Screenshot 2023-08-28 193051](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/d78a65ae-a66e-4470-8b68-77e2d0df8076)

    Section with Class "home" (Home Section):

        <section class="home" id="home">: This HTML tag represents the home section.
        
        CSS properties applied:
            background-image: Creates a linear gradient overlay combined with a background image.
            min-height: 120vh;: Sets a minimum height of 120 viewport heights.
            display: flex;: Displays the section as a flex container.
            flex-direction: column;: Arranges the content in a column layout.
            justify-content: center;: Vertically centers the content.
            align-items: center;: Horizontally centers the content.
            text-align: center;: Centers the text within the section.
            color: var(--white);: Sets the text color to white.
            background-position: center;: Positions the background image at the center.
            background-repeat: no-repeat;: Prevents the background image from repeating.
            background-size: cover;: Scales the background image to cover the entire section.
        
        <h1>: This HTML tag represents the main heading.
        
        CSS properties applied:
            font-size: 3.5rem;: Sets the font size to 3.5 rem units.
            color: var(--white);: Sets the text color to white.
        
        <p>: This HTML tag represents a paragraph of text.
        
        CSS properties applied:
            width: 42%;: Sets the width of the paragraph.
            color: var(--dark-white);: Sets the text color to a dark white shade.
            font-size: 1.15rem;: Sets the font size to 1.15 rem units.
            margin-bottom: 2rem;: Adds margin at the bottom.
            line-height: 1.6rem;: Sets the line height for the paragraph.
        
        <button>: This HTML tag represents a button.
        
        CSS properties applied:
            padding: 0.9rem 2.2rem;: Sets padding for the button.
            color: var(--white);: Sets the text color to white.
            font-weight: 700;: Sets the font weight to 700 (bold).
            text-transform: uppercase;: Converts text to uppercase.
            background-color: var(--light-green);: Sets the background color to a light green shade.
            border-radius: 5px;: Rounds the button corners.
            border: 2px solid var(--light-green);: Adds a border with a light green color.
            transition: all 0.5s ease-in-out;: Adds a smooth transition effect.
            font-size: 0.75rem;: Sets the font size to 0.75 rem units.
            cursor: pointer;: Changes the cursor to a pointer on hover.
        CSS properties applied to button:hover:
            background-color: transparent;: Removes background color on hover.
            color: var(--light-green);: Changes text color on hover.

![Screenshot 2023-08-28 193115](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/0b99f869-e136-4cc9-b59e-edf16697c615)

    Section with Class "intro" (Introduction Section):

        <section class="intro" id="intro">: This HTML tag represents the introduction section.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            flex-direction: row;: Arranges the content in a row layout.
            justify-content: center;: Horizontally centers the content.
            align-items: center;: Vertically centers the content.
            padding: 6.5rem 2rem 3rem 2rem;: Sets padding around the content.
        
        .text: This class represents the text content within the introduction section.
        
        CSS properties applied:
            width: 100%;: Sets the width to 100%.
            padding-left: 3rem;: Adds left padding.
            padding-top: 2rem;: Adds top padding.
            max-width: 37rem;: Sets the maximum width.
        
        .text h1: This targets the headings within the .text element.
        
        CSS properties applied:
            color: var(--dark-gray);: Sets the text color to a dark gray shade.
            width: 70%;: Sets the width of the heading.
            font-size: 1.75rem;: Sets the font size to 1.75 rem units.
        
        .text h4: This targets the subheading within the .text element.
        
        CSS properties applied:
            color: var(--dark-gray);: Sets the text color to a dark gray shade.
        
        span: This HTML tag represents the introductory label "Intro".
        
        CSS properties applied:
            color: var(--light-green);: Sets the text color to a light green shade.
            font-size: 0.8rem;: Sets the font size to 0.8 rem units.
            font-weight: 500;: Sets the font weight to 500.
            text-transform: uppercase;: Converts text to uppercase.
        
        .intro .text p: This targets the paragraphs within the .text element.
        
        CSS properties applied:
            width: 75%;: Sets the width of the paragraph.
            font-size: 1rem;: Sets the font size to 1 rem unit.
            margin: 1.5rem 0;: Sets margin above and below the paragraph.
            color: var(--light-gray);: Sets the text color to a light gray shade.
        
        .quote: This class targets the quote paragraph.
        
        CSS properties applied:
            font-style: italic;: Applies italic font style to the text.
        
        .image-container: This class represents the container for the image within the introduction section.
        
        CSS properties applied:
            background-position: center;: Positions the background image at the center.
            background-size: contain;: Scales the background image to fit within the container.
            background-repeat: no-repeat;: Prevents the background image from repeating.
            overflow: hidden;: Hides overflowing content.
            border-radius: 0.25rem;: Adds rounded corners to the container.
        
        .image-container img: This targets the image within the .image-container.
        
        CSS properties applied:
            width: 100%;: Sets the width to 100%.
            height: 100%;: Sets the height to 100%.
            transition: all 0.3s;: Adds a smooth transition effect.
        
        .image-container img:hover: This targets the image within .image-container on hover.
        
        CSS properties applied:
            transform: scale(1.1);: Enlarges the image on hover.

![Screenshot 2023-08-28 193124](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/542fc478-0950-4855-a979-971c132f3c19)

    Section with Class "cards" (Cards Section):

        <section class="cards">: This HTML tag represents the section containing the cards.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            justify-content: center;: Horizontally centers the content.
            align-items: flex-start;: Aligns items at the start of the cross axis.
            margin-top: 3rem;: Adds margin at the top.
            padding-left: 12rem;: Adds left padding.
        
        .card: This class represents an individual card within the .cards section.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            flex-direction: column;: Arranges the content in a column layout.
            align-items: flex-start;: Aligns items at the start of the cross axis.
        
        .card img: This targets the images within the .card elements.
        
        CSS properties applied:
            width: 6rem;: Sets the width of the image.
            height: 6rem;: Sets the height of the image.
        
        .hexagon: This class targets the hexagon icons within the cards.
        
        CSS properties applied:
            font-size: 2rem;: Sets the font size to 2 rem units.
            color: var(--white);: Sets the icon color to white.
            position: absolute;: Sets the icon's position to absolute.
            top: 2rem;: Sets the icon's position from the top.
            left: 44%;: Sets the icon's position from the left.
        
        .card p: This targets the paragraphs within the .card elements.
        
        CSS properties applied:
            width: 75%;: Sets the width of the paragraph.
            font-size: 1rem;: Sets the font size to 1 rem unit.
            margin: 1.5rem 0;: Sets margin above and below the paragraph.
            color: var(--light-gray);: Sets the text color to a light gray shade.
        
        .card .icon: This class represents the container for the icon within each card.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            align-items: center;: Aligns items vertically in the center.
            justify-content: center;: Aligns items horizontally in the center.
            position: relative;: Sets the position to relative.

            
![Screenshot 2023-08-28 193148](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/5146a7d1-658f-4f97-92b2-402bfe6ec88c)
![Screenshot 2023-08-28 193202](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/ed767862-3fc5-49e7-8fcf-3cf81eb3f931)
![Screenshot 2023-08-28 193214](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/f8a3f073-1f23-430b-aea4-8e158a727520)
![Screenshot 2023-08-28 193221](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/d2c8db0f-97ce-43b7-abb5-c70b56abe48e)

    Section with Class "services" (Services Section):

        <section class="services" id="services">: This HTML tag represents the services section.
        
        CSS properties applied:
            padding: 5rem 0;: Adds padding to the section.
            background-color: var(--background-color);: Sets the background color.
            
        .services .services-title: This class targets the title "SERVICES" within the section.
        
        CSS properties applied:
            display: block;: Sets the display property to block.
            text-align: center;: Centers the text horizontally.
            color: var(--light-green);: Sets the text color to light green.
        
        .services .service-subtitle: This class targets the subtitle within the section.
        
        CSS properties applied:
            text-align: center;: Centers the text horizontally.
            font-size: 1.8rem;: Sets the font size to 1.8 rem units.
            color: var(--dark-gray);: Sets the text color to dark gray.
        
        .service-list-container: This class represents the container for the service items.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            justify-content: space-evenly;: Distributes space evenly between the items.
            padding: 3rem 10vw;: Adds padding to the container.
            align-items: start;: Aligns items at the start of the cross axis.
        
        .services .service-item: This class represents an individual service item.
        
        CSS properties applied:
            width: 27.5%;: Sets the width of the item.
            flex-grow: 0;: Disables flex-grow.
            flex-shrink: 0;: Disables flex-shrink.
            background-color: var(--white);: Sets the background color to white.
            border-radius: 5px;: Adds border-radius.
        
        .services .service-item img: This targets the images within the service items.
        
        CSS properties applied:
            width: 100%;: Sets the width to 100%.
            height: 12rem;: Sets the height of the image.
            object-fit: cover;: Applies the "cover" value for object-fit.
            object-position: center;: Centers the image horizontally.
        
        .services .service-item h4: This targets the headings within the service items.
        
        CSS properties applied:
            text-align: center;: Centers the text horizontally.
            font-size: 1.375rem;: Sets the font size to 1.375 rem units.
            color: var(--dark-gray);: Sets the text color to dark gray.
            padding: 0.5rem 2rem;: Adds padding to the heading.
        
        .services .service-item p: This targets the paragraphs within the service items.
        
        CSS properties applied:
            line-height: 1.5rem;: Sets the line height for the paragraph.
            color: var(--light-gray);: Sets the text color to light gray.
            padding: 0.5rem 2rem;: Adds padding to the paragraph.
        
        .services .service-item ul: This targets the unordered lists within the service items.
        
        CSS properties applied:
            line-height: 2rem;: Sets the line height for list items.
            color: var(--light-gray);: Sets the text color to light gray.
            padding: 0.5rem 2.2rem;: Adds padding to the list.
            list-style: none;: Removes default list bullets.
        
        .services .service-item ul li:before: This targets the list items within the unordered lists.
        
        CSS properties applied:
            content: "\25a0";: Sets the content to a square bullet.
            color: var(--light-green);: Sets the bullet color to light green.
            margin-right: 5px;: Adds margin on the right.
            margin-top: -5px;: Adjusts margin on top.
            font-size: 1rem;: Sets the font size to 1 rem unit.
        
        .services .service-item .cost: This targets the cost details within the service items.
        
        CSS properties applied:
            color: var(--dark-gray);: Sets the text color to dark gray.
            font-size: 1rem;: Sets the font size to 1 rem unit.
            text-align: center;: Centers the text horizontally.
            font-weight: 700;: Sets the font weight to 700.
        
        .price: This class targets the price within the cost details.
        
        CSS properties applied:
            color: var(--light-green);: Sets the text color to light green.
            font-size: 1rem;: Sets the font size to 1 rem unit.
            font-weight: 700;: Sets the font weight to 700.
            
        .services .service-item button: This targets the buttons within the service items.
        
        CSS properties applied:
            top: 0;: Sets the top position to 0.
            left: 50%;: Sets the left position to 50%.
            position: relative;: Sets the position to relative.
            transform: translate(-50%, 50%);: Translates the button to center it.
            background-color: var(--white);: Sets the initial background color.
        
        .services .service-item button:hover: This targets the buttons within the service items on hover.
        
        CSS properties applied:
            background-color: var(--white);: Sets the background color to white on hover.
            
        .services .proportions-1, .services .proportions-2: These classes represent the proportioned content sections.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            margin-top: 4rem; (proportions-1), margin-top: 2rem; (proportions-2): Adds margin at the top.
        
        .services .proportions-1 img, .proportions-2 img: These target the images within the proportioned content sections.
        
        CSS properties applied:
            max-width: 47.5rem;: Sets the maximum width of the image.
            height: 34.6875rem;: Sets the height of the image.
        
        .proportion-content: This class represents the content within the proportioned sections.
        
        CSS properties applied:
            width: 55%;: Sets the width of the content.
            padding: 6rem 3.5rem;: Adds padding to the content.
        
        .proportion-content .growth: This class targets the growth heading within the proportioned content.
        
        CSS properties applied:
            font-size: 1.75rem;: Sets the font size to 1.75 rem units.
        
        .points: This class represents the points within the proportioned content.
        
        CSS properties applied:
            margin: 1rem 0;: Adds margin around the points.
        
        .growth-points:hover .circle: This targets the circles within the growth points on hover.
        
        CSS properties applied:
            color: var(--light-green);: Sets the color to light green on hover.
            border: 2px solid var(--light-green);: Adds border on hover.
        
        .growth-points:hover h4: This targets the headings within the growth points on hover.
        
        CSS properties applied:
            color: var(--light-green);: Sets the color to light green on hover.
        
        .proportion-content h4: This targets the headings within the proportioned content.
        
        CSS properties applied:
            font-size: 1.25rem;: Sets the font size to 1.25 rem units.
        
        .growth-points: This class represents the growth points.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            align-items: center;: Aligns items vertically in the center.
            cursor: pointer;: Sets the cursor to pointer.
            gap: 1rem;: Adds gap between items.
            
        .circle: This class represents the circles within the growth points.
        
        CSS properties applied:
            width: 2rem;: Sets the width of the circle.
            height: 2rem;: Sets the height of the circle.
            border-radius: 50%;: Sets the border radius to make it a circle.
            border: 2px solid var(--dark-gray);: Adds border.
            color: var(--dark-gray);: Sets the color to dark gray.
            text-align: center;: Centers the content within the circle.
            padding-top: 0.2rem;: Adds padding at the top.
            font-weight: 700;: Sets the font weight to 700.
            font-family: var(--Opensans);: Sets the font family.
            
        .growth-points a: This targets the links within the growth points.
        
        CSS properties applied:
            color: var(--dark-gray);: Sets the text color to dark gray.
        
        .points:hover .point-details: This targets the point details on hover.
        
        CSS properties applied:
            display: block;: Displays the details on hover.
            padding: 0 0.5rem 0 3rem;: Adds padding to the details.
        
        .point-details: This class represents the point details.
        
        CSS properties applied:
            display: none;: Initially hides the details.
            line-height: 1.75rem;: Sets the line height for the details.
        
        .fa-table-cells: This class targets the icons within the proportioned content.
        
        CSS properties applied:
            color: var(--green);: Sets the icon color to green.
            background-color: var(--white);: Sets the background color to white.
            font-size: 1.3rem;: Sets the font size to 1.3 rem units.
        
        .proportion-content a: This targets the links within the proportioned content.
        
        CSS properties applied:
            text-decoration: none;: Removes the default underline decoration.
        
        .data-container: This class represents the container for the data items.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            align-items: center;: Aligns items vertically in the center.
            gap: 2rem;: Adds gap between items.
        
        .data: This class represents individual data items.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            align-items: center;: Aligns items vertically in the center.
            gap: 0.5rem;: Adds gap between items.
        
        .data h3: This targets the headings within the data items.
        
        CSS properties applied:
            font-size: 1.3rem;: Sets the font size to 1.3 rem units.
        
        .data-title: This class represents the title for the data items.
        
        CSS properties applied:
            margin: 1.5rem 0;: Adds margin around the title.
        
        .data-details: This class represents the details within the data items.
        
        CSS properties applied:
            line-height: 1.62rem;: Sets the line height for the details.
        
        .data-details a: This targets the links within the data details.
        
        CSS properties applied:
            text-decoration: underline;: Adds underline decoration to the links.
            color: var(--light-green);: Sets the text color to light green.
        
        .progress: This class represents the progress section.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            flex-direction: column;: Arranges items in a column layout.
            justify-content: center;: Centers items vertically.
            gap: 0.5rem;: Adds gap between items.
            margin-top: 2rem;: Adds margin at the top.
        
        .progressbar: This class represents the progress bar container.
        
        CSS properties applied:
            background-color: var(--dark-white);: Sets the background color to a darker white shade.
            width: 28rem;: Sets the width of the progress bar container.
            height: 1.3rem;: Sets the height of the progress bar container.
            border-radius: 2px;: Adds border-radius.
        
        .progress100, .progress76, .progress90: These classes represent different progress bars with varying percentages filled.
        
        CSS properties applied:
            .progress100: Sets the width to 100% for full progress.
            .progress76: Sets the width to 76% for progress.
            .progress90: Sets the width to 90% for progress.
        
        .testimonials: This class represents the testimonials section.
        
        CSS properties applied:
            display: flex;: Sets the display property to flex.
            flex-direction: column;: Arranges items in a column layout.
            justify-items: center;: Centers items horizontally within their container.
            align-content: center;: Aligns items vertically within their container.
            text-align: center;: Centers the text horizontally.
            margin-top: 3rem;: Adds margin at the top.
            padding-top: 2rem;: Adds padding at the top.
        
        .testimonials h2: This targets the heading within the testimonials section.
        
        CSS properties applied:
            margin: 1rem 0;: Adds margin around the heading.
        
        .testimonial-list-container: This class represents the container for testimonial items.
        
        CSS properties applied:
            max-width: 1100px;: Sets the maximum width of the container.
            margin-top: 2rem;: Adds margin at the top.
            display: flex;: Sets the display property to flex.
            overflow-x: scroll;: Adds horizontal scroll for items.
            text-align: center;: Centers the text horizontally.
            justify-content: flex-start;: Justifies content to the start of the container.
            align-items: center;: Aligns items vertically within the container.
            gap: 2.5rem;: Adds gap between items.
            margin: 0 12rem;: Adds margin to the sides.
        
        .testimonial-item: This class represents individual testimonial items.
        
        CSS properties applied:
            width: 15rem;: Sets the width of the item.
            flex-grow: 0;: Disables flex-grow.
            flex-shrink: 0;: Disables flex-shrink.
            display: flex;: Sets the display property to flex.
            flex-direction: column;: Arranges items in a column layout.
            align-items: center;: Aligns items vertically in the center.
            flex-wrap: wrap;: Allows content to wrap within the item.
            gap: 1rem;: Adds gap between items.
        
        .testimonial-item img: This targets the images within the testimonial items.
        
        CSS properties applied:
            width: 5.5rem;: Sets the width of the image.
            height: 5.5rem;: Sets the height of the image.
            border-radius: 50%;: Adds border-radius.
        
        .testimonial-item p: This targets the paragraphs within the testimonial items.
        
        CSS properties applied:
            font-style: italic;: Sets the font style to italic.
            margin: 1rem 0;: Adds margin around the paragraph.
![Screenshot 2023-08-28 193233](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/3f003a13-fccd-4041-92a5-6a1105822431)

    .call-me: This class represents the "Call Me" section.

    CSS properties applied:
        background-color: var(--dark-green-background);: Sets the background color.
        display: flex;: Sets the display property to flex.
        padding: 2rem 0rem;: Adds padding to the top and bottom.
        align-items: center;: Aligns items vertically in the center.
        justify-content: center;: Centers content horizontally.
        color: var(--white);: Sets the text color to white.
    
    .call-me .content: This class represents the content within the "Call Me" section.
    
    CSS properties applied:
        width: 45%;: Sets the width of the content.
    
    .call-me .content h2: This targets the heading within the content.
    
    CSS properties applied:
        color: var(--white);: Sets the text color to white.
        margin-top: 1rem;: Adds margin to the top.
        font-size: 1.75rem;: Sets the font size.
    
    .call-me .content p: This targets the paragraphs within the content.
    
    CSS properties applied:
        color: var(--white);: Sets the text color to white.
        margin: 1rem 0;: Adds margin above and below the paragraph.
        line-height: 1.6rem;: Sets the line height.
    
    .content ul: This targets the unordered list within the content.
    
    CSS properties applied:
        line-height: 2rem;: Sets the line height.
        padding: 0.5rem 0;: Adds padding above and below the list.
        list-style: none;: Removes the default list bullet points.
    
    .content ul li:before: This adds custom bullet points to the list items.
    
    CSS properties applied:
        content: "\25a0";: Sets the content to a square bullet point.
        color: var(--light-green);: Sets the color of the bullet point.
        margin-right: 5px;: Adds margin to the right.
        margin-top: -5px;: Adjusts the vertical position.
        font-size: 1rem;: Sets the font size.
    
    .call-form: This class represents the call form container.
    
    CSS properties applied:
        display: flex;: Sets the display property to flex.
        flex-direction: column;: Arranges form elements in a column layout.
        gap: 1rem;: Adds gap between form elements.
    
    .call-form input, select: These target the input fields and select element within the form.
    
    CSS properties applied:
        padding: 1rem;: Adds padding to the input fields and select element.
        border-radius: 5px;: Adds border-radius to the input fields and select element.
        background-color: var(--form-input-background-color);: Sets the background color.
        border: 1px solid var(--form-border-color);: Sets the border properties.
        color: var(--white);: Sets the text color.
        outline: none;: Removes the default outline.
    
    .call-form input:hover, select:hover: These styles are applied when hovering over the input fields and select element.
    
    CSS properties applied:
        border: 1px solid var(--white);: Sets the border properties.
        transition: all 0.2s ease-in;: Adds a smooth transition effect.
    
    .call-form input::placeholder: This targets the placeholder text of the input fields.
    
    CSS properties applied:
        color: var(--white);: Sets the text color of the placeholder.
    
    .call-form .checkbox label: This targets the labels within the checkbox.
    
    CSS properties applied:
        font-family: var(--Opensans);: Sets the font family.
        font-size: 0.8rem;: Sets the font size.
        
    .checkbox label a: This targets the links within the labels.
    
    CSS properties applied:
        color: var(--white);: Sets the link color to white.
    
    .checkbox: This class represents the checkbox container.
    
    CSS properties applied:
        display: flex;: Sets the display property to flex.
        align-items: center;: Aligns items vertically in the center.
        gap: 0.8rem;: Adds gap between items.

        
![Screenshot 2023-08-28 193247](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/05941e0f-ee12-4a6e-870e-12917d7b634b)
![Screenshot 2023-08-28 193257](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/1c8b4709-0ef7-4b06-8038-371bb0caf945)

    .projects: This class represents the "Projects" section.

    CSS properties applied:
        padding: 7rem 0;: Adds padding to the top and bottom of the section.
        text-align: center;: Centers the content horizontally.
    
    .projects .button-list: This class represents the button list in the "Projects" section.
    
    CSS properties applied:
        display: flex;: Displays the buttons in a flex layout.
        flex-wrap: wrap;: Allows wrapping of buttons if the container is too narrow.
        justify-content: center;: Centers the buttons horizontally.
        margin-top: 3rem;: Adds margin at the top.
    
    .projects .button-list button: This targets the buttons within the button list.
    
    CSS properties applied:
        padding: 0.3rem 1.3rem;: Adds padding around the buttons.
        margin: 0 0.3rem;: Adds margin between the buttons.
        border: none;: Removes the button border.
    
    .button-list .not-active: This class targets the inactive buttons within the button list.
    
    CSS properties applied:
        color: var(--light-gray);: Sets the text color for inactive buttons.
        background-color: var(--dark-white);: Sets the background color for inactive buttons.
        border: none;: Removes the button border.
        
    .button-list .not-active:hover: This class targets the hover effect for inactive buttons.
    
    CSS properties applied:
        color: var(--white);: Sets the text color on hover.
        background-color: var(--light-green);: Sets the background color on hover.
        border: none;: Removes the button border on hover.
        
    .project-photos: This class represents the container for project photos.
    
    CSS properties applied:
        margin: 2rem 0;: Adds margin above and below the project photos.
        display: grid;: Sets the display to grid.
        grid-template-areas: ...;: Defines the placement of project photos within the grid.
        justify-content: center;: Centers the content horizontally.
        align-items: center;: Centers the content vertically.
    
    .project-photos .project-image: This class represents each individual project image container.
    
    CSS properties applied:
        max-width: 17.375rem;: Sets the maximum width of the project image container.
        max-height: 16.96rem;: Sets the maximum height of the project image container.
        overflow: hidden;: Hides any overflow content.
    
    .project-image:hover img: This rule applies a scale transformation when hovering over a project image.
    
    CSS properties applied:
        transform: scale(1.2);: Scales the image by a factor of 1.2 on hover.
    
    .project-image img: This targets the project images themselves.
    
    CSS properties applied:
        max-width: 17.375rem;: Sets the maximum width of the project image.
        transition: all 0.2s ease-in-out;: Adds a smooth transition effect on image changes.
    
    .team-members: This class represents the "Team Members" section.
    
    CSS properties applied:
        margin: 10rem 0;: Adds margin to the top and bottom of the section.
        display: flex;: Displays the content in a flex layout.
        flex-direction: column;: Arranges content vertically.
        align-items: center;: Centers content horizontally.
    
    .team-members p: This targets the paragraphs within the "Team Members" section.
    
    CSS properties applied:
        width: 43%;: Sets the width of the paragraph

![Screenshot 2023-08-28 193311](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/f2bab9b8-fb5c-4af2-a359-55732a077c7b)

    .about: This class represents the "About" section.

    CSS properties applied:
        display: flex;: Displays the content in a flex layout.
        justify-content: center;: Centers the content horizontally.
        gap: 5rem;: Adds a gap between the two main content elements.
        align-items: center;: Centers the content vertically.
        padding-top: 6rem;: Adds padding to the top of the section.
    
    .about .about-image: This class represents the container for the image in the "About" section.
    
    CSS properties applied:
        max-width: 32.5rem;: Sets the maximum width of the image container.
        max-height: 22rem;: Sets the maximum height of the image container.
        border-radius: 5px;: Adds a rounded border to the image container.
        overflow: hidden;: Hides any overflow content.
    
    .about-image img: This targets the image within the "About" section.
    
    CSS properties applied:
        max-width: 100%;: Sets the maximum width of the image to fill its container.
    
    .about-content: This class represents the container for the textual content in the "About" section.
    
    CSS properties applied:
        width: 30%;: Sets the width of the content container.
    
    .about-content h2: This targets the heading within the "About" section.
    
    CSS properties applied:
        margin-top: 1rem;: Adds margin at the top of the heading.
        font-size: 1.75rem;: Sets the font size of the heading.
    
    .about-content p: This targets the paragraphs within the "About" section.
    
    CSS properties applied:
        margin: 1rem 0;: Adds margin above and below the paragraphs.
        line-height: 1.6rem;: Sets the line height for the paragraphs.
    
    .about-content ul: This targets the unordered list within the "About" section.
    
    CSS properties applied:
        color: var(--light-gray);: Sets the text color for the list items.
        line-height: 2rem;: Sets the line height for the list items.
        padding: 0.5rem 0;: Adds padding above and below the list.
        list-style: none;: Removes the default list styling.
    
    .about-content ul li:before: This rule adds a square bullet before each list item.
    
    CSS properties applied:
        content: "\25a0";: Sets the bullet character.
        color: var(--light-green);: Sets the color of the bullet.
        margin-right: 5px;: Adds space between the bullet and the text.
    
    .stats-container: This class represents the container for the statistics in the "About" section.
    
    CSS properties applied:
        display: flex;: Displays the statistics in a flex layout.
        flex-wrap: wrap;: Allows statistics to wrap if the container is narrow.
        align-items: center;: Centers the statistics vertically.
        justify-content: space-evenly;: Distributes the statistics evenly along the container.
    
    .stats: This class represents each individual statistic element.
    
    CSS properties applied:
        display: flex;: Displays the statistic content in a flex layout.
        align-items: center;: Centers the content vertically.
        .stats h1: This targets the large number in each statistic element.
    
    CSS properties applied:
        font-size: 3rem;: Sets the font size of the number.
        color: var(--light-green);: Sets the color of the number.
    
    .stats p: This targets the text below the number in each statistic element.
    
    CSS properties applied:
        margin: 0;: Removes margins around the text.
        line-height: 1.3rem;: Sets the line height for the text.

![Screenshot 2023-08-28 193319](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/6275167d-a63f-4dbf-9bec-51bc7d1318dc)

    .contact: This class represents the "Contact" section.

    CSS properties applied:
        padding-top: 10rem;: Adds padding to the top of the section.
        display: flex;: Displays the content in a flex layout.
        align-items: center;: Centers the content vertically.
        justify-content: center;: Centers the content horizontally.
    
    .contact-container: This class represents the container for the contact information.
    
    CSS properties applied:
        display: flex;: Displays the content in a flex layout.
        flex-direction: column;: Stacks the content vertically.
        align-items: flex-start;: Aligns the content to the start of the container.
        max-width: 35%;: Sets the maximum width of the container.
    
    .contact-container h1: This targets the main heading within the contact container.
    
    CSS properties applied:
        margin: 1rem 0;: Adds margin above and below the heading.
        font-size: 1.75rem;: Sets the font size of the heading.
    
    .contact-container p: This targets the paragraphs within the contact container.
    
    CSS properties applied:
        line-height: 1.6rem;: Sets the line height for the paragraphs.
        margin: 0.4rem 0;: Adds margin above and below the paragraphs.
    
    .contact-details: This class represents the container for contact details.
    
    CSS properties applied:
        display: flex;: Displays the contact details in a flex layout.
        align-items: center;: Centers the content vertically.
        flex-wrap: wrap;: Allows contact details to wrap if the container is narrow.
        gap: 0.8rem;: Adds space between contact details.
    
    .contact-icons: This class represents the container for social media icons.
    
    CSS properties applied:
        display: flex;: Displays the social media icons in a flex layout.
        flex-wrap: wrap;: Allows icons to wrap if the container is narrow.
        align-items: center;: Centers the content vertically.
        gap: 0.4rem;: Adds space between icons.
    
    .contact-form: This class represents the contact form container.
    
    CSS properties applied:
        display: flex;: Displays the form in a flex layout.
        flex-direction: column;: Stacks the form elements vertically.
        gap: 1rem;: Adds space between form elements.
    
    .contact-form input, textarea: These rules target input and textarea elements within the contact form.
    
    CSS properties applied:
        padding: 1rem;: Adds padding inside the input and textarea fields.
        border: 1px solid var(--dark-white);: Sets a border for the input and textarea fields.
        border-radius: 5px;: Adds rounded corners to the input and textarea fields.
        outline: none;: Removes the default outline appearance.
        font-family: var(--Opensans);: Sets the font family for the text.
    
    .contact-checkbox: This class represents the checkbox and label for privacy agreement.
    
    CSS properties applied:
        display: flex;: Displays the checkbox and label in a flex layout.
        gap: 0.5rem;: Adds space between the checkbox and label.
        align-items: center;: Centers the content vertically.
        font-family: var(--Opensans);: Sets the font family for the text.
        color: var(--light-gray);: Sets the color of the text.
        font-size: 0.85rem;: Sets the font size of the text.
    
    .contact-checkbox label a: This rule targets the links within the label of the checkbox.
    
    CSS properties applied:
        color: var(--light-gray);: Sets the color of the links.

![Screenshot 2023-08-28 193326](https://github.com/Lok-ii/Major-Project-Aria_Webpage/assets/129180844/751e00c5-1c6f-4b11-a9af-534fcf795de8)

    <footer>: This is the footer section of the website.

    CSS properties applied:
        margin-top: 6rem;: Adds margin to the top of the footer.
        padding: 3rem;: Adds padding within the footer.
        background-color: var(--dark-green-background);: Sets the background color of the footer.
    
    .footer-data: This class represents the container for the footer content.
    
    CSS properties applied:
        display: flex;: Displays the content in a flex layout.
        justify-content: space-evenly;: Distributes the content evenly along the horizontal axis.
        gap: 1rem;: Adds space between the content elements.
    
    .footer-text h3, .footer-text p, .links a, .links h3: These rules target the headings, paragraphs, and links within the footer.
    
    CSS properties applied:
        color: var(--white);: Sets the color of the text.
        font-family: var(--Opensans);: Sets the font family for the text.
    
    .links: This class represents the container for footer links.
    
    CSS properties applied:
        display: flex;: Displays the links in a flex layout.
        flex-direction: column;: Stacks the links vertically.
    .copyright: This class represents the copyright text at the bottom of the footer.
    
    CSS properties applied:
        text-align: center;: Centers the text horizontally.
        color: var(--white);: Sets the color of the text.
    
    .backtotop: This class represents the "Back to Top" button.
    
    CSS properties applied:
        width: 2rem;: Sets the width of the button.
        height: 2rem;: Sets the height of the button.
        background-color: var(--green);: Sets the background color of the button.
        border-radius: 50%;: Makes the button circular by setting border radius to 50%.
        color: var(--white);: Sets the color of the icon.
        text-align: center;: Centers the content horizontally.
        position: fixed;: Fixes the button's position on the screen.
        bottom: 5%;: Sets the distance from the bottom of the screen.
        right: 2%;: Sets the distance from the right edge of the screen.
    
    .backtotop i: This rule targets the icon within the "Back to Top" button.
    
    CSS properties applied:
        padding: 0.25rem 0;: Adds padding to the icon.
        font-size: 1.6rem;: Sets the font size of the icon.
    
    .backtotop:hover: This rule targets the "Back to Top" button when hovered.
    
    CSS properties applied:
        background-image: linear-gradient(var(--green), rgba(0, 0, 0, 0.3));: Applies a gradient background when hovered.
