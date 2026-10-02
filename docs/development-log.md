# Development Log – Modern CV Web Page

## 28 September 2026 – Planning

### Work completed
- Reviewed the project requirements.
- Chose a simple, professional, one-page CV.
- Planned the main sections: profile, summary, skills,
  experience, education, projects, and contact.
- Decided to document planning, design, implementation,
  and testing for the class presentation.

### Design decision
Keep the structure easy to extend because this CV will
provide a foundation for a future personal portfolio.

## 29 September 2026 – Wireframes and HTML

### Work completed
- Prepared desktop and mobile wireframes.
- Planned a centred desktop layout with Skills in three
  columns and Projects in two columns.
- Planned a single-column layout for smaller screens.
- Built and reviewed the HTML structure.

### Learning
- Reviewed HTML elements, tags, and attributes.
- Learned how the external stylesheet is linked.
- Reviewed the purpose of the page title and aria-label.
- Learned how navigation links use section IDs.

## 30 September 2026 – Content Refinement

### Work completed
- Refined the education section.
- Removed the standalone Energy Engineering courses.
- Removed the degree-equivalence explanation.
- Kept the education content focused and concise.

## 1 October 2026 – Styling and Layout

### Work completed
- Applied Arial typography and dark-green accents.
- Added light-grey section backgrounds.
- Used Flexbox for navigation and CSS Grid for Skills
  and Projects.
- Improved spacing within Education and Projects.
- Grouped the experience role, company, location, and dates.
- Styled the Contact section and footer.
- Added CSS comments explaining the main styling rules.

### Design decisions
- Limit the content width to 1100px for readability.
- Use consistent spacing and rounded section corners.
- Allow navigation links to wrap on smaller screens.

### Testing
- Checked the page layout.
- Checked navigation links.
- Checked keyboard navigation.

## 2 October 2026 – Review, Responsiveness, and Documentation

### Work completed
- Reviewed the assignment requirements and confirmed that
  JavaScript is optional.
- Manually reviewed the HTML structure and CSS rules.
- Corrected “Professionl Summary” to “Professional Summary”.
- Improved the grammar of the second Professional Experience bullet.
- Removed the unused `.education-dates` CSS rule.
- Updated the responsive rule to include both Skills and Projects.
- Created `README.md` with project information, setup instructions,
  design decisions, and testing results.
- Updated `development-log.md` to record progress.

### Problem and solution
The media query initially changed only the Skills section
to one column. Projects remained in two columns.

Added both `.skills-grid` and `.projects-grid` to the media
query so they use one column at viewport widths of
768px or less.

### Review and testing
- Manually reviewed HTML nesting, closing tags, and heading hierarchy.
- Checked that section IDs are unique and navigation targets match.
- Checked that CSS selectors match the HTML.
- Reviewed CSS layout and spacing rules.
- Saved the CSS, refreshed the browser, and narrowed the window.
- Confirmed that Skills and Projects both stack into one column.
- Confirmed that both HTML text corrections have been applied.

Testing consisted of manual code review and browser checks.
Automated validation was not performed and is not planned
for this version.

### Repository and publication
- Created the public ModernCV repository through VS Code.
- Uploaded the website files and the docs folder.
- Configured GitHub Pages to deploy from the main branch
  and the repository root.
- Published the website online.
- Checked the live website’s styling and navigation.
- Added the repository and live website links to README.md.

### Project links
- GitHub repository: https://github.com/EphraimLex/ModernCV
- Live website: https://ephraimlex.github.io/ModernCV/

### Current status
The website is implemented, tested manually, and published.
The public repository includes the code and project documentation.

