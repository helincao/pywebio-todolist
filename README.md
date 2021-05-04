<h1 align="center"><strong>To-Do List</strong></h1>

<p align="center">
  <img src="https://imgur.com/YvFny7S.png">
</p>
<br />

# Motive

A to-do list made using [PyWebIO](https://github.com/wang0618/PyWebIO), a Python library that provides a series of imperative functions to obtain user input and output on the browser.

The input function of PyWebIO is blocking, and the output function will output content to the user in real-time.

By default, PyWebIO uses WebSocket protocol for server-browser communication. Though, one can easily opt to use HTTP polling instead for server-browser communication.
With PyWebIO, I was able to build an interactive web app simply with just Markdown, without the need to have knowledge of HTML and JS.

# Changes

1. Deployment method: The original project was made for Heroku deployment. Here we only keep the main function.
2. Support to data persistence. Saving tasks[] data to a local file.
3. Re-organize the table display logic.
