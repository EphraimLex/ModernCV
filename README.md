# Modern CV Web Page

A responsive, one-page CV website created using HTML5 and CSS3.
It presents my professional background, education, technical skills,
and software development projects.

This project is part of my software development training and provides
a foundation for a future personal portfolio website.

## Features

- Professional profile and summary
- Skills grouped into three categories
- Professional experience and education
- Software development project descriptions
- Contact section with a placeholder email address
- Navigation links to sections on the page
- Back-to-top link
- Responsive desktop and mobile layouts

## Technologies

- HTML5 for content and semantic structure
- CSS3 for styling and responsive layouts
- Flexbox for navigation
- CSS Grid for the Skills and Projects sections

No frameworks or JavaScript are required to run this version.

## Project Files

- `index.html` — page content and structure
- `style.css` — styling and responsive layout
- `README.md` — project documentation

## How to Run

1. Download or clone the repository.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in a web browser.

No installation, dependencies, or build steps are required.

To edit the website, open the project folder in Visual Studio Code.
Save your changes and refresh the browser to see the result.

## Planning and Design

The page structure was planned using desktop and mobile wireframes
before implementation.

The design uses:

- A centred content area with a maximum width of 1100px
- Arial typography for readability
- A light page background and light-grey sections
- Dark-green headings and links
- Consistent spacing and rounded section corners

On wider screens, Skills uses three columns and Projects uses two.
At viewport widths of 768px or less, both sections switch to one
column. Navigation links wrap when space is limited.

## Code Organisation

HTML and CSS are kept in separate files to separate content from
presentation.

Semantic elements such as `header`, `nav`, `main`, `section`,
`article`, and `footer` organise the page.

Reusable classes define shared layouts. Section IDs provide
navigation targets and allow section-specific styling.

This structure makes it easier to add content and develop the
website into a personal portfolio.

## Testing

The following manual checks were completed:

- Checked the layout at desktop and narrow browser widths.
- Confirmed that Skills and Projects stack into one column
  on smaller screens.
- Checked navigation links.
- Checked keyboard navigation.

## Contact Information

The email address is a placeholder for this educational project.
No home address or personal phone number is included.

## Deployment

The website is published using GitHub Pages.

- GitHub repository: https://github.com/EphraimLex/ModernCV
- Live website: https://ephraimlex.github.io/ModernCV/