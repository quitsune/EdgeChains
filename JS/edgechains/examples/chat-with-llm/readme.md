## Video

    ```
    https://drive.google.com/file/d/1y0tGZx9HnjZpWlMmJW-6Yt1fW9lXpxFD/view
    ```

# Chat with LLM Example

## Installation

1. Install the required dependencies:

    ```bash
    npm install
    ```

## Configuration

1 Add OpenAiApi key in secrets.jsonnet
`bash
    local OPENAI_API_KEY = "sk-****";
    `

## Usage

1. Start the server:

    ```bash
    npm run start
    ```

2. Hit the `POST` endpoint with basic question `http://localhost:3000/chat`.

    ```bash

    body = {
        "question":"hi"
    }
    ```
