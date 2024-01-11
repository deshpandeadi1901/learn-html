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
   Ans: The action tag defines the URL to which the data of the form is to be sent. 

2. What is the purpose of the _method_ attribute in the _form_ tag?
   Ans: The method attribute specifies the HTTP method such as GET or POST to be used while sending the form data to the server.

3. What is the purpose of the _name_ attribute in the _input_ tag?
   Ans: The name attribute is used to uniquely identify a particular data in the server when the form is submitted. 

4. What is the purpose of the _type_ attrbute in the _input_ tag?
   Ans: The purpose of the type attribute is to define the behaviour and appearance of an input field. For example: textbox, checkbox, password, etc. 

5. What is the purpose of the _label_ tag?
   Ans: The purpose of the label tag is to define the name of the input field. It helps the user to understand what input is expected.

6. What is the purpose of the _required_ attribute?
   Ans: The purpose of the required attribute is to make a particular input field to be filled compulsorily before submitting the form. 

