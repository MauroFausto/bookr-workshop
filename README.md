# bookr-workshop
Projeto de estudo do framework Django com Angular

## Como rodar o projeto?

1. Rode o seguinte comando no terminal do Powershell: <code>python -m venv bookr-env</code>. Deverá ser criado uma pasta 'bookr-env' contendo as libs e os scripts para a gestão do ambiente de desenvolvimento Python;
2. No diretório onde se encontram agora a pasta dos arquivos fonte e os arquivos do ambiente virtual, invoque o script de ativação do ambiente: <code>.\bookr-env\Scripts\activate</code>;
3. Uma vez ativado o ambiente virtual, instale as dependências do projeto através do comando: <code>python -m pip install -r requirements.txt</code>;
4. Após a instalação das dependências, navegue até o diretório com o nome do projeto, onde se encontra o arquivo 'manage.py';
5. Dentro desse diretório, execute o comando: <code>python manage.py runserver [Nº da Porta]</code> para executar o servidor de desenvolvimento Django;
6. Feito isso, ao acessar o endereço <code>localhost:[Nº da Porta]</code> ou <code>127.0.0.1:[Nº da Porta]</code>, você deverá ver essa página de testes:
   
   ![image](https://github.com/MauroFausto/bookr-workshop/assets/89610280/e679863e-f6c9-4638-9838-343085a7ec54)
