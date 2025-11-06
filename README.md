# MyWebUtils: Your All-in-One Suite of Online Developer Tools

Welcome to MyWebUtils, a comprehensive collection of free, client-side web utilities designed for developers, designers, data analysts, and tech enthusiasts. Our goal is to provide a fast, secure, and user-friendly toolkit that streamlines common tasks without ever sending your data to a server.

## ✨ Features

MyWebUtils is packed with a wide range of tools organized into logical categories for easy access. All tools run directly in your browser, ensuring your data remains private and secure.

### 🗃️ Data & Text Tools
- **JSON Validator**: **Validate, format, and visualize JSON data.** Paste your JSON into the input area. The tool will instantly validate the syntax, highlight errors, and display the formatted data in a collapsible tree view.
- **JSON Diff**: **Visually compare two JSON files.** Paste your original JSON in the left box and the modified JSON in the right. The tool highlights added (green) and removed (red) lines to easily spot differences.
- **CSV to JSON**: **Convert CSV data into structured JSON.** Paste your CSV text or upload a file. Use the options to specify if your data has a header row and to select the correct delimiter (comma, semicolon, etc.). The JSON output is generated instantly.
- **JSON Filter**: **Extract specific values from complex JSON.** Paste your JSON object and use the filter input to enter a path (e.g., `user.address.city` or `items[0].name`) to extract the corresponding value.
- **JSON Viewer**: **Parse and explore JSON data in a clean, navigable tree format.** Paste any JSON to see it beautifully formatted in a collapsible tree, making it easy to understand the structure of complex data.
- **YAML ↔ JSON Converter**: **Seamlessly convert data between YAML and JSON.** Choose your conversion direction (YAML to JSON or vice versa), paste your data, and see the converted output in real-time.
- **JSON String Escaper**: **Escape or unescape special characters in a string.** Paste a string to escape it for safe embedding within a JSON object, or paste an escaped string to convert it back to its readable form.
- **Regex Tester**: **Test and debug JavaScript regular expressions in real-time.** Enter your regex pattern and a test string. The tool will highlight all matches instantly and show you the match count.
- **Diff Viewer**: **Compare two blocks of text to see character-by-character differences.** Paste your original and modified text in the respective boxes to get a visual breakdown of what has been added or removed.
- **Text Cleaner & Sorter**: **Remove duplicate lines, empty lines, and extra whitespace.** Use the checkboxes to select cleaning options and choose a sorting method (alphabetical, by length) to instantly reformat your text.
- **Word & Character Counter**: **Get real-time statistics on your text.** Paste your content into the text area to see an instant count of words, characters (with/without spaces), lines, sentences, and paragraphs.
- **Case Converter**: **Convert text between various case formats.** Paste your text, select a target format like camelCase, PascalCase, or snake_case, and the converted text will appear immediately.
- **Lorem Ipsum Generator**: **Create customizable placeholder text.** Choose whether you want to generate paragraphs, sentences, or words, set the desired quantity, and click "Generate Text" to get your dummy content.

### 🔒 Encoders, Decoders & Security
- **Base64 Encode/Decode**: **Convert text to and from Base64.** Select "Encode" or "Decode" mode, paste your text, and the converted output will appear instantly. It fully supports UTF-8 characters.
- **URL Encode/Decode**: **Safely encode or decode text for URLs.** Choose "Encode" to make a string safe for a URL, or "Decode" to convert a percent-encoded string back to its original form.
- **JWT Decoder**: **Decode JSON Web Tokens to inspect their contents.** Paste a JWT into the input field to see the decoded Header and Payload in a readable JSON format. This tool does not verify the signature.
- **Hash Generator**: **Generate SHA-1, SHA-256, and SHA-512 hashes.** Paste any text and click "Generate Hashes" to get secure hash values, which are useful for data integrity checks.
- **Password Generator**: **Create strong, random passwords.** Adjust the sliders and checkboxes to set your desired length and character types (uppercase, numbers, symbols), then copy your new secure password.
- **Text Encryptor/Decryptor**: **A conceptual tool to demonstrate simple text obfuscation.** Enter text and a password, then choose "Encrypt" or "Decrypt" to see how a simple XOR cipher works. **Note: This is not for secure use.**
- **SSL Decoder**: **A conceptual tool to view certificate details.** Paste a PEM-encoded SSL certificate to see a placeholder breakdown of its properties, such as subject, issuer, and validity period.

### 🖼️ Image & QR/Barcode Utilities
- **Image ↔ Base64 Converter**: **Convert images to Base64 strings, and vice versa.** Upload an image to get its Base64 data URI, or paste a Base64 string to preview and download the corresponding image.
- **Image Cropper**: **Crop images with precision.** Upload an image, then define the crop area by setting the X, Y, Width, and Height coordinates. Click "Crop Image" to see a preview and download the result.
- **Image Rotator/Flipper**: **Adjust image orientation.** Upload an image, then use the buttons to rotate it in 90-degree increments or flip it horizontally/vertically. Download the transformed image.
- **Image Format Converter**: **Convert between PNG, JPG, and WEBP formats.** Upload an image, select your target format, adjust the quality slider if applicable, and download the newly converted file.
- **Image Resizer & Compressor**: **Resize dimensions and adjust quality.** Upload an image, set your desired width and height, and use the quality slider to find the perfect balance between size and clarity before downloading.
- **Image Text Watermark**: **Add customizable text watermarks.** Upload your image, then use the controls to type your watermark text, adjust its font, size, color, opacity, position, and rotation.
- **QR Code Generator**: **Create QR codes for any text or URL.** Enter the data you want to encode, customize the size and colors, and download the final QR code as a PNG, SVG, or JPEG.
- **All-in-One QR Code Generator**: **Generate specialized QR codes.** Use the tabs to create QR codes for Email, SMS, Twitter, or Facebook. Just fill in the relevant details for each type.
- **WiFi QR Code Generator**: **Share your WiFi network easily.** Enter your network name (SSID), password, and security type. The generated QR code will let guests connect instantly by scanning it.
- **Calendar Event QR Code Generator**: **Create an iCalendar (.ics) event QR code.** Fill in the event title, start/end times, and location. Users can scan the QR code to add the event directly to their calendar.
- **UPI QR Code Generator**: **Create QR codes for UPI payments in India.** Enter your UPI ID and optional details like your name and a payment amount to generate a scannable payment QR code.
- **1D Barcode Generator**: **Generate various barcode formats.** Enter your data, select a format like Code128 or EAN-13, customize the appearance (width, height, colors), and download the barcode as an SVG or PNG.

### ⚙️ Developer Utilities & Other Tools
- **Unit Converter**: **A developer-focused unit conversion tool.** Switch between categories like Length (px, rem, em) and Data Storage (Bytes, KB, MB, GB), enter a value, and see the conversion instantly.
- **Code Playground**: **An interactive sandbox for web development.** Write HTML, CSS, and JavaScript in the provided tabs and see the live preview update in real-time.
- **SVG Previewer**: **Preview SVG code live.** Paste your SVG markup into the input area to see it rendered instantly. You can then download the file.
- **JavaScript Runner**: **Execute JavaScript snippets in the browser.** Write your JS code, click "Run Code," and view all `console` outputs and errors in the output pane.
- **Sitemap Generator**: **Create an XML sitemap from a list of URLs.** Paste a list of your website's URLs (one per line), configure options like change frequency and priority, and generate the `sitemap.xml` file.
- **SQL Formatter**: **Beautify SQL queries for readability.** Paste your SQL code, select the correct dialect (e.g., PostgreSQL, MySQL), and click "Format SQL" to get a clean, indented version.
- **Gradient Generator**: **Visually create CSS gradients.** Choose a gradient type (linear, radial, conic), add, remove, or edit color stops, adjust the angle, and copy the generated CSS code.
- **CSS Box-Shadow Generator**: **A visual tool for creating complex CSS box-shadows.** Use the sliders to adjust offsets, blur, spread, and color opacity to design the perfect shadow, then copy the CSS.
- **Signature Pad**: **Draw a handwritten electronic signature.** Use your mouse or a stylus to draw your signature on the canvas, customize the pen color and thickness, and download the result as an image.
- **Typed Signature Generator**: **Create a signature image from text.** Type your name, choose from a variety of fonts, set the size and color, and download the generated signature image.
- **Fake Data Generator**: **Quickly generate dummy data for testing.** Select the type of data you need (e.g., names, emails, UUIDs), set the quantity, and generate a list of placeholder data.
- **Dictionary**: **Look up English word definitions and more.** Enter a word to get its definitions, phonetics (with audio), synonyms, and example sentences.

