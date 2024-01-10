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
> The endpoint to which the form needs to send the information collected in the form fields
2. What is the purpose of the _method_ attribute in the _form_ tag?
> The kind/type of request to use while submitting the form
3. What is the purpose of the _name_ attribute in the _input_ tag?
> To determine the field name when the form is sent to the server
4. What is the purpose of the _type_ attrbute in the _input_ tag?
> To indicate the type of input field in the form
5. What is the purpose of the _label_ tag?
> To display a label to the user on the browser
6. What is the purpose of the _required_ attribute?
> To enforce that the field be filled by the user before the form is submitted

