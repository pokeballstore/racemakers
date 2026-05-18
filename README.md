[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Fwra5Fna)
# Project Instructions
# Project Plan — Reusable Event Registration Website

## 1. Project Idea
The goal of this project is to create a reusable website where different types of activities can be presented and people can sign up to participate.

The website will not be built for a specific event.  
Instead, it will act as a template where only the event information needs to be changed.

Possible uses:
- Competitions
- Challenges
- Group activities
- Meetings
- Contests

---

## 2. Purpose
The website should allow an organizer to:

- Present an event
- Provide important information
- Explain rules or requirements
- Allow participants to register
- Show a participant list

The main focus is a clear and logical HTML structure that is easy to understand and reuse.

---

## 3. Pages Overview

### Home Page — `index.html`
Gives a quick overview of the event.

Content:
- Event title
- Short introduction
- Date and location
- Organizer information
- Navigation links to other pages

---

### Event Details — `details.html`
Provides deeper information about the activity.

Content:
- Full description
- Rules
- Requirements
- Schedule

---

### Signup Page — `signup.html`
Allows a user to register for the event.

Form fields:
- Name
- Contact information
- Optional comment
- Submit button

---

### Participants Page — `participants.html`
Displays participants.

Content:
- List of participants
- Optional waiting list

---

## 4. Reusability Plan
The website layout should never need to be changed.

Only the text content inside sections will be edited:

- Event name
- Description
- Date
- Location
- Rules

This makes the webpage reusable for many different activities without rewriting the code.

---

## 5. Technical Plan
The project will focus on simple and clear HTML.

Planned structure:
- Headings for hierarchy
- Paragraphs for text
- Div elements for grouping content
- Links for navigation between pages
- A basic form for registration

No advanced functionality is required.  
If dynamic features are added in the future, they will be part of a separate project.

---

## 6. File Structure

project/
│── index.html
│── details.html
│── signup.html
│── participants.html


---

## 7. Design Principles
- Simple structure
- Clear hierarchy of information
- Easy to read code
- Easy to modify content
- Consistent layout between pages

---

## 8. Short Project Description
This project is a reusable event registration website template where activities can be presented and users can sign up by changing only the event content while keeping the same page structure.

---

## 9. Inspiration and source material 
 - https://www.udemy.com/course/learn-html-and-css-in-7-days-web-developer-bootcamp/?couponCode=CODING2GO Flexbix and Css
 - https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design
 - It’s crucial for creating visually balanced buttons. So now the question is, How much padding is right? As a general rule, use 1x padding on the top and bottom, and 2x padding on left and right — For example, 16px vertically and 32px horizontally. https://medium.com/%40santoshsonnad01/designing-buttons-c9b910e09704
  - Smooth scroll https://www.w3schools.com/howto/howto_css_smooth_scroll.asp#section1
  - Implement netify https://docs.netlify.com/start/quickstarts/deploy-from-repository/ https://docs.netlify.com/start/quickstarts/deploy-from-repository/

  ## 10. Notes and ideas on the way.
  - I'll try to make the navigation to be at the bottom all the time so when you are on a phone it is easier to navigate. 