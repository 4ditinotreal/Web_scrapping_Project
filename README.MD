# 🌐 Web Scraping Project

A Python-based web scraping application that automates downloading datasets from Kaggle using **Playwright**. The project logs into Kaggle, searches for a specified dataset, downloads it, and saves it locally for further analysis.

---

## 🚀 Features

- 🔐 Automatic Kaggle Login
- 🔍 Search Datasets by Keyword
- 📥 Download Dataset Automatically
- 📂 Save Downloaded Dataset
- ⚡ Browser Automation using Playwright
- 🐍 Built with Python

---

## 🛠️ Technologies Used

- Python 3.x
- Playwright
- Regular Expressions (re)
- Kaggle
- VS Code

---

## 📂 Project Structure

```text
web_scrapping_project/
│
├── app.py
├── scrapper.py
│
├── dataset/
│   ├── Airline Dataset.csv
│   ├── Airline Dataset Updated.csv
│   └── Airline Dataset Updated - v2.csv
│
└── README.md
```

---

## 📦 Installation

### Clone the repository

```bash
git clone https://github.com/4ditinotreal/web_scrapping_project.git
```

Move into the project folder:

```bash
cd web_scrapping_project
```

Install the required packages:

```bash
pip install playwright
```

Install Playwright browsers:

```bash
playwright install
```

---

## ▶️ Running the Project

Execute the application:

```bash
python app.py
```

The application will:

1. Open Kaggle.
2. Sign in using your credentials.
3. Search for the specified dataset.
4. Download the dataset.
5. Save it to the local project folder.

---

## 📁 Example Dataset

This project demonstrates downloading the **Airline Dataset** from Kaggle automatically.

Downloaded files are stored in the **dataset/** folder.

---

## 📸 Screenshots

You can add screenshots of:

- Login Page
- Dataset Search
- Download Process
- Downloaded Dataset

inside this section.

---

## 📌 Requirements

- Python 3.10 or later
- Playwright
- Internet Connection
- Kaggle Account

---

## 🔮 Future Improvements

- Support multiple datasets
- Add graphical user interface (GUI)
- Export logs
- Automatic dataset updates
- Error handling and retry mechanism

---

## 👨‍💻 Author

**Aditi Thul**

GitHub: https://github.com/4ditinotreal

---

## 📄 License

This project is licensed under the MIT License.