# boost-beast-rest
#### How to run the Rest server:
```
Ensure your boost libraries are linked correctly(Beast and Asio)
From the root directory run the following commands in order
```
1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./ResfulApi
```
In a separate terminal run the command
```
6. curl http://localhost:8080  

## Original article written by Alexander Obregon:
https://medium.com/@AlexanderObregon/building-restful-apis-with-c-4c8ac63fe8a7