# Health Monitoring and Wellness Website

A simple, clean, and beginner-friendly website that shares general
health information and helps visitors explore healthcare options and
plan a doctor appointment.

> **Important:** This project is an informational website demo. It does
> diagnose only viral diseases, provide personal medical advice, verify
> hospitals, or book confirmed appointments.

------------------------------------------------------------------------

## 1. About the Project

The **Health Monitoring and Wellness** website is designed to make basic
health information easier to explore. It has a calm layout, simple
navigation, and separate sections for health guidance, hospital
examples, and an appointment request form.

The website is made with two main files:

-   `index.html` --- contains the page structure and content.
-   `styles.css` --- controls the colours, fonts, spacing, layout,
    cards, and responsive design.

The main idea is to give visitors a clear starting point when they want
to read general health information or learn how they might contact a
healthcare provider.

## 2. Main Goals

-   Present common health topics in simple language.
-   Show general adult health reference information.
-   Make important safety guidance easy to notice.
-   Provide sample public and private hospital listings.
-   Give visitors a basic appointment request form.
-   Keep the website easy to navigate on desktop and mobile screens.

## 3. Website Sections

### 3.1 Header and Navigation

The top area contains the website name and navigation links:

-   **Health guide** --- moves to the health information section.
-   **Find care** --- moves to the hospital directory section.
-   **Appointments** --- moves to the appointment form.
-   **Book a visit** --- a call-to-action link that also moves to the
    appointment section.

The navigation uses HTML anchor links. For example, a link to `#guide`
moves the visitor to the element whose ID is `guide`.

### 3.2 Hero / Home Section

The first main section welcomes visitors with the message:

**"Your health, in good hands."**

It briefly explains the purpose of the website and provides two links:

-   **Explore care**
-   **Browse health guide**

The right side contains a doctor illustration created with HTML elements
and CSS shapes. It is not an uploaded photograph.

### 3.3 Quick Links

Three shortcut cards help visitors reach important sections:

1.  **Health guide** --- everyday health information.
2.  **Nearby hospitals** --- sample public and private care listings.
3.  **Doctor visits** --- the appointment planning form.

These cards are also internal links, so visitors can jump directly to
the relevant part of the same page.

### 3.4 Health Guide

The health guide introduces six common viral illnesses:

  -----------------------------------------------------------------------
  Topic                               What the page briefly mentions
  ----------------------------------- -----------------------------------
  Flu (influenza)                     Fever, body aches, tiredness,
                                      headache, and cough may occur.

  COVID-19                            Possible symptoms include cough,
                                      sore throat, fever, and fatigue.

  Dengue                              Fever, aches, headache, nausea, or
                                      rash may occur.

  Common cold                         Runny or stuffy nose, sneezing, and
                                      sore throat are common symptoms.

  Viral stomach bug                   Vomiting or diarrhoea can lead to
                                      dehydration.

  RSV                                 It can resemble a cold and may be
                                      more serious for some people.
  -----------------------------------------------------------------------

Each illness card includes a link to a related page from the **Centers
for Disease Control and Prevention (CDC)**.

The website also explains that symptoms can overlap. A visitor should
not use this page to decide exactly which illness they have. A qualified
healthcare professional may need to examine or test them.

### 3.5 Simple Health Checks

A table presents general adult reference information for four checks:

-   Blood pressure
-   Body temperature
-   Resting pulse
-   Oxygen level (if measured)

The table also gives examples of situations in which a person should
contact a healthcare professional or seek urgent help.

These are general references only. Age, pregnancy, medicines, altitude,
existing health conditions, and a person's usual readings can change
what is appropriate. The values on the page are not a personal diagnosis
or a replacement for medical advice.

### 3.6 Safety Information

Two notice areas highlight important points.

**Know when it may be serious**

The page lists examples of serious symptoms that may need emergency
help, such as severe breathing difficulty, chest pain, fainting,
confusion, seizure, severe dehydration, heavy bleeding, or rapidly
worsening symptoms. It also includes warning signs associated with
possible dengue.

