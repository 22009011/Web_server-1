# Developing a Simple Webserver

# AIM:

To develop a simple webserver to display top five web application development language.

## DESIGN STEPS:

### Step 1:

HTML content creation is done

### Step 2:

Design of webserver workflow

### Step 3:

Implementation using Python code

### Step 4:

Serving the HTML pages.

### Step 5:

Testing the webserver

## PROGRAM
from http.server import HTTPServer,Bas
```
<!DOCTYPE html>
<html>
<head>
<title>My Web server</title>
</head>
<h1>Top Five Web Application Framework</h1>
<h2>1.Django</h2>
<h2>2.MEAN Stack</h2>
<h2>3.React</he>
<h2>4.Angular</h2>
<h2>5.Express</h2>

</body>
</html>
"""
class MyServer(BaseHTTPRequestHandler):
    def do_GET(self):
        print('Get request received...')
        self.send_response(200)
        self.end_headers()
        self.wfile.write(content.encode())
          

print("This is my Webserver")
server_address =('',80)
httpd = HTTPServer(server_address,MyServer)
httpd.serve_forever()
```
## OUTPUT:
![WhatsApp Image 2022-12-13 at 8 23 44 PM](https://user-images.githubusercontent.com/118343461/207372321-ecdbac77-0a68-45f1-ba26-a0a6d1706783.jpeg)
![WhatsApp Image 2022-12-13 at 8 23 44 PM(1)](https://user-images.githubusercontent.com/118343461/207372444-444b477f-8ac2-47ca-bf07-1d74ff67feea.jpeg)


## RESULT:
The program is executed succesfully
