# 📋 Responsive Registration Form

This project is a responsive registration form built using HTML and CSS. It is designed to collect user information such as name, email, password, age, and preferences while maintaining an accessible and clean layout.

---

## 🌐 Live Demo

> You can test this form using [this mock submission URL](https://register-demo.freecodecamp.org).

---

## 📁 Project Structure

registration-form/ <br>
│<br>
├── index.html # Main HTML structure of the registration form<br>
├── styles.css # Styling and layout rules for the form<br>
└── README.md # Project documentation<br>


---

## ✨ Features

- 📱 **Responsive Design**: Adjusts layout for different screen sizes using `max-width`, `width`, and viewport-relative units.
- ✅ **Form Validation**: Required fields and input patterns to ensure correct user input.
- 📸 **File Upload Support**: Allows users to upload a profile picture.
- 🔒 **Password Requirements**: Enforces pattern-based password creation.
- 🔘 **Radio and Checkbox Inputs**: Account type selection and terms agreement included.
- 📝 **Textarea and Dropdown**: For bio and referral source.

---

## 📜 Form Fields

### **Personal Details**
- First Name (text)
- Last Name (text)
- Email (email format)
- Password (min. 8 characters, lowercase letters or digits only)

### **Account Type**
- Personal or Business (radio buttons)

### **Profile Details**
- Profile picture upload
- Age input (13 to 120)
- Referral source (dropdown)
- Short bio (textarea)

### **Terms & Conditions**
- Checkbox to agree to terms before submission

---

## 🎨 Styling (CSS Highlights)

- Dark theme with:
  - Background: `#1b1b32`
  - Text color: `#f5f6f7`
  - Form elements styled with dark background and light text.
- Layout:
  - `max-width: 500px` ensures form does not stretch too wide.
  - `width: 60vw` makes the form responsive to screen size.
- Consistent spacing using:
  - `margin`
  - `padding`
  - `fieldset` separation with a subtle border.

---

## 🚀 How to Use

1. **Download or clone** this repository:

```bash
git clone https://github.com/yourusername/registration-form.git
```


## 🛠️ Customization Tips
- Update the form action URL if you want to connect it to your backend.

- Adjust pattern on the password field to enforce different complexity rules.

- Add client-side JavaScript for advanced validation or interactive elements.

## 🧩 Accessibility
- Uses proper label associations with for and id attributes.

- Inputs use required, type, and pattern for validation.

- All elements follow a logical and readable structure.

## 🧪 License
This project is open-source and free to use under the MIT License.
