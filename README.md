#### AVISO!

##### Infelizmente o PySimpleGUI (a biblioteca gráfica usada no projeto) não está mais disponivel gratuitamente.

### Sistema de Autenticação  em Python

O sistema é uma aplicação desktop simples com cadastro e recuperação  de contas de usuários. O software foi construido usando `MySql` como banco de dados e `PySimpleGUI` para interface gráfica. O programa tem como objetivo fins de estudos práticos, para compreenção e o funcionamento de um software de login completo.  

___
#### Configurações do projeto

Crie e ative um ambiente virtual 


`python3 -m venv C:\path\to\new\virtual\environment`


`PS C:\> <venv>\Scripts\Activate.ps1`

Instale as depêndencias do projeto

`python3 -m pip install -r requirements.txt`

Apos a instalar o `MySql`, faça a configuração das variáveis de ambiente para o servidor smtp:

Crie um arquivo `.env` nas pasta `\src\` em seguida insira as configurações. 

```
HOST=localhost
USER=root
PASSWORD="database-password"
DATABASE="database-name"
SMTPEMAIL="email-smtp-server"
SMTPPASS="password-smtp-server"
```
Configurações do servidor SMTP no arquivo `validation.py`. 

Exemplos de domínio do servidor: 

smtp.gmail.com

smtp-mail.outlook.com

As opções de configuração incluem:
Porta 25, 465 ou 587. Protocolos SSL e TLS.

configure a instância:
```
self.smtp = SmtpServer(host, port) # Use a porta 587
```










