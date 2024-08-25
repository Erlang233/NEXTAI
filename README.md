# PDF Document Interaction Platform

This project allows users to upload, interact with, and query PDF documents in real-time. The application is built with React and Ant Design, offering a user-friendly interface and utilizing advanced AI technologies for efficient data retrieval and interaction.

## Project Overview

This platform is designed to facilitate seamless interaction with PDF documents, leveraging AI to enhance user experience and efficiency. Users can upload PDF files, query their content, and receive intelligent responses powered by OpenAI's GPT-3.5 Turbo API and Langchain technologies.

## Key Features

- **Interactive UI**: Developed using React and Ant Design, the platform provides a smooth, intuitive interface for users to upload and interact with PDF documents in real-time.
- **High-Performance Backend**: Implemented RESTful APIs using Express and Node.js, ensuring efficient and high-performance request handling.
- **Efficient Data Retrieval**: Utilizes an in-memory vector store to cache generated embeddings, enabling quick and effective data access.
- **AI Integration**: Integrated with OpenAI's GPT-3.5 Turbo API and Langchain technologies, resulting in a sophisticated AI Agent capable of loading, storing, and querying document content.

## Getting Started

### Prerequisites

To run this project, you will need:

- **Node.js** and **npm** installed on your machine.
- An **OpenAI API key** for accessing GPT-3.5 Turbo.
- SSH access configured in the `.env` file for secure deployment.

### Setting Up the Environment

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/pdf-interaction-platform.git
    cd pdf-interaction-platform
    ```

2. Install the required dependencies:
    ```bash
    npm install
    ```

3. Configure the `.env` file with your credentials:
    - **OPENAI_API_KEY**: Your OpenAI API key.
    - **SSH_KEY**: Ensure your SSH key is correctly configured here for secure access.

    Example `.env`:
    ```bash
    REACT_APP_OPENAI_API_KEY=your-openai-api-key
    SSH_KEY=your-ssh-key
    ```

4. Start the development server:
    ```bash
    npm start
    ```
   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

### Available Scripts

- **`npm start`**: Runs the app in development mode.
- **`npm test`**: Launches the test runner in interactive watch mode.
- **`npm run build`**: Builds the app for production in the `build` folder.
- **`npm run eject`**: Removes the single build dependency from your project. Use with caution as it is a one-way operation.

### Deployment

1. Build the application:
    ```bash
    npm run build
    ```

2. Deploy the `build` folder to your hosting service of choice.

For more detailed instructions on deployment, refer to the [Create React App deployment documentation](https://facebook.github.io/create-react-app/docs/deployment).

## Troubleshooting

- **`npm run build` fails to minify**: This is a common issue with some npm packages. Refer to the [troubleshooting guide](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify) for solutions.

## Learn More

- [React Documentation](https://reactjs.org/)
- [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [OpenAI API Documentation](https://beta.openai.com/docs/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
