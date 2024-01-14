## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
It is set to the URL. 
2. What is the purpose of the _method_ attribute in the _form_ tag?
It defines the HTTP method used when sending form data to the server.
It is set to "GET".
3. What is the purpose of the _name_ attribute in the _input_ tag?
It provides a name for the input field. When the form is submitted, the data from the input field is sent to the server with the name as the identifier.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
It specifies the type of input control being used.
5. What is the purpose of the _label_ tag?
This tag is used to associate a text label with a form control. 
It improves accessibility and user experience by providing a clickable label that focuses on or activates the associated input when clicked.
6. What is the purpose of the _required_ attribute?
It is a boolean attribute that specifies whether the user must fill out the input field before submitting the form.

