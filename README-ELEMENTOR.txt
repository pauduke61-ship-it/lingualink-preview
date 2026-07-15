LINGUALINK — CORRECTED ELEMENTOR MODIFICATION

This package contains only the two requested page changes, not a replacement website:
1) Hero: keep the existing left-side message and replace the current right-side image with the order form.
2) FAQ: add a two-column accordion immediately below the relevant homepage content.

FILES
- lingualink-v2.html — responsive working visual prototype.
- lingualink-v2-preview.png — hero preview.
- lingualink-v2-faq-preview.png — FAQ preview.

ELEMENTOR INTEGRATION
Hero:
- Open the existing first section in Elementor.
- Keep the current left column, typography, button, and spacing.
- Remove only the image/widget from the right column.
- Add Elementor Pro Form to the right column.
- Fields: Translate from, Translate to, Number of pages, Approx. word count, Email, File upload.
- Set Actions After Submit > Email and configure recipient, Reply-To, and attachment delivery.
- Apply the green card styles from the .card and .form rules in lingualink-v2.html.

FAQ:
- Add a new full-width section and class faq.
- Add heading, intro, and a two-column inner container.
- Place four Elementor Nested Accordion items in each column.
- Copy the questions and answers from lingualink-v2.html.
- On mobile, use one column.

CONTACT FORM 7 ALTERNATIVE
Use fields equivalent to:
[select* from first_as_label "Choose language" "English" "Polish" "Ukrainian" "German"]
[select* to first_as_label "Choose language" "English" "Polish" "Ukrainian" "German"]
[number pages min:1 placeholder "e.g. 5"]
[number words min:1 placeholder "e.g. 1200"]
[email* email placeholder "you@email.com"]
[file document limit:10mb filetypes:pdf|doc|docx|jpg|jpeg|png]
[submit "Get Your Translation Now →"]

IMPORTANT
The standalone HTML simulates the success state for presentation. Real email submission must be handled by Elementor Pro Form or Contact Form 7. Configure SMTP and test one real submission with an attachment before launch.
