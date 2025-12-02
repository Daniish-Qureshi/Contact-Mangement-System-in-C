# 📞 Contact Management System

A lightweight, command-line based Contact Management System implemented in C. This project provides a simple yet functional way to manage your contacts through an easy-to-use text interface.

## Screenshots

[![Demo Screenshot 1](https://github.com/Daniish-Qureshi/Contact-Mangement-System-in-C/blob/main/demo.png)]

## 🚀 Features

- Add new contacts with name, phone, and email
- View all saved contacts
- Edit existing contacts
- Delete contacts
- Simple, menu-driven interface
- Easy to understand and modify codebase

## 🛠️ Prerequisites

- GCC Compiler (MinGW for Windows)
- Windows OS (originally developed for, but can be adapted for other platforms)

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Daniish-Qureshi/Contact-Mangement-System-in-C.git
   cd Contact-Mangement-System-in-C
   ```

## 🏗️ Building the Project

### Windows (Using MinGW)

```powershell
# If MinGW is installed at C:\MinGW
C:\MinGW\bin\gcc.exe -o contact_manager project.c

# Or if gcc is in your system PATH
gcc -o contact_manager project.c
```

### VS Code Users

You can use the built-in task by pressing `Ctrl+Shift+B` and selecting `C/C++: gcc.exe build active file`.

## 🚀 Usage

Run the compiled program:
```bash
.\contact_manager.exe
```

### Menu Options

1. **Add Contact** - Add a new contact with name, phone, and email
2. **View Contacts** - List all saved contacts
3. **Edit Contact** - Modify an existing contact
4. **Delete Contact** - Remove a contact from the system
0. **Exit** - Close the application

## 📝 Example Usage

```
=== Contact Management System ===
1. Add Contact
2. View Contacts
3. Edit Contact
4. Delete Contact
0. Exit

Enter your choice: 1

Enter Name: John Doe
Enter Phone: +1234567890
Enter Email: john@example.com
Contact added successfully!
```

1. **Main Menu**
   ```
   === Contact Management System ===
   1. Add Contact
   2. View Contacts
   3. Edit Contact
   4. Delete Contact
   0. Exit
   ```

2. **Adding a Contact**
   ```
   Enter your choice: 1
   
   Enter Name: John Doe
   Enter Phone: +1234567890
   Enter Email: john@example.com
   Contact added successfully!
   ```

3. **Viewing Contacts**
   ```
   === Contact List ===
   [1] John Doe
       Phone: +1234567890
       Email: john@example.com
   ```

To add actual screenshots:
1. Create a `screenshots` directory in your project root
2. Add your screenshot files (e.g., `main-menu.png`, `add-contact.png`)
3. Reference them using Markdown:
   ```markdown
   ![Main Menu](./screenshots/main-menu.png)
   ```

## �🛠️ Development

### Project Structure

- `project.c` - Main source file containing all the application logic

### Future Enhancements

- [ ] Add persistent storage (file I/O)
- [ ] Implement contact search functionality
- [ ] Add input validation
- [ ] Support for multiple phone numbers per contact
- [ ] Export/Import contacts (CSV/JSON)
- [ ] Add contact categories/groups

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## � Contact

For any queries or feedback, feel free to reach out:

- � Email: *danishwork29@gmail.com*
- 🌐 Portfolio: [danish-qureshi.vercel.app](https://danish-qureshi.vercel.app/)
- 💼 LinkedIn: [danishqureshi786](https://www.linkedin.com/in/danishqureshi786/)
- 💻 GitHub: [Daniish-Qureshi](https://github.com/Daniish-Qureshi)

## 🙋‍♂ Author

👤 **Danish Qureshi**  
🔗 [Portfolio](https://danish-qureshi.vercel.app/) | [GitHub](https://github.com/Daniish-Qureshi) | [LinkedIn](https://www.linkedin.com/in/danishqureshi786/)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped improve this project.
- Inspired by the need for simple, educational C projects.
