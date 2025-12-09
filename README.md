# 📦 Bulk UPC Label Generator

A professional, responsive web application for generating bulk UPC barcode labels for e-commerce inventory management. Designed specifically for Amazon, Flipkart, and Meesho sellers.

## ✨ Features

- **Bulk Label Generation**: Process multiple UPC codes with quantities in one click
- **Professional Barcodes**: Uses JsBarcode library for high-quality CODE128 barcodes
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, attractive interface with toast notifications
- **Print-Optimized**: A4 page layout with 3 labels per page
- **Real-time Preview**: Instant visual feedback before printing
- **Auto-resizing Textarea**: Input field grows as you add more data
- **Error Handling**: Beautiful toast notifications for validation and success messages

## 🚀 Quick Start

1. Save the HTML file to your computer
2. Open it in any modern web browser (Chrome, Firefox, Edge, Safari)
3. Enter your label data
4. Click "Generate Preview" to see your labels
5. Click "Print Labels" to print directly to your printer

## ⚙️ Configuration

### Input Fields

**Line 1 (Name)**: Your brand or collection name
- Default: "Nilu's collection,"

**Line 2 (Company)**: Your company name
- Default: "BLINK COMMERCE PRIVATE LIMITED"

**Line 3 (Warehouse)**: Warehouse location (automatically bold)
- Default: "Hyderabad H3 - Feeder Warehouse"

**UPC Data**: Enter data in format `UPC,Quantity`
- One item per line
- Example:
