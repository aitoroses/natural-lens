# Natural Lens

Unlock the power of your database with **Natural Lens**! This innovative command-line interface (CLI) tool not only downloads database schemas but also generates insightful profiles using cutting-edge AI technology. Say goodbye to tedious data analysis and hello to intelligent insights!

<img src="./logo.png" alt="Natural Lens Logo" width="200" height="200">

## Features

- **Effortlessly Download Schemas**: Quickly fetch database schemas from PostgreSQL with a single command.
- **Instant Sample Data**: Automatically retrieve and save sample data for each table, ready for analysis.
- **AI-Powered Insights**: Generate detailed profiles for each table, revealing hidden patterns and insights.
- **User-Friendly CLI**: Enjoy a seamless command-line experience designed for both beginners and experts.

## Requirements

- Python 3.6 or higher
- OpenAI API key

## Installation

1. Install the package using pip:
   ```bash
   pip install natural-lens
   ```
2. Set your OpenAI API key as an environment variable:
   ```bash
   export OPENAI_API_KEY='your_openai_api_key'  # On Windows use: set OPENAI_API_KEY='your_openai_api_key'
   ```

## Usage

The CLI will be available as `nlens`. Run the following command to see the available options:

```bash
nlens --help
```

Refer to the [Northwind Example](./examples/northwind/README.md) to test **Natural Lens** with a sample PostgreSQL database.

## Troubleshooting

- **Error: Connection failed**: Ensure that your database credentials are correct and that the database server is running.
- **Error: OpenAI API key not set**: Make sure you have set your OpenAI API key as an environment variable.

## Contributing

We love contributions! Whether you have a bug fix, a new feature, or just a suggestion, your input is invaluable. Join our community and help us make **Natural Lens** even better!

1. Fork the repository.
2. Create a new branch.
3. Make your changes and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. The MIT License allows for reuse within proprietary software, as long as the license is distributed with that software.

## Acknowledgments

- [OpenAI](https://openai.com/) for providing the AI capabilities.

## Get Started Today!

Ready to unlock the potential of your database? Clone the repository, set up your environment, and start exploring the world of intelligent data analysis with **Natural Lens**!
