# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone git@github.com:mosad2/Mynote-app-.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`

`sudo apt install nginx`

![mmmm](https://user-images.githubusercontent.com/63494835/228964675-66ce9d11-0f0c-48ad-9de2-9402f54f111a.png)
