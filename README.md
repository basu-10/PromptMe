# PromptMe
Inspired the subreddit: [r/WritingPrompts](https://www.reddit.com/r/WritingPrompts/), this platform, supports users to create account, post prompts and more.

### Its a lightweight server to host a prompt generating and sharing site.

> It's very much a work in progress; however usual operations like sign in/sign up/posting/viewing works. 
> <br>Features like posting stories with the user submitted prompts, is in the pipeline.

<br>

### **Tech stack** *('why this tech?')*:
* **Flask, Python** *(Flask with python, handles incoming requests, interacts with database,etc)*
* **Jinja, JS** *(Jinja's loop funtion, among others, is very helpful to show all entries in a DB dynamically.)*
* **HTML, CSS** *(CSS framework: Bootstrap5)*
* **SQLite3** *(lightweight, easy browsing with [DB Browser for SQLite](https://sqlitebrowser.org))*
* **flask-ngrok** *(easiest and lightest option to host from my old RaspberryPi)*
> *(ngrok free account doesnt support more than 8hrs or so of uptime. but script given to start it on your machine or in any containerized environment like Docker, Kubernetes.)*
