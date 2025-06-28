# 📚 gutendex-data-transform

> A PySpark-based data transformation pipeline that pulls and processes book data from the Gutendex API.

---

## 🚀 Project Overview

This project implements a data transformation pipeline using **PySpark** to extract, clean, and transform book metadata and texts obtained from the [Gutendex API](https://gutendex.com/). The focus is on the transformation stage — preparing raw data into structured formats ready for analysis, storage, or further processing.

This repository serves as a foundational step towards building a full ETL pipeline.

---

## 🎯 Features

- Pulls raw book data from the Gutendex API  
- Efficient transformations using distributed PySpark jobs  
- Cleans and enriches data (e.g., filtering, normalization)  
- Modular code organized for scalability and extensibility  
- Easily configurable input/output paths  
- Ready for integration with extraction and loading steps  

---

## 📁 Repository Structure

```
gutendex-data-transform/
│
├── data/                   # Placeholder for raw and transformed data
├── notebooks/              # Jupyter notebooks for experimentation
├── src/                    # PySpark transformation scripts and modules
├── tests/                  # Unit and integration tests (optional)
├── .gitignore              # Ignore rules for Git
├── LICENSE                 # MIT License
├── README.md               # Project overview and instructions
└── environment.yml        # Conda environment configuration

````

---

## 🛠️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/gutendex-data-transform.git
cd gutendex-data-transform
````

2. Create and activate a Conda environment:

```bash
conda env create -f environment.yml
conda activate gutendex-data-transform
```

---

## ⚙️ Usage

Run the main transformation script using Spark:

```bash
spark-submit src/transform.py --input data/raw/gutendex.json --output data/transformed/
```

Modify paths and parameters as needed.

---

## 🔮 Future Enhancements

* Add API extraction and data loading components to complete the ETL
* Support cloud storage integration (AWS S3, Azure Blob, etc.)
* Implement pipeline orchestration (Airflow, Prefect)
* Add comprehensive testing and continuous integration
* Expand transformation logic with additional enrichment features

---

## 🤝 Contribution

Contributions are welcome! Please fork the repo and open pull requests.
Consider adding a `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md` for smoother collaboration.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

**Priyesh Gupta**  
Email: [priyeshgupta83@gmail.com](mailto:priyeshgupta83@gmail.com)  
GitHub: [https://github.com/Kalinga07](https://github.com/Kalinga07)

---

✨ *Happy transforming!*

