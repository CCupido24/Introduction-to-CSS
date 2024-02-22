# Introduction-to-CSS

1.	Introduction in CSS
1.1 HTML and CSS:
	CSS (Cascading Style Sheets):
  o	Holds styles for webpages.
  o	Enhances visual appeal.
  o	Linked to HTML for connection.

	HTML (Hypertext Markup Language):
  o	Defines webpage structure with elements like paragraphs, headings, lists, and links.
  o	Raw HTML appears unattractive in browsers.

	CSS Components:
  o	Selector: Defines pattern in HTML.
  o	Declaration block: Contains styles applied to matching HTML elements.

	Cascading in CSS:
  o	Multiple styles can apply to the same pattern.
  o	Simplified approach in this course, not delving deep into cascading.

1.2 CSS Components:
	Each style declaration comprises:
  o	A property
  o	A value

	Focus on a select set of properties and values during the course.
	Emphasis on understanding selectors for targeting HTML elements.
	Importance of selectors for utilizing properties and values effectively.
	Initial emphasis on creating unattractive web pages.
	Improvement expected by the end of the course as key styles are incorporated.

2.	Adding CSS Selectors
2.1 Writing Your First Comment and Element Selector:
	Start with simple CSS code for the document.
	Review HTML structure before diving into CSS.
	Example HTML structure includes headings, paragraphs, and comments.
	HTML comments differ from CSS comments.
	CSS comments use slash star and star slash.
	Selectors in CSS:
  o	Element selector targets specific HTML elements.
  o	Example: "P" selects all paragraphs and sets color to blue
  o	"H2" selector makes all H2 elements red.

	Encouragement to try writing styles for H1 and H3 elements.
	Experiment with different colors for each heading text.
	Reference the "01-01-End" state in the Exercise Files to see the outcome.
	Congratulations on writing your first CSS code.


2.2 Writing a Class Selector:
	Introduction to assigning classes to HTML elements for styling specificity.
	Classes are attributes providing additional details about elements.
	Use of class attribute in HTML for specific styling references
	In CSS, differentiate class selectors with a dot (.)
	Example: ".intro" class makes the first paragraph green.
	Utilize span element with class attribute for styling specific parts of elements.
	Example: ".guarantee" class styles a sentence within a paragraph differently
	Order of style declarations is flexible in CSS.
	Example task: Make a sentence black, bold, and uppercase using the "important" class and "text-transform: uppercase" CSS property.
	Apply class name to select the sentence in HTML and complete the styling in CSS.

2.3 Grouping Selectors:
	Apply the same style to different selectors at times.
	Example: Making all paragraphs green.
	Consideration: Extend the style to list items as well.
	Utilize grouping selectors to avoid repetitive code.
	Combine selectors using a comma (,) in CSS.
	Example: Writing ".paragraph, .list-item" to style paragraphs and list items collectively.
	Grouping selectors can include elements and classes.
	Example: Adding ".mineral" class to make specific text green.
	Each item in the grouped selectors is treated individually by the browser.
	Grouping selectors streamline styling for multiple elements or classes.

2.4 Descendant Selectors:
	HTML includes headings, paragraphs, and two lists under the "ingredients" section.
	Lists differentiate between ordered and unordered lists, indicating a specific order or lack thereof.
	Styling involves grouping paragraphs, list items, and elements with the class "mineral" and making them green.
	Ordered list items styled as blue and bold, while unordered list items as purple and uppercase.
	Individual class assignment to each list item is cumbersome.
	Descendant selector simplifies styling by selecting elements based on their hierarchy in HTML.
	HTML organized like a family tree with parent, child, and descendant elements.
	Descendant selector syntax: "OL LI" selects list items within ordered lists.
	Styles applied using a descendant selector read from right to left.

3.	CSS Images and Colors
3.1 Identifying a Color Scheme:
	Choosing a color scheme for a website is crucial.
	Options for creating color palettes:
  o	Design background enables personal creation.
  o	Use online resources like Canva's color palette generator.

	Canva offers three methods for creating color palettes:
  o	Extracting colors from images (e.g., donuts, canoe).
  o	Exploring pre-made color palettes with related combinations.
  o	Creating custom color palettes based on user preferences.
	Custom color palette creation includes options like:
  o	Complementary, monochromatic, analogous, and triadic color combinations.
  o	Tetradic color combinations for a square of colors.

	Users can adjust saturation or try different variations of color combinations.
	Canva provides categorized color palettes filtered by keywords.
	Users can also upload images to generate color palettes based on the image's colors.

