# Overview
I had based on project 4 : develop and deploy serverless app create, get and update information

# Run local on browser
- cd to /client folder
- npm install
- npm start
- open http://localhost:3000/

# TEST API WITH POSTMAN
import file (Final Project.postman_collection.json) into postman (update region from us-east-1 to us-east-2 and update {{apiId}}: kevy8v1g5f )

# TEST BROWSER
Get list images by User:
<img width="1440" alt="Screenshot 0004-08-20 at 23 42 50" src="https://user-images.githubusercontent.com/37759418/185757641-03020655-362e-4945-bab1-458a71979e20.png">

# AWS Cloud Formation
<img width="1440" alt="Screenshot 0004-08-20 at 23 44 09" src="https://user-images.githubusercontent.com/37759418/185757698-468a4713-8879-4f7a-b64b-f7c5cf4ce781.png">
<img width="1440" alt="Screenshot 0004-08-20 at 23 44 00" src="https://user-images.githubusercontent.com/37759418/185757704-24ca52de-1ae9-4751-beb2-8b94d0f3dde4.png">


# Auth0-capstone-app
![Uploading Auth0_capstonse_app.png…]()

# Serverless App
<img width="1440" alt="serverless_todo_app_1" src="https://user-images.githubusercontent.com/37759418/185757845-cd3ed548-8141-4632-b09c-9ce1b8401a23.png">
<img width="1440" alt="serverless_todo_app_2" src="https://user-images.githubusercontent.com/37759418/185757854-f3bc1a23-290e-44a1-a552-3ea7e656d916.png">
<img width="1440" alt="serverless_todo_app_3" src="https://user-images.githubusercontent.com/37759418/185757858-79efceff-0dad-4a53-9189-dcb2fc0f5cec.png">

# Service Map
<img width="1440" alt="xray_service_map" src="https://user-images.githubusercontent.com/37759418/185757873-aaf9693f-b17a-47eb-ae7e-515689650b5a.png">

<img width="1440" alt="servicemap_monitoring" src="https://user-images.githubusercontent.com/37759418/185757890-1e537c32-c342-420d-858c-c08fd8a58ab9.png">

# Trace
<img width="1440" alt="xray_trace" src="https://user-images.githubusercontent.com/37759418/185757905-6023a0a3-fff0-420c-b61e-38b266c95073.png">
<img width="1440" alt="cloudwatch_trace" src="https://user-images.githubusercontent.com/37759418/185757913-30fef3ef-7952-40a1-aebd-853fa8265388.png">


# API endpoint
- GET - https://kevy8v1g5f.execute-api.us-east-2.amazonaws.com/dev/todos
- POST - https://kevy8v1g5f.execute-api.us-east-2.amazonaws.com/dev/todos
- PATCH - https://kevy8v1g5f.execute-api.us-east-2.amazonaws.com/dev/todos/{todoId}
- DELETE - https://kevy8v1g5f.execute-api.us-east-2.amazonaws.com/dev/todos/{todoId}
- POST - https://kevy8v1g5f.execute-api.us-east-2.amazonaws.com/dev/todos/{todoId}/attachment
