# FAT12 File System Reader

This project is a Python-based implementation of a FAT12 File System reader. It was developed as part of the Data Structures course to understand how data is organized and stored on a disk.

##  Features
* **Binary Image Parsing:** Reads and processes the `sample.img` binary file.
* **Boot Sector Analysis:** Extracts critical disk information (Bytes per sector, sectors per cluster, etc.).
* **Directory Listing:** Navigates the Root Directory to list all stored files and folders.
* **Data Retrieval:** Follows cluster chains in the FAT table to read full file contents.

##  File Descriptions
* **fat-file-system.ipynb:** The main Jupyter Notebook containing the Python implementation.
* **sample.img:** A sample FAT12 disk image used for testing and validation.
* **fatspec.pdf:** Technical specification document for the FAT file system.

##  Requirements
* Python 3.9
* Jupyter Notebook or VS Code (with Jupyter extension)

## 📖 How to Run
1. Clone or download this repository.
2. Ensure `sample.img` is in the same directory as the notebook.
3. Open `fat-file-system.ipynb` and run the cells sequentially.