3.2 Formatting Color in CSS:
	Incorporate selected color palette into code.
	Named colors: Limited selection, around 130 available in CSS.
	Hex codes: Represent colors using hexadecimal format (six-digits)
  o	Red, green, and blue components represented by pairs of digits.
  o	Correspond to numbers from 0 to 255.

	Canva's color palettes display hex values, commonly used in web design.
	Hex values can be shortened if each two-digit pair is the same.
	RGB format: Specifies colors using Base 10 numbers for red, green, and blue channels.
  o	Can be represented as an eight-digit hex number or RGBA with an alpha value for opacity.

	Other color formats like HSL or HSLA may be used, especially in platforms like Squarespace.
	Converting color formats:
  o	Google and DuckDuckGo offer color picker tools for conversions.
  o	Color Hex website provides shades, tints, and color palettes specific to chosen colors.

	Resources like Google, DuckDuckGo, and Color Hex are helpful for color conversions and exploring complementary colors.

3.3 Background and Text Color in CSS:
	Exercise files provide starting and ending states for Sublime Text, along with additional resources.
	Test named colors and adjusted text color for readability.
	Use named color chart to choose colors, preferring hex values for compatibility.
	Canva provides color palettes but use hex values for Sublime Text.
	Note differences in shades of colors between Canva and CSS chart.
	Change background color with "background-color" property and specify hex color
	Adjust text color for readability, like setting white text on a white background.
	Apply background color to elements like unordered lists (ul)
	Use hex codes for consistency and readability.
	Style entire webpage using "body" HTML element for uniform background color
	Recap: Choose colors for text and background elements, either for specific elements or the entire page
	Use named color palettes or create custom colors using Canva.


3.4 Understanding Images in CSS:
	Images can be added in HTML or CSS on webpages.
	Various image formats for the web: GIF, PNG, JPEG, bitmap, TIFF, PSD.
	Traditionally, web supported three main image formats:
  o	GIF: Limited colors, transparency, and animation
  o	PNG: More colors, transparency, no animation
  o	JPEG: Optimized for photographs, millions of colors, no transparency, or animation.

	Emergence of WebP format: Offers high compression for smaller file sizes, suitable for both photos and illustrations.
	Importance of choosing the right image format to avoid color loss and large file sizes.
	Tips for optimizing images: Adjust dimensions, trim unnecessary parts, resize, and reduce file size.
	Tools like tinypng.com or Adobe Photoshop aid in reducing image file sizes without quality loss.
	Inclusion of images in webpages:
  o	HTML: Use the image element for placing images alongside text, essential for conveying messages like logos or icons
  o	CSS: Allows inclusion of background images, primarily decorative and not essential to webpage text
  o	Background images can repeat or display a portion of the image based on configuration.

3.5 Working with Background Images in CSS:
	Preview background images before usage.
	Apply background images to webpages using CSS.
	Use background images for body element or specific elements like H1 headings.
	Background images can flex and tile both horizontally and vertically.
	Adjust background image positioning and repetition using CSS properties like "repeat-X" and "repeat-Y".
	Control background image starting position with values like "center," "right," or "left".
	Set background image position using height values like "97vh" to position it where desired.
	Experiment with different background images and properties to enhance webpage visual appeal.
	Adjust background image positioning using percentages for improved aesthetics.
	Explore various styling options for background images in webpage design.

4.	CSS Boxes, Types and Sizes

4.1 Understanding Type in CSS:
	Font and spacing contribute to web page aesthetics.
	Fonts categorized into serif and sans serif types.
  o	Serif fonts: Have small lines (serifs) at letter ends, historically used for print materials.
  o	Sans serif fonts: Modern appearance, lack serifs, preferred for extended text on the web.

	Default web font usually Times New Roman but varies depending on device and user settings.
	Web fonts selection complex due to device and font availability variations
	Font stack: Specifies multiple fonts to ensure compatibility across devices.
  o	Example: Arial, Helvetica, sans serif

	Safe font choices include Arial, Helvetica, Verdana, Times, Times New Roman, Georgia, Trebuchet MS.
	Google offers over a thousand web fonts for website use, loaded into web browser for consistent display.
	Course focuses on basic fonts available on user devices, development teams guide font stack choices.
	Font selection impacts webpage design and readability, influencing user experience.

