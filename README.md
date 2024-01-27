# Kanye Says...

This simple Python script utilizes the `tkinter` library to create a basic graphical user interface (GUI) that displays random quotes from Kanye West. The quotes are fetched from the "https://api.kanye.rest" API using the `requests` library.

## Prerequisites

Make sure you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).

Additionally, you need to install the `requests` library. You can install it using the following command:

```bash
pip install requests
```

## How to Run

1. Clone the repository or download the script files.

```bash
git clone https://github.com/your-username/kanye-says.git
cd kanye-says
```

2. Run the script:

```bash
python kanye_says.py
```

## Usage

- Upon running the script, a GUI window titled "Kanye Says..." will appear.
- The window displays a background image with a default quote and a button featuring Kanye West's image.
- Clicking the Kanye button will trigger a request to the "https://api.kanye.rest" API to fetch a new random quote, updating the displayed quote on the GUI.

## Files

- `kanye_says.py`: The main Python script containing the GUI code.
- `background.png`: Background image for the GUI.
- `kanye.png`: Image of Kanye West for the button.

## Credits

- **Kanye Rest API**: [https://api.kanye.rest](https://api.kanye.rest)
- **tkinter Documentation**: [https://docs.python.org/3/library/tkinter.html](https://docs.python.org/3/library/tkinter.html)

Feel free to customize and enhance the script as needed!
