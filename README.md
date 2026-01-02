# 📞 Phone Number Information Extractor (Python)

A simple yet practical Python tool that extracts **timezone, carrier, and registered location** information from a phone number using the `phonenumbers` library.

This project demonstrates working with **real-world data parsing**, external libraries, and clean CLI-based user interaction.

---

## 🚀 Project Overview

This tool allows users to:
- Enter a phone number with country code
- Detect the phone number's timezone
- Identify the SIM carrier
- Find the registered geographical location

It is useful for learning:
- Data extraction
- Library-based parsing
- Input validation concepts
- CLI-based Python tools

---

## 🧠 How It Works

1. User inputs a phone number with country code
2. The number is parsed using `phonenumbers`
3. Timezone is extracted using `timezone.time_zones_for_number`
4. Carrier name is detected using `carrier.name_for_number`
5. Registered location is identified using `geocoder.description_for_number`
6. Results are printed in the terminal

---

## 🛠️ Technologies Used

- **Python**
- **phonenumbers** library
- **CLI-based interaction**
- **Linux environment**

---

## 📁 Project Structure

```
phone-number-info/
│
├── main.py          # Main Python script
├── README.md        # Project documentation
└── .gitignore
```

---

## ▶️ How to Run the Project

### 1️⃣ Install dependency
```bash
pip install phonenumbers
```

### 2️⃣ Run the script
```bash
python main.py
```

### 3️⃣ Example input
```text
Enter your number with Country Code: +8801XXXXXXXXX
```

---

## 🎯 Purpose of This Project

- Learn how to work with phone number metadata
- Practice Python scripting with external libraries
- Build small but useful portfolio projects
- Understand real-world data extraction use cases

---

## 🔮 Future Improvements

- Validate phone number format
- Add error handling for invalid numbers
- Format output more cleanly
- Convert into a GUI or web tool
- Batch phone number lookup

---

## ⚠️ Disclaimer

This tool does **not** track users or reveal private data.  
It only extracts publicly available metadata from phone numbers.

---

## 📜 License

This project is open-source and intended for educational and portfolio purposes.

---

## 🙌 Author

**Nayon Ahmed**  
Linux user | Python developer | Automation enthusiast  
GitHub: https://github.com/nayonahmedjoy
