# Go URL Shortener

This URL Shortener is a simple web application written in Go that allows users to shorten long URLs just like Bit.ly and other similar services. It provides basic functionality to shorten a URL and then redirect to the original URL when the shortened version is accessed.

## Features

- **Shorten URLs**: Convert long URLs into manageable short links that redirect to the original URLs.
- **Redirect**: Use the short link to redirect users to the original long URL.
- **Simple UI**: A basic form to input URLs that need to be shortened.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need Go installed on your machine. To install Go, you can follow the instructions here: https://golang.org/doc/install

### Running the Application

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/go-url-shortener.git

2. Navigate to the cloned directory:
   ```bash
   cd go-url-shortener

3. Build the project
   ```bash
   go build -o urlshortener

4. Run the application:
   ```bash
   ./urlshortener

5. Open a web browser and visit http://localhost:3030 to start using the URL Shortener.

## Usage

- To shorten a URL, enter the full URL in the input box on the main page and click "Shorten".
- You will be redirected to a page showing the original and the shortened URL.
- Access the shortened URL in any browser to be redirected to the original URL.

## Future Iterations

- Persistent Storage: Implement a database to store URL mappings permanently. Currently, the application loses its data upon restart

- Analytics: Track how many times each shortened URL is visited.

- Custom Short URL: Allow users to choose custom short URLs.

- User Accounts: Implement user authentication to let users track their URLs and view statistics.

