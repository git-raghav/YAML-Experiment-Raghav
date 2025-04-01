# YAML Student Data Manager

A Python application that demonstrates the practical use of YAML files for data management, specifically handling student information. This project showcases how to read, process, and filter data from YAML files using Python.

## 🚀 Features

-   **YAML Data Loading**: Efficiently reads and parses student information from a YAML file
-   **Student Information Display**: Shows comprehensive details of all students including:
    -   Name
    -   Age
    -   Major
    -   GPA
-   **GPA Filtering**: Allows filtering students based on minimum GPA threshold
-   **Clean Code Structure**: Well-organized code with separate functions for different operations
-   **Error Handling**: Includes basic error handling for file operations and data processing

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

-   Python 3.x
-   pip (Python package installer)

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/git-raghav/YAML-Experiment-Raghav.git
cd YAML-Experiment-Raghav
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Run the application:

```bash
python app.py
```

2. The application will:
    - Display all students and their information
    - Prompt you to enter a minimum GPA
    - Show filtered results of students meeting the GPA criteria

## 📊 Data Structure

The `students.yaml` file follows this structure:

```yaml
students:
    - name: <student_name>
      age: <age>
      major: <major>
      gpa: <gpa>
```

### Example Data:

```yaml
students:
    - name: Alice
      age: 21
      major: Computer Science
      gpa: 3.8
    - name: Bob
      age: 22
      major: Mathematics
      gpa: 3.5
```

## 🔍 Code Structure

The application consists of several key functions:

-   `load_data(file_path)`: Loads and parses the YAML file
-   `display_students(students)`: Displays all student information
-   `filter_students_by_gpa(students, min_gpa)`: Filters students based on GPA
-   `main()`: Orchestrates the program flow

## 📝 Example Output

When you run the application, you'll see output similar to this:

```
All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: David, Age: 23, Major: Chemistry, GPA: 3.2
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7

Enter minimum GPA to filter students: 3.6
Students with GPA >= 3.6:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7
```
![screenshot](/assets/Screenshot%202025-04-01%20155042.png)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Author

-   Raghav

## 🙏 Acknowledgments

-   PyYAML library for YAML processing
-   Python community for excellent documentation and support
