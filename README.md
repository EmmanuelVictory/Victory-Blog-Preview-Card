#Blog Preview Card Challenge

This project is a solution to one of the Frontend Mentor beginner challenges recreating a blog preview card using only HTML and CSS.

It may look small, but for me, it was a huge milestone in my frontend journey. Every single line of code here was written by me as part of my practice and I’m very excited to share what I learned while building this.



 ##Technologies Used
	•	HTML – for the structure of the card.
	•	CSS – for styling, layout, colors, and positioning.



##Features I Implemented

1. Card Container (div)

I created a div to act as the main container of the card. Inside it, all the elements (image, button, texts, avatar) are placed.
	•	I added a white background (background-color: hsl(0, 0%, 100%)) to make it stand out.
	•	I used border-radius to give it soft curved edges.
	•	I added a border on the right and bottom (border-right and border-bottom) in black to make the card pop and give it a slightly 3D effect.
	•	I centered it on the page with margin: auto and some margin-top + margin-bottom.

This was a great exercise for me in creating clean, centered layouts.



2. Top Image (img.lo)

I added the illustration image at the top of the card with its own class .lo.
	•	I gave it rounded corners using border-radius.
	•	I positioned it slightly away from the card edges with relative positioning (left: 35px, top: 30px).

This taught me how relative positioning can move an element from its normal position inside a container.



3. Button (Learning)

The button was styled to look bold and clickable:
	•	Bright yellow background (hsl(47, 88%, 63%)) for contrast.
	•	I removed default borders with border: none.
	•	I made it bold with font-weight: bolder.
	•	I used padding to give it breathing space.
	•	I positioned it neatly using left: 36px and margin-top.

This step helped me understand how buttons can be fully customized beyond the browser’s default styles.



4. Text Elements (p, h1, h3)

I styled three different text sections:
	•	Date (p) – smaller text in gray using color: hsl(0, 0%, 42%).
	•	Title (h1) – bold and larger with font-size: 1.8rem and font-weight: bolder.
	•	Description (h3) – muted gray with line breaks (<br />) to mimic the design layout.

This part really strengthened my skills in typography and how to use different heading levels effectively.



5. Avatar and Name (img.va + span)

At the bottom, I added the profile avatar and author’s name.
	•	The avatar image (.va) is aligned left using relative positioning.
	•	The author’s name is wrapped in a span, bolded, and placed beside the avatar using positioning (top: -50px, padding-left: 45px).

This gave me practice in aligning images with text inside a card.



##💡 What I Learned

While building this project, I learned a lot of small but powerful CSS and HTML concepts:
	1.	How to create a card layout using div as a container.
	2.	The importance of border-radius.
	3.	How to use relative positioning to move elements slightly without breaking the flow.
	4.	How to style buttons from scratch instead of relying on default styles.
	5.	Using colors in HSL format instead of HEX or RGB – which is more intuitive for adjusting hue, saturation, and lightness.
	6.	The difference between headings and paragraphs in structuring content.
	7.	How to align an avatar beside text using positioning and spacing.



#Gratitude

I’m really grateful to Frontend Mentor for providing this challenge because it gave me the chance to practice real-world UI component.
This project has boosted my confidence with basic layouts and shown me how even simple HTML and CSS can create beautiful, professional-looking designs.

Every mistake I corrected here made me better, and I’m proud of how the final design turned out.