4.2 Applying Type Formatting with CSS:
	Modify appearance using different fonts in CSS.
	Use font-family property to change fonts on the page.
	Employ font stack: Arial, Helvetica, Sans-serif for compatibility across devices.
	Arial and Helvetica installed on computer allow comparison of fonts.
	Helvetica likely default Sans-serif font for Chrome browser.
	Perfection in font display across devices not attainable; aim for readability and decent appearance.
	Avoid using too many fonts to maintain professionalism.
	Create contrast by using serif font like Georgia or Times New Roman for headings.
	Enclose font names with multiple words in quotes, place comma outside quotes.
	Serif font for headings and Sans-serif font for paragraphs improve readability, especially for longer text.
	Experiment with additional properties like font-style: italic and font weight to normal to give headings a unique look.
	Using Sans-serif font instead of Times text significantly improves overall appearance and readability.

4.3 Understanding and Applying size in CSS:
	Text size often determined by web browser's default style sheet.
	Two types of sizing: absolute (points, pixels) and relative (percentages, rem)
	Preferred font size unit: "rem" (1 rem = 16 pixels)
	Online calculators available for converting between different size units.
	Point to REM Converter tool helps convert between pixels, rem, em, and percent.
	Font size adjustment in CSS using "font-size" property.
	Adjustments in font size proportional to body size unless explicitly defined.
	No strict rule for hierarchy of heading sizes (h1, h2, h3, etc.)
	Heading sizes can be adjusted for stylistic purposes without changing HTML structure.


4.4 Understanding the Box Model in CSS:
	HTML elements treated as boxes with various properties.
	Properties include content, border, padding, and margin.
	Content: text inside the box
	Border: line surrounding the content with customizable styles
	Padding: space between border and content, can have background color
	Margin: space between elements on the page, separates intersecting elements
	Properties can be applied individually or to all four sides.
	Shorthand values available for border, padding, and margin properties
	Examples include setting border thickness and style, applying margins, and setting padding.
	Focus on applying changes to all sides or specific sides of the box.
	Key sides: left, right, top, bottom.

4.5 Working with Border, Padding, and Margin in CSS:
	Background leaves and spacing issues on the webpage need addressing.
	Start with the body element to remove default browser margin by setting it to zero.
	Reposition the background leaves to the bottom by adding a footer element.
	Give the footer height and add a top border for separation.
	Adjust margins and padding for headings:
  o	Remove margins from H1 to position it at the top.
  o	Add padding to create space for the red bar beneath H1.
  o	Adjust margins and padding for H2 and H3 for visual appeal.
  o	Include decorative borders for visual distinction.

	Center the image by placing it inside a paragraph with a class of "circle" and set text-align to center.
	Utilize the border-radius property to create rounded corners for elements.
	Apply these CSS modifications to enhance the webpage's appearance with minimal CSS usage.

5.1 Styling Links With CSS
	Links are essential elements on the internet, typically appearing as blue and underlined.
	The default behaviour of links is to turn purple after being visited.
	We explore formatting links in HTML and CSS, especially focusing on Sublime Text and Chrome's guest tab.
	To change link colors, specify color codes, but default browser styles may override these changes.Target links using the "a" anchor tag and specify color properties.
	Different states of links include unvisited, visited, and hover states.
	For hover states, color changes and underline removal can enhance user experience.
	Separate styles for visited and unvisited links are possible using "a:link" and "a:visited" selectors.
	The order of styles is crucial for proper styling application.
	Retaining underlines on links aids users, especially those with disabilities, but exceptions can be made for navigation bars.
	These tips help in styling web page links for better user experience and visual appeal.

5.2  Inheritance in CSS
	Inheritance and specificity in CSS can be complex but are crucial concepts.
	Inheritance ensures that styles cascade down to child elements from their parent elements.
	When styling the body element, properties like font family are inherited by all HTML elements within it.
	Font-related styles typically inherit to maintain consistency across the document.
	However, styles related to the box model, such as borders, do not inherit to prevent chaos.
	Using the "*" selector to apply borders to all elements results in a messy webpage.
	Understanding inheritance is essential for developers to control styling effectively.
	Inheritance impacts developers more than average users but remains important for all to grasp.
 5.3 Debugging CSS with Borders and Background Colors
	Debugging CSS issues is common when styling elements.
	Adding background colors or borders to elements can reveal hidden information and aid in debugging.
	For example, adding a border to a UL element helps visualize its position on the page.
	Block-level elements like UL and LI take up the full width of their container, while inline elements like links (A) are only as wide as their content.
	Understanding the distinction between block and inline elements is crucial for effective CSS styling.
	To create a hover effect spanning the entire width of an element, consider changing inline elements to block-level elements.
	Applying CSS styles like "display: block" to links can stretch them across the page, enabling full-width hover effects.
	Experimenting with borders and background colors helps diagnose and solve CSS issues effectively.
	Focus on functionality first, then refine aesthetics once functionality is correct.
