1. Project Overview
  This project contains:
  A Data Structures & Algorithms problem (first non-repeating character in a string).
  A Course Rating System API built using Java + Spring Boot.
   The API allows users to submit ratings for courses and retrieve the average rating.

2. Tech Stack
   Java 17
   Spring Boot 3.x
   Maven
   Embedded Tomcat

3. How to Run the Project
    Prerequisites
       Java 17 or higher installed
       Maven installed
    Steps:
   1. Clone the repository
   2. navigate into project
   3. build and run
   4. application will start on  "http://localhost:8080"

4. API Endpoints
    POST /courses/{courseId}/rating
    http://localhost:8080/courses/101/rating?userId=1&rating=5
    GET /courses/{courseId}/rating
    http://localhost:8080/courses/101/rating

5. Data Structure problem Explanation
   I used a fixed-size array of 256 elements to store character frequencies instead of a HashMap to improve time efficiency and avoid extra object overhead. This       allows constant-time access and keeps the algorithm simple.
