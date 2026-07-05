# 📝 ToDo List

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

This project is a **dynamic web application for managing daily tasks**, focused on a clean, minimalist, and highly responsive user experience. It is ideal for consolidating state management and event-handling concepts within the Front-End ecosystem.

---

## 📌 Table of Contents

- [📝 ToDo List](#-todo-list)
  - [📌 Table of Contents](#-table-of-contents)
  - [📌 About the Project](#-about-the-project)
  - [🛠️ Structure and Styling](#️-structure-and-styling)
  - [🚀 Main Features](#-main-features)
  - [📸 Interface Demonstration](#-interface-demonstration)
  - [🎯 Learning Objectives](#-learning-objectives)
  - [🔧 How to Run](#-how-to-run)

---

## 📌 About the Project

The application allows users to create, edit, complete, and delete tasks in a fully interactive way. The layout was developed with structural minimalism in mind, utilizing soft blue and gray tones to keep the visual focus entirely on pending and completed tasks.

---

## 🛠️ Structure and Styling

Following best practices for interface design and development, the site structure features:

- **Centralized Container:** Main layout centered on the screen with rounded corners and smooth shadows (`box-shadow`), ensuring depth and visual prominence for the panel;
- **Modern Input Field:** A text input with rounded corners integrated with a green highlighted quick-action button (`+`);
- **Flexible Listing:** Each list item is structured using `display: flex` to perfectly align the task text to the left and the action icons (edit and delete) to the right;
- **Conditional Styling:** Use of CSS properties combined with JavaScript to dynamically apply a strikethrough visual effect (`text-decoration: line-through`) on tasks marked as completed.

---

## 🚀 Main Features

- **➕ Add Task:** Dynamic creation of new items in the list straight from the text field.
- **✅ Visual Completion:** Instant checkmark activation and line-through effect when an activity is completed.
- **✏️ Dynamic Editing:** Allows modifying the text of an existing pending task directly in the interface via the pencil icon.
- **🗑️ Individual Deletion:** Full and immediate removal of any item using the trash can button.

---

## 📸 Interface Demonstration

<p align="center">
  <img src="/images/preview.gif" alt="ToDo List Interface Demonstration" width="550px">
</p>

---

## 🎯 Learning Objectives

This project served as a practical laboratory to apply and master crucial concepts such as:

- Advanced DOM (Document Object Model) manipulation via vanilla JavaScript;
- Capture and handling of click events using `addEventListener`;
- State management in lists (tracking active vs. completed items);
- Advanced alignment and responsiveness using CSS Flexbox.

---

## 🔧 How to Run

1. Clone the repository to your local machine:

```bash
git clone git@github.com:vinicioslacerda/To-Do-List.git
```
