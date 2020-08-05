# CSE_Moodle_API
## API made for the BUET CSE Moodle \
Original work by :Shanjinur Islam Spondon

git clone this repository or download zip. Then open with cmd and start the node server. 
Then with any http req website send the http requests. Can use Reqbin or postman.
According to this server the listener is set at localhost port 8000

## Features

### Log in
url: localhost:8000/login\
Method: POST\
Content: {"username":"username","password":"password"}\

Result: a sesskey. save this for later reqs
### Courses
url: localhost:8000/courses\
Method: GET\
header: sesskey: sesskey
### Course details
url: localhost:8000/courses/id\
Method: GET\
header: sesskey: sesskey
### Site news
url: localhost:8000/sitenews\
Method: GET\
header: sesskey: sesskey
### Site news details
url: localhost:8000/sitenews/id\
Method: GET\
header: sesskey: sesskey
### Resource download
url: localhost:8000/resources\
Method: GET\
header: sesskey: sesskey
	url: url
### Logout
url: localhost:8000/logout\
Method: POST\
header: sesskey: sesskey
