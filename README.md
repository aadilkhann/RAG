To install the packages listed in a `requirements.txt` file using `pip`, follow these steps:

1. **Navigate to the directory** where your `requirements.txt` file is located.

2. **Run the following command** in your terminal or command prompt:

```bash
pip install -r requirements.txt
```

This command will install all the dependencies specified in the `requirements.txt` file.

### Troubleshooting Tips:

* **Ensure you're using the correct Python version**: If you're using Python 3, make sure to use `pip3` instead of `pip` (depending on your system):

  ```bash
  pip3 install -r requirements.txt
  ```

* **Create a virtual environment** (optional but recommended) to avoid conflicts with other Python projects:

  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
  pip install -r requirements.txt
  ```
