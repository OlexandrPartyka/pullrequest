# pullrequest
IPZs-23-1 Partyka Olexandr

# Pull Request Server

This server is developed to handle requests for creating pull requests. It accepts POST requests to the path `/pull-request` and returns a message confirming the successful creation of a pull request.

## Usage

To use this server, you need to have Node.js installed on your computer. You can clone this repository and start the server using the following commands:

1. Clone the repository:

git clone https://github.com/.../....git

2. Navigate to the project folder:

cd your-repo

3. Install dependencies:

npm install

4. Start the server:

node server.js

The server will be running on port 3000. You can make a POST request to http://localhost:3000/pull-request with JSON data to create a pull request.

## Example POST Request

{
    "title": "Pull Request Title",
    "description": "Pull Request Description",
    "author": "Author's Name",
    "repository": "Repository Name"
}

## Contribution

Feel free to open issues and pull requests to contribute to this project.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


