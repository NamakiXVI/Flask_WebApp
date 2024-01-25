1. install all the requirements from the project by using the command:
  on Windows: pip install -r requirements.txt
  on MacOS/Linux: pip3 install -r requirements.txt

2. run the application by using the command:
  on Windows: python main.py
  on MacOS/Linux: python3 main.py

3. the Web App will run on the port 5000, so if you want to see the Website you have to
  open it with the link localhost:5000 or 127.0.0.1:5000.

  the paths of my Web App:

  "/chat": it will open my own chat web application, where you can sign in first and
  automatically get passed on to the path "/chat/<username>" where you are in the chatroom.

  "/": this is the origin link without a path and it is a project from myself where you can translate any
  sentence into any language using the ISO-3166-1 codes.

  "/latest_request/get_json=format:api=request" or "localhost:5000/latest_request/get_json=format:api=request":
  this path has a familiar function like an api, where you can get all the informations of the last send request
  from the translator project in json when you send a request to this path / url and get a json format as response.
  

  "/chat/get_json=format:401" or "localhost:5000/chat/get_json=format:401": this path is basically the same like the
  previous path but it will send you the data from the last message from my chat web app in a json format if you send
  the request. It also contains the location and the ip address of the user who wrote the message.

  the last to paths of my Web App are always sending an response in status code 401 which means that it 
  indicates that the request lacks proper authentication credentials or the provided credentials are invalid,
  but dont worry about that because it was made on purpose so that the api can send it as a json format.

  

  
