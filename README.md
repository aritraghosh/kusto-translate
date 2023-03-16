**This project is a fork from [SQL translator](https://github.com/whoiskatrin/sql-translator)** 


# KQL Translator
KQL stands for [Kusto Query language](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/). It is used widely to interact with data stored in Azure Data explorer

KQL Translator is a tool for converting natural language queries into KQL code using artificial intelligence. This project is 100% free and open source.


## Features

- dark more
- lowercase/uppercase toggle
- copy to clipboard
- SQL syntax highlighting
- schema awareness (beta)

## Roadmap

- functions and procedures
- support for languages other than English

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/aritraghosh/kusto-translate.git
    ```

2. Install the required packages:

    ```bash
    cd sql-translator
    npm install
    npm build run
    ```
3. Input your OPENAI API key in the .env file, you can get your API key [here](https://beta.openai.com/account/api-keys):


    ```bash
    OPENAI_API_KEY=$YOUR_API_KEY
    ```

4. Start the development server:

    ```bash
    npm start
    ```

## Usage

Once the development server is running, you can access the application by navigating to `http://localhost:3000` in your web browser.

Enter a natural language query in the input box and click "Translate" to generate the corresponding KQL code. The generated KQL code will be displayed in the output box.

## Contributing

Contributions to KQL Translate are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Push your changes to your fork
5. Submit a pull request

## License

KQL Translator is released under the MIT License.
