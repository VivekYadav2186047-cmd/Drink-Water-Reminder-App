# 💧 Drink Water Reminder App

A simple Python application that reminds you to drink water at regular intervals using desktop notifications. This project helps promote healthy hydration habits while demonstrating the use of Python notification libraries.

## 🚀 Features

- 🔔 Sends desktop notifications every hour
- 💧 Encourages regular water intake
- 🐍 Built with Python
- ⚡ Lightweight and easy to use

## 🛠️ Technologies Used

- Python 3
- plyer
- time

## 📂 Project Structure

```
Drink-Water-Reminder/
│── main.py
│── README.md
```

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Drink-Water-Reminder.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Drink-Water-Reminder
   ```

3. Install the required package:
   ```bash
   pip install plyer
   ```

## ▶️ Usage

Run the application:

```bash
python main.py
```

The app will send a desktop notification every **60 minutes** reminding you to drink water.

## 📝 Note

There are two small issues in the current code that need to be fixed before running:

```python
time.sleep(60 * 60)
```

instead of

```python
timesleep(60 * 60)
```

Also, make sure you have imported the `time` module correctly:

```python
import time
```

## 📸 Example Notification

**Title:**
> Hey love! Please drink some water and relax for a minute

**Message:**
> I love you ❤️

## 🎯 Future Improvements

- Custom reminder intervals
- Sound notifications
- Start/Stop reminder button
- GUI using Tkinter or CustomTkinter
- System tray support

## 👨‍💻 Author

**Vivek Yadav**

If you found this project useful, don't forget to ⭐ the repository!