**Medicine safety comes first**

The page explains that there is no single medicine that is right for
every viral fever. Visitors are advised to ask a qualified clinician or
pharmacist about medicines. It also includes a warning about aspirin and
ibuprofen when dengue is possible.

Please use a qualified medical professional for personal advice. In an
emergency, contact the local emergency service.

### 3.7 Find Care / Hospital Directory

This section is intended to help visitors explore different kinds of
healthcare providers.

It currently displays two **sample listings**:

-   **District General Hospital** --- shown as a government hospital
    example.
-   **City Care Medical Centre** --- shown as a private hospital
    example.

These names and cards are placeholders for demonstration. They are not
verified real hospital listings. The page does not currently search for
the visitor's location or retrieve live hospital information.

Before visiting a real healthcare facility, confirm its address,
services, hours, availability, and costs directly with that facility.

### 3.8 Appointment Section

The appointment area explains a simple three-step process:

1.  Pick a care type.
2.  Find a local provider.
3.  Confirm directly with the provider.

The form contains these fields:

  -----------------------------------------------------------------------
  Field                               Purpose
  ----------------------------------- -----------------------------------
  Your name                           Enter the visitor's name.

  Type of visit                       Choose general consultation,
                                      follow-up, specialist consultation,
                                      or not sure yet.

  Preferred date                      Select a preferred date.

  Your city or area                   Enter a location.
  -----------------------------------------------------------------------

The name field is marked as required. The form uses HTML form controls
such as text input, date input, and a select menu.

**Current form limitation:** The form's action is set to
`mailto:appointments@example.com`. This is a demo email address, not a
connected appointment system. The form does not confirm a booking or
check a doctor's availability. A real deployment needs a proper backend
or a verified appointment service, along with suitable privacy and
security measures.

### 3.9 Footer

The footer contains:

-   The website name.
-   A short closing message.
-   A link to return to the top of the page.
-   A reminder that the website provides general information and is not
    a substitute for professional medical advice.

------------------------------------------------------------------------

## 4. Technologies Used

### HTML5

HTML is used to create the structure and content of the website.

Examples from `index.html` include:

-   `<header>` for the top navigation area.
-   `<nav>` for navigation links.
-   `<main>` for the main page content.
-   `<section>` for separate website sections.
-   `<article>` for individual illness and hospital cards.
-   `<table>` for health reference information.
-   `<form>`, `<label>`, `<input>`, and `<select>` for the appointment
    form.
-   `<footer>` for the bottom area of the website.

The HTML also uses IDs such as `home`, `guide`, `hospitals`, and
`appointment` so that internal links can reach the correct section.

### CSS3

CSS is used to control how the website looks.

The `styles.css` file contains:

-   Colour variables.
-   Font settings.
-   Page widths and spacing.
-   Header and navigation styles.
-   Hero section layout.
-   Buttons and links.
-   Health and hospital cards.
-   Tables and safety notices.
-   Appointment form styling.
-   Footer styling.
-   Responsive rules for smaller screens.

### Google Fonts

The page imports two font families from Google Fonts:

-   **DM Sans** --- used for much of the general page text.
-   **Manrope** --- used for headings and some title-like text.

Georgia is also included as a fallback serif font for selected italic
heading words.

### JavaScript

The current project does **not** include a separate JavaScript file and
does not use custom JavaScript interactions. The navigation uses HTML
links, and the appointment form uses standard HTML form controls.

------------------------------------------------------------------------

## 5. Design and Colour Theme

The website uses a soft, calm visual style.

Some of the main colours are stored as CSS variables in `:root`:

  Variable    Colour value   Use
  ----------- -------------- ---------------------------------
  `--ink`     `#203a36`      Main dark text and dark buttons
  `--muted`   `#697d77`      Supporting text
  `--green`   `#e8f1ed`      Light green theme colour
  `--mint`    `#d8e9df`      Mint accent
  `--coral`   `#f4a78f`      Warm accent
  `--cream`   `#fbfaf6`      Cream background option
  `--line`    `#e7e9e2`      Borders and separators

