Types Of CSS:

1. Inline CSS
    Applied background color to the <body> element:
    <body style="background-color: #e8f0fe;">

2. Internal CSS
    Inside <style> tag in the `<head>` section for:
    .bio styling
    Group selector for `h1, h2` to style headings
    Descendant selector .contact p to space contact section

3. External CSS
   Linked via style.css
   Contains most layout, spacing, card design, hover effects, and button styles

Selectors Used:

1. Element Selectors
   body, ul, a[href] used for global styling and links

2. ID Selector
   #profile-pic styles the profile image (size, border-radius, border)

3. Class Selectors
   .bio styles the short bio text
   .card styles the main profile card container (background, shadow, padding)
   .btn styles contact buttons (color, padding, hover effect)

4. Group Selector
   h1, h2 sets consistent font and color for headings

5. Descendant Selector
   .contact p applies spacing specifically to paragraphs inside the contact section

6. Attribute Selector
   a[href] styles anchor tags that have an href attribute