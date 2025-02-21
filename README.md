## 📝 Pygame Task Manager

This is a simple **Task Manager** built using Python and the Pygame library. The application allows users to enter their name, add tasks to a list, and remove tasks once they are completed.

## 🚀 Features

- 🎨 User-friendly interface with a green background and black text.
- 🖋️ Add new tasks to your to-do list.
- ❌ Remove tasks when they're finished.
- 👤 Personalized experience by entering your name.

## 📦 Requirements

Ensure you have Python and Pygame installed. You can install Pygame using:

```bash
pip install pygame
```

## 💻 How to Run

1. Clone this repository or copy the code into a `.py` file.

2. Open a terminal in the project folder and run:

```bash
python task_manager.py
```

3. Follow the on-screen instructions:
   - Enter your name.
   - Add tasks to the list.
   - Enter `0` when you're ready to remove tasks.
   - Enter the task number to remove it.
   - Enter `0` again to exit the app.

## 🛠️ Code Structure

### Key Sections
- **Input Handling:** Captures keyboard inputs for adding/removing tasks.
- **Task Display:** Shows the current task list with numbering.
- **Task Removal:** Removes tasks based on user input.
- **Dynamic Prompts:** Adapts the user interface depending on the current action.

## 🖱️ Controls

- **Type:** Enter your name, tasks, or task numbers.
- **Enter:** Confirm input.
- **Backspace:** Delete the last character.
- **0:** Switch between adding and removing tasks.

## 📷 Preview

```
What is your name?
Current input: [Your Name Here]

1. Grocery Shopping
2. Work
3. Gym
4. Restocking Fridge
```

After entering `0`, you'll enter the task removal mode:

```
Hello [Name], what task number do you want to remove from this list? (Enter 0 to QUIT!)
Current input: 2

You have marked off/Finished: Work
```

## ⚙️ Customization

- **Background Color:** Change `BG_COLOR` in the code.
- **Font Size:** Modify `FONT_SIZE` to increase/decrease text size.
- **Default Tasks:** Update the `tasks` list with your preferred default tasks.

## 📝 Known Issues

- Only accepts numerical input for task removal.
- Does not save tasks after closing the app.

## 🤝 Contributing

Feel free to fork this repository, make improvements, and submit pull requests!

## 📄 License

This project is released under the **MIT License**.

---

⭐ Enjoy managing your tasks efficiently with this fun Pygame project!
