# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**

- A **Flex container** is a parent element that establishes a flex formatting content for its immediate children, which become **flex items**
    - To turn an element into a flex container, you apply the css property: `display: flex` or `display: inline-flex`

- A **Flex item** is a child element of the flex container located inside of the **flex container**.

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**
- **Main Axis** is the direction that flex items flow in
- Cross Axis is the direction perpendicular to the main axis.
- **Justify-content** defines the spacing along the main axis
- **Align-items** defines the alignment of elements along the cross axis.

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**
- Flexbox is used for standard website header where you want the logo on the far right and nav links to the far right. Flexbox handles the dynamic spacing between items and pushes the elements to opposite ends using a simple

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**
- The `fr` stands for fraction and it represents the fraction of available free space in a container.
- `grid-template-columns: 1fr 2 fr 1 fr` would create three columns. The first and third columns would only take up half the amount of available space that the middle column would. Leaving the middle column to be twice as wide as the first and third.

## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**
- A media query is a css feature that allows you to apply styles strictly based on specfic device characteristics. They are important for responsive web design because they allow your layout adapt to to different viewports, providing a seamless user experience across phones, tablets, and desktops.

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**
- **mobile-first- design** is a responsive design strategy where developers begin their project by creating the layout for the smallest screens first, and then add complexity or new features using media queries as the screen size increases.
- A benefit is improved loading speed and performance for mobile users, since they only load the necessary core styles rather than heavy desktop code.