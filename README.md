# Single Price Grid Component (Vanilla Web)

A clean, responsive Single Price Grid component built using vanilla HTML and CSS.

![Single Price Grid Preview](./images/desktop-design.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS for a lightweight, dependency-free component.
- **Responsive Design:** Mobile-first approach with optimized layouts for both mobile and desktop viewports (desktop styles at `992px`).
- **Polished Visuals:** Thoughtful use of CSS custom properties, shadows, and layout to create a modern pricing card.
- **Accessible & Semantic:** Uses semantic HTML structure to improve accessibility and SEO.
- **Easy to Integrate:** Drop the `index.html`, `style.css`, and the `images/` folder into any project—no build step required.
- **Customizable:** Clear class names and CSS variables make it simple to change colors, typography, spacing, and copy.

## Prerequisites & Dependencies

- A web browser (Chrome, Firefox, Safari, Edge) to view the component.
- A text editor or IDE to edit `index.html` and `style.css` (e.g., VS Code).
- (Optional) A local server for consistent asset loading (VS Code Live Server).

## Installation & Setup Instructions

1. **Clone or download the repository** (or copy the project folder locally):

```bash
git clone https://github.com/syntaxSangoma/single-price-grid-component-vanilla-10.git
```

```bash
cd single-price-grid-component-vanilla-10
```

2. **Open the project** in your editor and open `index.html` in the browser:

- Double-click `index.html` or open it from your editor.
- Or serve the folder using a simple local server (recommended for consistent image loading)

## Usage Examples

The component is a pricing card template. To customize, edit `index.html`:

- Update the main title in the `.price-card__heading` element.
- Change the guarantee or short CTA text in `.price-card__cta-sect1`.
- Update the price in `.price-card__package-price` and the period in `.price-card__package-duration`.
- Edit the list of benefits inside the `.price-card__reasons` list.
- Modify the CTA button text and link in the `.price-card__cta-button` anchor.

Example: to update the package price, find the `.price-card__package-price` element and replace the value:

```html
<p class="price-card__package-price">$29</p> <!-- Update this value -->
```

## Configuration Options

Most visual settings live in `style.css` using CSS custom properties at the top of the file (`:root`). Common adjustments:

- **Colors & Palette:** Edit variables such as `--BODY-BG`, `--SECT2-BG`, `--CTA-BUTTON-BG`, and other `--` variables near the top of `style.css`.
- **Typography:** Change the `--FF` font-family or the `@import` Google Font entry to swap fonts.
- **Card Size & Spacing:** Modify `.price-card` width, padding, and `grid-template-rows` to alter layout proportions.
- **Button Behavior:** Update `.price-card__cta-button` styles, hover colors, and transition timing to tune interactions.
- **Responsive Breakpoint:** Desktop styles apply at `@media (min-width: 992px)` — change that value if needed.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/dark-mode`).
3. Make focused commits and push to your fork.
4. Open a pull request describing your changes.

## License

License not specified.

## Acknowledgments

- Google Fonts for the `Karla` font used in this project.