The design uses rounded cards, light backgrounds, clear spacing, and
green accents to create a gentle healthcare theme.

------------------------------------------------------------------------

## 6. Responsive Design

The website includes CSS media queries so that the layout can adapt to
different screen sizes.

### At widths up to 850 pixels

The page reduces some spacing and adjusts the hero illustration and
hospital cards.

### At widths up to 640 pixels

The layout changes for smaller screens:

-   The main navigation links are hidden.
-   The hero section becomes a single-column layout.
-   Quick links are stacked vertically.
-   Health cards are displayed in one column.
-   Hospital cards are stacked.
-   The appointment section becomes one column.
-   Footer content can wrap onto multiple lines.
-   The health reference table can be scrolled horizontally.

This makes the page more suitable for phones and smaller screens. The
current mobile header hides the navigation links, so a future version
could add a mobile menu button.

------------------------------------------------------------------------

## 7. Project File Structure

Keep both files in the same folder:

``` text
health-monitoring-website/
│
├── index.html
├── styles.css
└── README.md
```

The HTML file loads the CSS file using:

``` html
<link rel="stylesheet" href="styles.css">
```

If the CSS file is renamed or moved to another folder, this link must be
updated.

------------------------------------------------------------------------

## 8. How to Run the Website

No special software or installation is required for the basic version.

1.  Create a folder named `health-monitoring-website`.
2.  Put `index.html` inside the folder.
3.  Put `styles.css` in the same folder.
4.  Open the folder.
5.  Double-click `index.html`.
6.  The website should open in your default browser.

You can also open the folder in Visual Studio Code and use a local
preview extension if you prefer.

**Internet note:** The page itself is made from local HTML and CSS
files, but Google Fonts and the external CDC links need an internet
connection to load their online resources.

------------------------------------------------------------------------

## 9. How to Edit the Website

### Change the website name

Open `index.html` and find the brand text inside the header and footer.
Edit the words there.

### Change the main heading

Find the `<h1>` element in the hero section and replace its text.

### Change colours

Open `styles.css` and edit the values inside the `:root` block. For
example:

``` css
:root {
  --ink: #203a36;
  --muted: #697d77;
  --green: #e8f1ed;
}
```

### Change health card content

In `index.html`, find the section with `id="guide"`. Each illness is
written inside a `<article class="guide-card">` element. Edit its
heading, paragraph, and reference link carefully.

### Change sample hospital cards

Find the section with `id="hospitals"`. The current hospital names are
examples. Replace them only with accurate, verified information if you
build a real directory.

### Change the appointment form

Find the `<form>` element inside the appointment section. You can edit
the labels and options. To receive real appointment requests, connect
the form to a secure backend or a trusted form service instead of
relying on the current demo email action.

------------------------------------------------------------------------

## 10. Accessibility and Usability Features

The current HTML includes several helpful basics:

-   A viewport meta tag for mobile layouts.
-   A page description in the document head.
-   Navigation with an accessible label.
-   Labels connected to appointment form fields using `for` and `id`.
-   A text alternative for the doctor illustration through `role="img"`
    and `aria-label`.
-   Clear section headings.
-   Links with descriptive text.
-   A required name field in the appointment form.

These are useful foundations. A future version should also test keyboard
navigation, colour contrast, screen-reader behaviour, and visible focus
states.

------------------------------------------------------------------------

## 11. Current Features and Limitations

  Feature                                Current status
  -------------------------------------- -----------------------------------------
  Home page and navigation               Available
  Health information cards               Available
  External CDC reference links           Available
  General adult health reference table   Available
  Safety notices                         Available
  Sample hospital cards                  Available; demo content only
  Automatic location detection           Not implemented
  Live hospital search                   Not implemented
  Doctor profiles                        Not implemented
  Real appointment booking               Not implemented
  Appointment database                   Not implemented
  User login or registration             Not implemented
  JavaScript functionality               No custom JavaScript currently included

