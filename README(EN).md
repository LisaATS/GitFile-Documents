Certainly, here's the English version of the example:

```markdown
# Project Name

## 1. Project Overview

### 1.1 Project Description

This is a sample project to demonstrate the structure and content of a project README file. The goal of the project is to showcase how to organize and document an open-source project effectively.

### 1.2 Project Status

The current status of the project is **In Development**. We are actively adding new features and improvements.

## 2. Installation and Running

### 2.1 Dependencies

Ensure that the following dependencies are installed on your system:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/)

### 2.2 Environment Setup

1. Clone the project repository locally:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repo
    ```

3. Install project dependencies:

    ```bash
    npm install
    ```

### 2.3 Installation Steps

Follow these steps to install the project and prepare for running:

1. Create a `.env` file in the project root with the necessary environment variables:

    ```env
    API_KEY=your_api_key
    DATABASE_URL=your_database_url
    ```

   Replace `your_api_key` and `your_database_url` with the actual API key and database URL.

2. Run database migration:

    ```bash
    npm run migrate
    ```

### 2.4 Running the Project

Now, you can start the project:

```bash
npm start
```

Visit [http://localhost:3000](http://localhost:3000) to see the project in action.

**Note:** If there are any specific settings or configuration steps, please refer to the project documentation for detailed instructions.

## 3. Directory Structure

```
.
├── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   └── index.js
├── public/
├── .gitignore
├── package.json
└── README.md
```

The main directory structure of the project is as shown above. The `src/` directory contains the source code, `public/` contains public files, `.gitignore` specifies files or directories to be ignored, `package.json` contains project configuration.

## 4. Usage Guide

### 4.1 Examples

Examples will be provided shortly.

### 4.2 Advanced Usage

More advanced usage will be added in future versions.

## 5. Contribution Guidelines

### 5.1 Reporting Issues

If you encounter any issues, please report them on the [Issues page](https://github.com/your-username/your-repo/issues) and be sure to provide detailed steps and environment information.

### 5.2 Submitting Pull Requests

Refer to the [Contribution Guidelines](CONTRIBUTING.md) for information on how to submit pull requests, including code style and testing requirements.

### 5.3 Contributor Code of Conduct

Follow the project's [Contributor Code of Conduct](CODE_OF_CONDUCT.md) to maintain a friendly and collaborative development environment.

## 6. Version Control

### 6.1 Version History

- **v1.0.0 (2023-01-01):**
  - Initial version release.

### 6.2 Roadmap

Next steps include adding user authentication and optimizing the interface design.

## 7. License

This project is licensed under the [MIT License](LICENSE).

## 8. Contact Information

For any questions or suggestions, please contact us via email: your.email@example.com.

## 9. Demo and Screenshots

Demos and screenshots will be provided soon.

## 10. Documentation Links

- [Online Documentation](https://docs.example.com)
- [Wiki Page](https://github.com/your-username/your-repo/wiki)

## 11. CI/CD Status

[![Build Status](https://github.com/your-username/your-repo/actions/workflows/ci.yml/badge.svg)](https://github.com/your-username/your-repo/actions/workflows/ci.yml)
```

Feel free to modify this example based on your project's specific details and requirements.
