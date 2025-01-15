# DevOps_Assignment3
This is a part of Assignment#03 - Communication between Microservices (2025-DevOps and Microservices Course)

Modify the example-4 codes (call it example-5) such that (after the command "docker-compose up --build") you could 
- hit http://localhost:4001/video?id=1 in your browser, then you should see "a short video 1" (an mp4 file streaming - may be the same mp4 file that we already have) on the browser, and the history microservice will insert a new entry (viewed-1) in the videos collection in the MongoDB, and the recommendation microservice prints out "recommendation video 1" to the console.
- hit http://localhost:4001/video?id=2 in your browser, then you should see "a short video 2" (another mp4 file streaming) on the browser, and the history microservice will insert a new entry (viewed-2) in the videos collection in the MongoDB, and the recommendation microservice prints out "recommendation video 1" to the console.
