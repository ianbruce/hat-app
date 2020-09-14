# Hat App

Make a webserver that, given a web request with a picture of a person in the payload, returns the same picture but with a hat on the person's head.

## Implementation Ideas

- **For the webserver**: A webserver is a program that runs forever, and whenever someone sends an HTTP request to it, it sends an HTTP response. A good webserver library in Python that makes it easy to make a webserver is a library called Flask.
- **You need to figure out how to add a picture to another picture**: There's a library called Pillow that gives you this capability
- **You need to figure out where to put the hat in the picture**: What pixel location will you put the hat at? This is the machine learning part.