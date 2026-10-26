PDFify Online — GitHub Pages Website Package (CV feature removed)

FILES
- index.html: main PDFify Online tools page.
- about.html, contact.html, faq.html, how-to-use.html: site information pages.
- privacy-policy.html and terms.html: policy pages.
- CNAME: custom domain mapping for pdfify.online. Keep this file in the repository root.
- firebase-config.js, firestore.rules, storage.rules, FIREBASE-SETUP.md: optional Firebase account setup materials. Accounts/cloud saving will not work until your own Firebase project is configured and tested.
- PAYMENT-LINKS-SETUP.txt: notes about optional invoice payment links.
- sitemap.xml and robots.txt: search-engine discovery files.

The Create CV / Resume feature and its page have been removed from this package. Other existing PDF, business and study tools remain in the website.

GITHUB PAGES UPLOAD
1. Download and extract the ZIP.
2. Open your website's GitHub repository.
3. Upload the CONTENTS of this extracted folder to the repository root, not the containing folder itself.
4. Keep the existing CNAME file (pdfify.online). If GitHub already has a correctly configured firebase-config.js, do not overwrite it with a placeholder.
5. Commit the changes and open https://pdfify.online/ after GitHub Pages finishes publishing.

NOTES
- This is a static website. Features that require Firebase remain inactive until Firebase Authentication, Firestore, Storage and security rules are configured in your own project.
- Payment buttons open the account owner's configured payment links; they do not independently verify payment completion.
- Browser tools can be limited by browser capabilities, file size and available memory.
