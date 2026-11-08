# Personal Portfolio

This is a static portfolio built with HTML, CSS, and browser-side JavaScript. It has no backend service or database; the site can be hosted on any static hosting provider.

The navbar language button switches the portfolio between French and English. The selected language is remembered in the visitor's browser using local storage; French is the default when no preference has been saved.

Project cards tilt and lift as visitors move their pointer over them. A fixed music player includes a live frequency equalizer and plays an optional, original cinematic pop loop with a dramatic melody, chords, bass, and beat. Audio is synthesized in the browser and starts only after the visitor clicks play.

The contact section includes an appointment-request form. Because this portfolio is static, submitting opens the visitor's email app with the request pre-addressed to `mohamedyoussoufkeita4@gmail.com`; visitors must send the email themselves, and appointments are not automatically confirmed.

## Personalize the portfolio

Open `index.html` and edit the `portfolioData` object in the script near the bottom of the file. Project titles, organizations, descriptions, image paths, technologies, and optional project links are in `portfolioData.projects`. Certification details and optional certificate image paths are in `portfolioData.certifications`. The portrait path is `portfolioData.images.profile`, and the LinkedIn, GitHub, and Hashnode destinations are in `portfolioData.links` and `hashnodePublicationUrl`. The publication list and other page text are editable in the HTML markup.

## Add certificate images

Put image files in `assets/certificates/`. Then set the matching `image` value in `portfolioData.certifications` to a relative path, for example `assets/certificates/web-security.jpg`. Supported image formats are those browsers display, such as JPG, PNG, and WebP. Leave `image` empty to show a certificate card without an image. Project images can also use local paths or URLs in their project entries. Other page text is directly editable in the HTML markup.

## Publications and static hosting

The Hashnode profile link is configured in `portfolioData.hashnodePublicationUrl`; publication titles and dates are in the Writing section markup. This site is static and has no backend or upload service; adding an image means placing its file in the repository and referencing its path in the data.