This table describes the uploaded version of the project. Do not assume
that a displayed sample card or form means a real service is connected.

------------------------------------------------------------------------

## 12. Ideas for Future Improvements

The following are possible future features. They are **not included in
the current version**.

1.  Add a working mobile navigation menu.
2.  Add a search box for health topics.
3.  Add verified hospital names, addresses, phone numbers, and map
    links.
4.  Add filters for government and private hospitals.
5.  Connect a location-based directory using a suitable,
    permission-based service.
6.  Add doctor profiles and verified contact details.
7.  Connect the appointment form to a secure backend.
8.  Show a clear success or error message after a form submission.
9.  Add privacy information and collect only the information that is
    genuinely needed.
10. Improve accessibility and test the website on more devices and
    browsers.
11. Add a clear emergency information area with locally appropriate
    emergency contacts.
12. Review health content regularly and keep its medical references up
    to date.

------------------------------------------------------------------------

## 13. Health and Privacy Disclaimer

This website is an educational and informational demo. It is not a
medical device and does not provide diagnosis, treatment, or
personalised medical advice.

-   Do not use the website to diagnose yourself or another person.
-   Contact a qualified healthcare professional for personal medical
    questions.
-   Seek emergency help when symptoms may be serious.
-   Confirm hospital details directly with the hospital.
-   Do not enter sensitive personal or medical information into the
    current demo form. It is not connected to a secure
    appointment-management system.

If this project is developed into a real healthcare service, its medical
content, privacy practices, data security, and booking process should be
reviewed by appropriate professionals.

------------------------------------------------------------------------

## 14. Credits and References

The health guide in the HTML file links to these public information
sources:

-   [CDC --- Flu symptoms and warning
    signs](https://www.cdc.gov/flu/signs-symptoms/)
-   [CDC --- COVID-19
    symptoms](https://www.cdc.gov/covid/signs-symptoms/)
-   [CDC --- Dengue symptoms and warning
    signs](https://www.cdc.gov/dengue/signs-symptoms/)
-   [CDC --- Common cold
    treatment](https://www.cdc.gov/common-cold/treatment/)
-   [CDC --- Norovirus overview](https://www.cdc.gov/norovirus/about/)
-   [CDC --- RSV symptoms](https://www.cdc.gov/rsv/symptoms/)
-   [American Heart Association --- Understanding blood pressure
    readings](https://www.heart.org/en/health-topics/high-blood-pressure/understanding-blood-pressure-readings)
-   [MedlinePlus ---
    Fever](https://medlineplus.gov/ency/article/003090.htm)
-   [MedlinePlus --- Vital
    signs](https://www.medlineplus.gov/ency/article/002341.htm)
-   [NHS --- COVID-19 home oxygen monitoring
    guidance](https://www.england.nhs.uk/coronavirus/documents/covid-19-standard-operating-procedure-covid-oximetry-home/)
-   [CDC --- Dengue clinical
    care](https://www.cdc.gov/dengue/hcp/clinical-care/)

Fonts are loaded from [Google Fonts](https://fonts.google.com/).

------------------------------------------------------------------------

## 15. Conclusion

The **Health Monitoring and Wellness** website is a simple front-end
project built with HTML and CSS. It brings together general health
guidance, basic health reference information, sample hospital cards, and
an appointment request form in one responsive page.

The project is a good starting point for learning how to structure a
website, connect sections with navigation links, style content with CSS,
build cards and tables, and create a basic HTML form. More advanced
features---such as live hospital search, secure data storage, and real
appointment booking---would need additional development.

**Project name:** Health Monitoring and Wellness\
**Main files:** `index.html` and `styles.css`\
**Technologies:** HTML5 and CSS3\
**Project type:** Responsive front-end website
