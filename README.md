# Student ID Card Generator

A lightweight, browser-based student ID card generator for creating, previewing, printing, and downloading professional-looking student identification cards as PNG images.

![Student ID Card Generator preview](https://github.com/AmjadKhan88/student-id-card-generator/blob/main/thumbnail.jpg?raw=true)

> **Preview image placeholder:** Replace the image URL above with your actual thumbnail or screenshot when it is ready.

## ✨ Features

- Live preview while entering student information
- Customizable institution, department, student, registration, contact, and validity details
- Student profile photo upload with remove/reset support
- Five built-in card themes:
  - Blue
  - Emerald
  - Purple
  - Dark
  - Crimson
- Download the completed ID card as a high-resolution PNG
- Print-friendly layout with dedicated print styles
- Barcode-style registration number display
- Responsive interface for desktop, tablet, and mobile screens
- Reset form button for quickly restoring sample data

## 🛠️ Built With

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Font Awesome
- Google Fonts
- [html2canvas](https://html2canvas.hertzen.com/) for PNG export

## 🚀 Getting Started

### Option 1: Open locally

1. Clone the repository:

   ```bash
   git clone https://github.com/AmjadKhan88/student-id-card-generator.git
   ```

2. Open the project directory:

   ```bash
   cd student-id-card-generator
   ```

3. Open `student_id_card_generator.html` in a modern web browser.

No build process, package installation, or server is required for the basic version.

### Option 2: Use a local web server

For the most reliable browser behavior, serve the file locally:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000/student_id_card_generator.html](http://localhost:8000/student_id_card_generator.html).

## 📖 How to Use

1. Enter the institution and department details.
2. Add the student's name, registration number, father's name, phone number, email, and validity period.
3. Upload a profile photo if required.
4. Select a visual theme.
5. Review the live card preview.
6. Choose **Download ID Card (PNG)** to save the card or **Print ID Card** to print it.

## 📁 Project Structure

```text
student-id-card-generator/
└── student_id_card_generator.html   # Complete application: markup, styling, and JavaScript
```

## 🌐 Browser Support

Use a current version of Chrome, Edge, Firefox, or Safari. An internet connection is recommended because the page loads Tailwind CSS, Font Awesome, Google Fonts, and html2canvas from CDNs.

## ⚠️ Important Notes

- This project is a front-end template and does not store student data in a database.
- Uploaded photos are processed in the browser and are not uploaded to a server by this application.
- Replace the sample student data before creating a real card.
- Treat generated identification cards and personal information responsibly. Do not use them for impersonation, fraud, or unauthorized access.

## 🔧 Customization

You can customize the application directly in `student_id_card_generator.html`:

- Change default institution and student values.
- Add or remove form fields.
- Modify card dimensions and print styling.
- Add new themes in the `themes` configuration object.
- Replace CDN dependencies with local assets for offline use.
- Replace the placeholder README image with an actual project screenshot.

## 🤝 Contributing

Contributions are welcome. To contribute:

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make and test your changes in a browser.
4. Commit your work:

   ```bash
   git commit -m "Add your feature"
   ```

5. Push the branch and open a pull request.

## 📄 License

No license has been specified yet. Add a license file if you plan to define permissions for using, modifying, or distributing this project.

## 👤 Author

Created by [AmjadKhan88](https://github.com/AmjadKhan88).

---

If this project helps you, consider giving it a ⭐ on GitHub.
