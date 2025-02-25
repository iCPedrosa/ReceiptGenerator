# Receipt Generator

A simple, standalone HTML/CSS/JavaScript receipt generator that works entirely in the browser.

## Features

- **No Installation Required**: Open the HTML file in any modern web browser to start using it.
- **Fully Customizable**: Edit company details, customer information, and line items.
- **Live Preview**: See changes in real-time as you edit the receipt.
- **PDF Generation**: Create printable receipts using your browser's built-in print function.
- **Responsive Design**: Works on desktop and mobile devices.
- **No External Dependencies**: Built with vanilla JavaScript, no libraries or frameworks needed.

## How to Use

### Getting Started

1. Download the `receipt-generator.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
3. That's it! No installation, server, or internet connection required.

### Customizing Your Receipt

#### Company Information
- Enter your company name
- Add your company address
- Include contact information (phone, email)

#### Receipt Details
- Set receipt number
- Choose date
- Enter customer name and address

#### Line Items
- Add as many service/product items as needed
- Specify quantity and rate for each item
- Amounts are calculated automatically
- Use the "Add Item" button to include additional items
- Use the "✕" button to remove unwanted items

#### Totals
- Subtotal and total are calculated automatically based on line items

### Generating a PDF

1. Fill out all necessary information
2. Click the "Generate Receipt PDF" button
3. Your browser's print dialog will appear
4. Select "Save as PDF" (or similar option in your browser)
5. Choose save location and filename
6. Click "Save" or "Print"

## Technical Details

### File Structure

The entire application is contained in a single HTML file that includes:
- HTML markup for the form and receipt preview
- CSS styles embedded in the `<style>` section
- JavaScript functionality in the `<script>` section

### Core Functionality

- **Real-time Calculations**: All calculations happen immediately as you type
- **Event Listeners**: Input changes automatically update the receipt preview
- **Print API**: Uses the browser's built-in printing capabilities for PDF generation

## Customization

You can easily modify the HTML, CSS, or JavaScript to:
- Change the visual design
- Add your company logo
- Include additional fields (like tax rates)
- Change currency format
- Add terms and conditions
- Implement additional functionality

## Browser Compatibility

Works with all modern browsers including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

## Limitations

- PDF generation relies on browser print capabilities
- No data persistence (refreshing the page will reset all fields)
- No server-side component or database integration

## License

Free to use for personal and commercial purposes.

---

Feel free to modify and extend this receipt generator to meet your specific needs!