### 🧮 Calculators
- **Standard & Scientific Calculators**: For both basic arithmetic and advanced functions. Use your keyboard or click the buttons to perform calculations.
- **Percentage Calculator**: A versatile tool for solving various percentage problems. Select the calculation type, enter your values, and see the result instantly.
- **Ohm's Law Calculator**: Solve for voltage, current, resistance, or power. Select the value you want to find, enter the two known values, and the rest are calculated automatically.
- **Finance Calculators**: A full suite for financial planning. Each calculator (EMI, Simple Interest, Compound Interest, SIP, Lumpsum, Retirement, Loan Affordability, Goal-Based Savings, and Tip) requires you to fill in the relevant fields to get a detailed calculation and breakdown.
- **Health & Fitness Calculators**: Includes BMI, Sleep Cycle, and Pace calculators. Enter your details to get health-related metrics and suggestions.
- **Area & Tile Calculator**: Estimate the number of tiles needed for a room. Enter room and tile dimensions, and the tool will calculate the total area and the number of tiles required, including wastage.
- **Time & Date Calculators**: A collection of tools for time-related math. Calculate your exact age, find the difference between two dates, or set a countdown to a future event.

### 🎮 Games & Fun
A collection of classic browser-based games and randomizers to take a break:
- **Chess**, **Snake**, **Sudoku**, **Tic-Tac-Toe**, **Rock Paper Scissors**, **Hangman**: Classic games with simple controls. Follow the on-screen instructions to play.
- **Catch the Falling Object**: Use your mouse to move the basket and catch the good items while avoiding the bad ones.
- **Higher or Lower**: Guess if the next number will be higher or lower than the current one.
- **Dice Roller**, **Spin The Wheel**, **Flip a Coin**, **Random Name Picker**, **Random Number Generator**, **Random Emoji Generator**: Simple randomizers. Configure your options (if any) and click the button to get a random result.

## 💻 Tech Stack
- **Framework**: [Next.js](https://nextjs.org/) (with App Router)
- **UI**: [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Tailwind CSS](https://tailwindcss.com/), [ShadCN UI](https://ui.shadcn.com/)
- **State Management**: React Hooks & Context API

## 🛡️ Our Commitment to Privacy

**Your data is your own.** Every tool in MyWebUtils is designed to work entirely on the client-side. This means the data you input is processed locally in your browser and is never sent to, stored on, or tracked by our servers. You can use our tools with the confidence that your information remains private.

## 🤝 Connect with Us

Stay up-to-date with the latest tools and features by following us on social media:

- **GitHub**: [https://github.com/mywebutils](https://github.com/mywebutils)
- **X / Twitter**: [https://x.com/mywebutils](https://x.com/mywebutils)
- **Facebook**: [https://www.facebook.com/mywebutils](https://www.facebook.com/mywebutils)
- **Instagram**: [https://www.instagram.com/mywebutils](https://www.instagram.com/mywebutils)

---

Thank you for using MyWebUtils! We are constantly working to add new tools and improve existing ones based on community feedback.
