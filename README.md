# Attendance-with-Deep-Learning
Take attendance of your employees and students with Machine Learning

<img src="https://5.imimg.com/data5/WP/CR/MY-10190404/face-recognition-based-attendance-system-500x500.jpg" />

# Install
 You can use any face_recognization algorithm here.. but I used this. ```pip3 install face_recognition```
 
 You can do same things in Raspberry pi



# Use

Train the model by feeding images. ( One Image per person is enough to get 99% accuracy )

```

# Load a second sample picture and learn how to recognize it.


biden_image = face_recognition.load_image_file("rutul.jpg")
biden_face_encoding = face_recognition.face_encodings(biden_image)[0]

mark_image = face_recognition.load_image_file("mark.jpg")
mark_face_encoding = face_recognition.face_encodings(mark_image)[0]

barry_image = face_recognition.load_image_file("barry.jpg")
barry_face_encoding = face_recognition.face_encodings(barry_image)[0]

venus_image = face_recognition.load_image_file("venus.jpg")
venus_face_encoding = face_recognition.face_encodings(venus_image)[0]

#Label your inputs 
known_face_encodings = [
    obama_face_encoding,
    biden_face_encoding,
    mark_face_encoding,
    barry_face_encoding,
    venus_face_encoding
]
known_face_names = [
    "Barack Obama",
    "Rutul Patel",
    "Mark Yaraskavitch",
    "Barry Morwood",
    "Venus Vavadiya",
]

````

# Get the results
You can get all the attendance result in this array 

```
# At the end just print this to the one file if you want..

all_time_faces_names = []


```
