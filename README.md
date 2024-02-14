# Simple HTTP Server With Go 

## Description
Welcome to the project! This is a Web Server With Golang. hope you enjoy and I look forward to your contributions!

### Prerequisites
1. install Go 
2. a IDE (Depend on you)

### Running the code
#### To run this code on your machine, follow these steps:
1. Save the code to a file with a “.go” extension (e.g., main.go). -

2. Open your terminal or command prompt and navigate to the directory containing the file.

3. Compile and run the code by entering the command:
```
go run main.go
```
#### Once the server is up and running, you can access the contents of the specified directory by visiting http://localhost:8000/ in your web browser.
and also Navigate to URL http://localhost:8000/hello and  http://localhost:8000/form

##Flow chart

```mermaid
graph TD;
    SERVER-->/;
    SERVER-->/hello;
    SERVER-->/form;
    /-->index.html;
    /hello-->hello func;
    /form-->form;
    /func-->form.html
```



### Contributing
Pull requests are welcomed. For major changes, please open an issue first to discuss what you would like to change. Thanks!

Happy Coding!!!

### Copyright
© KAVINDU™ | 2024

