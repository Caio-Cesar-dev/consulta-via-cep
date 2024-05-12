![banner do desafio api viaCep](https://github.com/Caio-Cesar-dev/consulta-via-cep/assets/148168603/6a4dcfc9-fe75-4d11-a085-dd62944a90ba)
# Desafio


Vamos implementar uma aplicação para consultar um endereço a partir de um CEP e salvar as informações em um arquivo json.


## 🔨 Objetivos do projeto

- Criar uma classe que representa um endereço (cep, uf, cidade, bairro, logradouro e complemento);
- Criar uma classe que consulta a API *ViaCEP* para buscar um endereço a partir de um cep (exemplo: https://viacep.com.br/ws/04101300/json);
- Criar uma classe que cria um arquivo json contendo os dados de um objeto `Endereco`;
- Criar uma classe com método main que deve solicitar ao usuário que informe um CEP e na sequencia utilizar as classes para consultar a api ViaCEP e salvar os dados do endereço em um arquivo json.

## Observações:
- Utilize a biblioteca GSon para converter o JSON devolvido pela API ViaCEP em um objeto `Endereco`;
- Utilize a biblioteca GSon para salvar um objeto `Endereco` em um arquivo .json;
- O arquivo deve ter como nome o cep informado (exemplo: `04101300.json`);

Bom desafio!
