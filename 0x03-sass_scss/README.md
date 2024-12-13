# CSS Preprocessors: SASS/SCSS for Efficient Styling

## **Project Overview**
This project demonstrates the use of SASS/SCSS for efficient and organized CSS styling. Each task involves applying core SASS concepts such as variables, mixins, nesting, and debugging.

### **Project Duration**
- **Start Date:** Dec 9, 2024 12:00 AM
- **End Date:** Dec 16, 2024 12:00 AM

### **Manual QA Review**
- Request QA review once all tasks are complete.
- An automatic review will occur at the deadline.

---

## **Tasks**

### **0. Project Set Up**
#### **Objective**
Install and set up SASS.

#### **Instructions**
1. Inside the `alx-intermediate-frontend` repository, create a new directory called `0x03-sass_scss`.
2. Install Node.js version 20.16 (Optional):
   ```bash
   $ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
   ```
   Exit and reopen the terminal.
3. Install SASS using npm (Optional):
   ```bash
   $ npm install sass -v 3.7.4
   ```
4. Create an empty file named `0-installation-script` and document the steps you took to install SASS.

---

### **1. Creating a Sass File to Output Debug Message 'Hello World'**
#### **Objective**
Write a SASS file to print `Hello world` in the debug output.

#### **File**
- `0-debug_log.scss`

#### **Expected Output**
```bash
0-debug_log.scss:2 DEBUG: Hello world
```

---

### **2. Using Sass Variables to Assign Text Color to Body and Paragraph Tags**
#### **Objective**
Assign the text color `#3D3D3D` to `<body>` and `<p>` tags using a SASS variable.

#### **File**
- `1-color_variable.scss`

#### **Expected Output**
```css
body {
  color: #3D3D3D;
}

p {
  color: #3D3D3D;
}
```

---

### **3. Nesting**
#### **Objective**
1. Remove margin and padding for `<body>` tags.
2. Add a margin of `10px` to `<p>` tags inside `<body>`.
3. Use nested declarations.

#### **File**
- `2-nested_tag.scss`

#### **Expected Output**
```css
body {
  margin: 0px;
  padding: 0px;
}

body p {
  margin: 10px;
}
```

---

### **4. Margin Mixins**
#### **Objective**
1. Assign a left and right margin of `10px` to `<body>` tags.
2. Assign a left and right margin of `15px` to `<div>` tags.
3. Use a mixin to achieve the above.

#### **File**
- `3-mixin_margins.scss`

#### **Expected Output**
```css
body {
  margin-left: 10px;
  margin-right: 10px;
}

div {
  margin-left: 15px;
  margin-right: 15px;
}
```

---

## **Repository Structure**
```plaintext
alx-intermediate-frontend/
├── 0x03-sass_scss/
│   ├── 0-installation-script
│   ├── 0-debug_log.scss
│   ├── 1-color_variable.scss
│   ├── 2-nested_tag.scss
│   ├── 3-mixin_margins.scss
└── README.md
```

## **How to Run the Files**
1. Navigate to the `0x03-sass_scss` directory:
   ```bash
   cd 0x03-sass_scss
   ```
2. Compile the SASS files using the `sass` command:
   ```bash
   sass <filename>.scss
   ```
   Replace `<filename>` with the specific file you want to compile.

---
