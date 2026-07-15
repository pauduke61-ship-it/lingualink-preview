LINGUALINK SITE — WORDPRESS / ELEMENTOR SETUP

1. WHAT IS INCLUDED
- index.html: complete responsive English landing page.
- The design follows the supplied reference: mint hero, dark-green typography, embedded quote form, services, process, and two-column FAQ accordion.
- CSS and JavaScript are self-contained inside index.html. No jQuery and no !important.

2. IMPORTANT: REAL FORM DELIVERY
The HTML preview validates the fields and demonstrates the success state. A static file cannot email submissions. On WordPress, replace the demo <form> with Elementor Pro Form or Contact Form 7 so requests are actually delivered.

3. ELEMENTOR PRO FORM
- Create a two-column hero container.
- Paste/rebuild the left content and add the Form widget on the right.
- Fields: From language, To language, Service type, Email, File upload, Acceptance.
- Under Actions After Submit choose Email.
- Configure recipient, site-domain From address, Reply-To, and message fields.
- Configure SMTP, then send a real test with an attachment.
- Copy styles from index.html into Elementor Site Settings > Custom CSS or a child-theme stylesheet.

4. CONTACT FORM 7 TEMPLATE
<div class="ll-form">
<div class="pair">
<label>From language [select* from-language first_as_label "Select language" "English" "Polish" "Ukrainian" "German" "French"]</label>
<label>To language [select* to-language first_as_label "Select language" "English" "Polish" "Ukrainian" "German" "French"]</label>
</div>
<label>Service type [select* service first_as_label "Choose a service" "Document translation" "Certified translation" "Website localization" "Business translation"]</label>
<label>Email address [email* your-email autocomplete:email placeholder "you@company.com"]</label>
<label>Upload your file [file document limit:10mb filetypes:pdf|doc|docx|jpg|jpeg|png]</label>
[acceptance consent] I agree to the processing of my data for this quote. [/acceptance]
[submit "Request my free quote →"]
</div>

In CF7 Mail settings, map [from-language], [to-language], [service], [your-email], and add [document] to File attachments.

5. FAQ
Use Elementor Nested Accordion with two columns and four questions in each, or paste the native <details> markup from index.html into an HTML widget. The native version is keyboard accessible and needs no library.

6. BEFORE LAUNCH
- Replace demo email and phone.
- Confirm privacy/consent wording.
- Test desktop, tablet, and 390 px mobile.
- Test keyboard navigation and file-size validation.
- Send a real submission and confirm email + attachment delivery.
- Clear Elementor and caching-plugin caches.
