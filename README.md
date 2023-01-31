## Wether info
In this project We can easily find the wether information like Temperature , Humidity , max temp, min temp,
sunrises time etc of just enter the city name .

## Technology Used
 Python
- Tkinter
- API
- Json file

## Tkinter
Python has a lot of GUI frameworks, but Tkinter is the only framework that’s built into the Python standard library. Tkinter has several strengths. It’s cross-platform, so the same code works on Windows, macOS, and Linux. Visual elements are rendered using native operating system elements, so applications built with Tkinter look like they belong on the platform where they’re run.
Although Tkinter is considered the de facto Python GUI framework, it’s not without criticism. One notable criticism is that GUIs built with Tkinter look outdated. If you want a shiny, modern interface, then Tkinter may not be what you’re looking for.

## API
 An API, or Application Programming Interface, is a server that you can use to retrieve and send data to using code. APIs are most commonly used to retrieve data, and that will be the focus of this beginner tutorial.
When we want to receive data from an API, we need to make a request. Requests are used all over the web. For instance, when you visited this blog post, your web browser made a request to the Dataquest web server, which responded with the content of this web page.

Making API Requests in Python
In order to work with APIs in Python, we need tools that will make those requests. In Python, the most common library for making requests and working with APIs is the requests library. The requests library isn’t part of the standard Python library, so you’ll need to install it to get started.
If you use pip to manage your Python packages, you can install requests using the following:-
Pip install request

## Json file
JSON (JavaScript Object Notation) is a popular data format used for representing structured data. It's common to transmit and receive data between a server and web application in JSON format.

To read a JSON file, as we already saw, we will be using the json.load() function. But before we load some JSON objects from a file, we have to read it using Python’s open() built-in function.

Suppose we want to read the test.json file using the read_json.py script, we:

Import the json module.
Open test.json using the open() built-in function.
Load the JSON object inside the test.json file using the json.load() function.
Print out the values of the JSON object inside the test.json file.
