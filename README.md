# ImageHashScanner 🔍🖼️

A powerful, fast, and user-friendly web application built with Python (Flask) that scans your local computer for images and identifies exact duplicates using MD5 hashing. 

With a modern HTML/CSS/JS frontend, it provides a clean interface to view, filter, and manage your image library, ensuring your storage isn't wasted on duplicate files.

## ✨ Features

* **Robust MD5 Hash Detection:** Reads files in 64KB chunks to efficiently compute MD5 hashes, ensuring 100% accuracy in detecting exact duplicate files regardless of their file names.
* **Extensive Format Support:** Detects almost all image formats including `JPG`, `PNG`, `GIF`, `WEBP`, `TIFF`, `HEIC`, `AVIF`, and RAW formats (`CR2`, `NEF`, `ARW`).
* **Live Scanning Progress:** Features a real-time progress bar that displays the current file being scanned and the overall scan progress.
* **Smart Filtering:** Easily toggle between viewing **All Images**, **Duplicates**, or **Unique** files.
* **Grid & List Views:** Flexible UI offering both a visually appealing thumbnail grid and a detailed list view.
* **Duplicate Groups Modal:** Click on a duplicate image to open a modal that groups and displays all identical files sharing the same MD5 hash.
* **Real-time Statistics Panel:** Keep track of your library with a dashboard showing Total Images, Unique Count, Duplicate Count, and Total Duplicate Groups.

## 🛠️ Tech Stack

* **Backend:** Python 3, Flask
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Hashing Algorithm:** MD5 (via Python's `hashlib`)

## 🚀 Getting Started

Follow these steps to run the application on your local machine.

### Prerequisites
Make sure you have [Python 3.x](https://www.python.org/downloads/) installed on your computer. 

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/ImageHashScanner.git](https://github.com/your-username/ImageHashScanner.git)
   cd ImageHashScanner

####  Install dependencies:

It is recommended to use a virtual environment. Install the required Python packages using pip:
  ```bash
  pip install -r requirements.txt

####  Run the application:
    python app.py

#### Open in Browser:
Open your favorite web browser and navigate to:
  http://localhost:5050
