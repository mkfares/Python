Python may be used in two forms:

### Interactive Mode (Python shell)

To start using Python in interactive mode, you need to open the Command Prompt on Windows or the Terminal on macos or Linux.

Once the app is opened, type python or python3.
```
$ python
```
The above command shows a message including the python version and additional information. 
```
Python 3.7.2 (v3.7.2:9a3ffc0492, Dec 24 2018, 02:44:43) 
[Clang 6.0 (clang-600.0.57)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
The `>>>` is called the prompt where you may type python statements.

To try an example of python statements; after typing this statements, press Enter key.
```python
>>> print("Hello, World!")
```
Once the statement is executed, Python shows the prompt `>>>` again to indicate that is ready to take another statement.

To quit the interactive mode, you may type
```python
>>> quit()
```
Or use the keyboard shorcuts **Ctrl + D**

The interactive mode is also available through the Python Integrated Development Environment (IDLE)

### Script Mode (Python programs)
Interactive mode is used maily for learning Python or testing statements. If you want to write programs and save your work in files then execute them later, you should use the python script mode (normal mode).

To write Python scripts or programs, you need to use a text editor. There are basic editors such as Notepad and advanced editors such as [ATOM](https://atom.io/).

A example of writing Python programs process

1. Open the text editor

2. Write your program

3. Save your program in a file with extension .py (e.g. hello.py)

4. Run the program using the command
    ```python
    >>> python hello.py
    ```

The Python IDLE has a built-in text editor. To use this provided text editor

1. Open Python IDLE application

2. From the File menu, click on the New File to create a new file (or Open... in case you want to open an existing file)

3. In the text editor window, type your code; for instance
    ```python
    print(Hello")
    ```

4. To save your program, click on the File menu then Save or use the keyboard shortcut Ctrl+S on Windows and Cmd+S on macOS

5. Choose the folder where you want to store the file and provide a name for your file (e.g. hello.py)

6. To run the program, click on the Run menu, then Run Module or press F5 key. To see the Run menu, the editor window should be active or in focus. After running the program, you should see the output in Python Shell window.
        ```python
        =================== RESTART: /Users/user/Desktop/hello.py ===================
        Hello
        >>> 
        ```

