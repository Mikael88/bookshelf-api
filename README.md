# Bookshelf API

The Bookshelf API is a simple API for managing a collection of books. It allows users to add, retrieve, update, and delete books from the bookshelf. Additionally, it provides features such as filtering books by name, reading status, and finished status.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the Server](#running-the-server)
  - [API Endpoints](#api-endpoints)
- [Features](#features)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- [npm](https://www.npmjs.com/) (Node Package Manager) to manage project dependencies.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/bookshelf-api.git
```

2. Navigate to the project directory:

```bash
cd bookshelf-api
```

3. Install dependencies:

```bash
npm install
```

## Usage

### Running the Server

To start the Bookshelf API, use the following command:

```bash
npm run start
```

The server will run on port 9000 by default. If needed, you can change the port in the `src/server.js` file.

### API Endpoints

- **POST /books**: Add a new book to the bookshelf.
- **GET /books**: Retrieve a list of books based on optional query parameters (`name`, `reading`, `finished`).
- **GET /books/{bookId}**: Retrieve details of a specific book by ID.
- **PUT /books/{bookId}**: Update the details of a specific book by ID.
- **DELETE /books/{bookId}**: Delete a book from the bookshelf by ID.

## Features

- **Add Book**: Add a new book to the bookshelf with various details.
- **Get All Books**: Retrieve a list of books with optional filtering.
- **Get Book by ID**: Retrieve details of a specific book by its unique ID.
- **Update Book**: Modify the details of a book based on its ID.
- **Delete Book**: Remove a book from the bookshelf by its ID.
