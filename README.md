# Facebook Login Page

A simple, responsive Facebook-style login page built using HTML and CSS.

## Overview

The page recreates the basic Facebook login interface, featuring a branding section, login form, password recovery link, account creation button, and a page creation message.

## Features

- Facebook branding and introductory text
- Email address or phone number input
- Password input field
- Login button with hover effect
- Forgotten password link
- Create new account button
- Create a Page message
- Responsive layout for smaller screens
- Clean design with rounded corners and subtle shadows

## Technologies Used

- **HTML5** — Structures the webpage.
- **CSS3** — Handles styling, layout, hover effects, and responsiveness.

## Page Structure

```text
Facebook Login Page
├── Container
│   ├── Left Section
│   │   ├── Facebook Heading
│   │   └── Introductory Text
│   │
│   └── Right Section
│       ├── Login Box
│       │   ├── Email / Phone Input
│       │   ├── Password Input
│       │   ├── Login Button
│       │   ├── Forgotten Password Link
│       │   └── Create New Account Button
│       │
│       └── Bottom Text
│           └── Create a Page Message
```

## Design Specifications

| Element | Styling |
|---|---|
| Background | Light gray (`#f0f2f5`) |
| Facebook heading | Blue (`#1877f2`) |
| Login button | Blue (`#1877f2`) |
| Account creation button | Green (`#42b72a`) |
| Login box | White background |
| Input fields | Light gray borders |
| Corners | Rounded |
| Shadow | Subtle box shadow |
| Font | Helvetica, Arial, sans-serif |

## Responsive Design

The page uses a CSS media query for screens with a maximum width of 900px.

On smaller screens:
- The main container changes from a horizontal layout to a vertical layout.
- The introductory text font size is reduced.
- The content is center-aligned.

## Project Setup

1. Create a file named `index.html`.
2. Paste the original HTML and CSS code into the file.
3. Save the file.
4. Open `index.html` in a web browser.

## Important Notes

- This project is a frontend demonstration.
- The login form does not authenticate users because no backend is connected.
- The password recovery link uses a placeholder URL.
- The account creation button has no account-creation functionality.
- For a production application, implement secure authentication, server-side validation, HTTPS, and appropriate security protections.

## License

For educational and practice purposes. This is an independent frontend recreation and is not affiliated with or endorsed by Meta or Facebook.
