![Static Badge](https://img.shields.io/badge/Python%20Package-shadePy-%234584b6?logo=python&logoColor=white) 

# shadePy

## **Description**
**ShadePy is a simple and robust Python library that offers an easy and user-friendly method for managing colors in the terminal.**

## **Features**
- **Add Colors to Text** : Use ANSI codes to color the text in the terminal.
- **Add Background Colors** : Apply background colors to enhance text visibility.
- **Variety of Colors** : Includes standard and bright colors for optimal customization.

## **Prerequisites**
- **Python 3.x** installed on your machine

## **Installation Instructions**
Make sure you have [Python](https://www.python.org/downloads/) installed on your system before running the install command.

1. Install the ***shadePy*** package using **pip**..

    ```bash
    pip install shadePy

2. Import the Colors and Back classes from the shadePy package.

    ```python
    from shadePy import Colors, Back

## **Usage Examples**
3. Assign the colors to variables and use them to style your text.

    ```python
    RED = Colors.RED
    GREEN = Colors.GREEN
    BACK_GREY = Back.BRIGHTGREY
    RESET = Colors.RESET # Use 'Colors.RESET' to reset the colors after use

    print(f"{RED}ERROR: Your Private Key is invalid{RESET}") # Print text in red
    print(f"{GREEN}SUCCESS: Encryption completed successfully!{RESET}") # Print text in green
    print(f"{BACK_GREY}INFO: Search process in progress...{RESET}") # Print text on grey background

 All available colors are listed in the file [static.py](https://github.com/0x414854/shadePy/blob/main/shadePy/static.py)

## Tree Directory

shadePy/
<br> ├── dist/
<br>&nbsp;│&nbsp;&nbsp;├── shadePy-1.0.0-py3-none-any.whl
<br>&nbsp;│&nbsp;&nbsp;└── shadepy-1.0.0.tar.gz
<br> ├── shadePy/
<br>&nbsp;│&nbsp;&nbsp;├── __init__.py
<br>&nbsp;│&nbsp;&nbsp;└── static.py
<br>├── LICENSE
<br>├── pyproject.toml
<br>└── README.md

## **License**
This project is licensed under the **MIT License**.

## **Author**
[**0x414854**](https://github.com/0x414854)
