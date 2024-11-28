
# API Via Cep


A aplicação tem o objetivo de consultar um endereço a partir de um CEP e salvar as informações em um arquivo json.


1. **Classe de Representação de Endereço**  
   - Criação de uma classe para representar um endereço, contendo os seguintes atributos:
     - `cep` (Código de Endereçamento Postal)
     - `uf` (Unidade Federativa)
     - `cidade` (Cidade)
     - `bairro` (Bairro)
     - `logradouro` (Logradouro)
     - `complemento` (Complemento, opcional)

2. **Consulta à API ViaCEP**  
   - Implementação de uma classe para realizar consultas à API ViaCEP utilizando um CEP informado.  
   - Exemplo de consulta: `https://viacep.com.br/ws/{cep}/json`.

3. **Criação de Arquivo JSON**  
   - Implementação de uma classe para criar e salvar um arquivo no formato JSON contendo os dados de um objeto `Endereco`.

4. **Interface de Interação com o Usuário**  
   - Criação de uma classe com um método `main` que realiza as seguintes operações:
     - Solicita ao usuário que informe um CEP.
     - Utiliza a classe de consulta para buscar os dados do endereço na API ViaCEP.
     - Salva os dados do endereço retornado em um arquivo JSON.

## Tecnologias Utilizadas

- **Java**: Linguagem principal utilizada no projeto.
- **Gson**: Biblioteca para manipulação de JSON.
- **API ViaCEP**: Serviço externo para consulta de endereços.

## Como Executar

1. Compile o projeto utilizando um compilador Java ou sua IDE preferida.
2. Execute a classe com o método `main`.
3. Insira o CEP solicitado quando o programa for iniciado.
4. O programa buscará o endereço correspondente na API ViaCEP.
5. Os dados do endereço serão salvos em um arquivo JSON no diretório do projeto.




