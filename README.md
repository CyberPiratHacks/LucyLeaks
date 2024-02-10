# BreachDirectory API Python Script

Este script em Python utiliza a API do BreachDirectory para realizar consultas de violações de dados usando endereços de e-mail. Ele exibe informações detalhadas sobre senhas e hashes associados ao e-mail fornecido, bem como as fontes das violações.

## Requisitos

- Python 3.x
- Módulos: `http.client`, `json`, `time`, `urllib.parse`

## Como Instalar

Apenas baixe e execute o **lucyinstaller.sh**
Todo o resto sera feito.

## Como usar

1. Substitua a variável `api_key` no script com a sua chave de API do RapidAPI.
2. Execute o script usando o comando: `python3 script.py`.
3. Insira o endereço de e-mail, username ou senha quando solicitado.
4. Visualize os resultados formatados e detalhes das violações de dados.
5. Use as flag -e, --email: Consultar um único endereço de e-mail, senha ou usuário.
6. Use a flag -l, --lista: Consultar uma lista de endereços de e-mail, senhas ou usuários a partir de um arquivo.
7. -h, --help: Exibir este menu de ajuda.

## Versão para Windows

- A versão para Windows é especialmente eficiente e não requer a instalação de nenhum pacote adicional.
- Para usuários do Windows, o script pode ser executado diretamente no executavel.

**[Download da Versão para Windows](https://github.com/CyberPiratHacks/LucyLeaks/blob/main/LucyLeaks.rar)**

[![Como usar](https://img.youtube.com/vi/Mr3MZcSQbNE/maxresdefault.jpg)](https://youtu.be/Mr3MZcSQbNE)

## Estrutura do Script

- O script utiliza a biblioteca `http.client` para realizar solicitações à API.
- Os resultados são exibidos de forma formatada, incluindo e-mails, senhas, hashes e fontes.
- O script trata redirecionamentos, limites de taxa e erros de solicitação.

## Personalização

- Modifique as cores no script usando códigos de escape ANSI para destacar resultados.
- Personalize a saída JSON para atender às suas necessidades.

## Notas

- Certifique-se de seguir as políticas de uso da API do BreachDirectory.
- Este script é um exemplo educacional e pode ser aprimorado para atender a requisitos específicos.
- Eu não me responsabilizo pelo mal uso desta ferramenta!

## Autor

- [David A. Mascaro](https://github.com/seuusuario)

# BreachDirectory API Python Script

This Python script utilizes the BreachDirectory API to perform data breach queries using email addresses. It displays detailed information about passwords and hashes associated with the provided email, as well as the sources of the breaches.

## Requirements

- Python 3.x
- Modules: `http.client`, `json`, `time`, `urllib.parse`

## How to Use

1. Replace the `api_key` variable in the script with your RapidAPI API key.
2. Run the script using the command: `python3 script.py`.
3. Choose an option:
    - Enter a single email address, password, or username.
    - Load a list of email addresses, passwords, or usernames from a file.
4. View the formatted results and details of the data breaches.
5. Use the flag `-e, --email`: Query a single email address, password, or username.
6. Use the flag `-l, --lista`: Query a list of email addresses, passwords, or usernames from a file.
7. Use the flag `-h, --help`: Display this help menu.

## Windows Version

- The Windows version is particularly efficient and does not require the installation of any additional packages.
- For Windows users, the script can be run directly from the executable.

**[Download Windows Version](https://github.com/CyberPiratHacks/LucyLeaks/blob/main/LucyLeaks.rar)**

[![How to Use](https://img.youtube.com/vi/Mr3MZcSQbNE/maxresdefault.jpg)](https://youtu.be/Mr3MZcSQbNE)

## Script Structure

- The script utilizes the `http.client` library to make requests to the API.
- Results are displayed in a formatted manner, including emails, passwords, hashes, and sources.
- The script handles redirections, rate limits, and request errors.

## Customization

- Modify colors in the script using ANSI escape codes to highlight results.
- Customize the JSON output to meet your specific needs.

## Notes

- Ensure compliance with BreachDirectory API usage policies.
- This script serves as an educational example and can be enhanced to meet specific requirements.
- I do not take responsibility for the misuse of this tool!

## Author

- [David A. Mascaro](https://github.com/seuusuario)
