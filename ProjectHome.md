# DA - Windows Vault/Network Password Recovery #


É uma pequena ferramenta de recuperação de senha que permite visualizar os nomes de usuário e senhas armazenadas pelo navegador Internet Explorer, recuperando os endereços e senhas armazenados pelo Windows Credential Store e pelo Windows Vault. Para cada entrada de senha, a seguinte informação é exibida: URL, Nome de Usuário, Campo de senha.

Você pode selecionar um ou mais itens e, em seguida, salvá-los em arquivo de texto/html/xml ou copiá-los para a área de transferência.

![http://desenvolvimentoabertotools.files.wordpress.com/2014/08/da-internet-network.gif](http://desenvolvimentoabertotools.files.wordpress.com/2014/08/da-internet-network.gif)

## Internet Explorer 7 ##

O Windows fornece o Credencial Store que é uma estrutura para armazenar senhas de rede em um formato seguro e criptografado. Isso proporciona mecanismo conveniente e confiável de armazenar as senhas para logins de rede para que o usuário não tem que digitar a senha toda vez que ao acessar os recursos da rede.

Não só o Windows usa para armazenar senhas de autenticação de rede, mas também outras aplicações como o Outlook, Windows Live Messenger, Remote Destktop, GMail Notifier e etc.

O Windows também permite que os aplicativos gerenciem perfeitamente o Credencial Store usando funções da API de gerenciamento de credenciais, as credenciais são armazenadas localmente no contexto do usuário.

## Internet Explorer 10 ##

O IE10 mudou a maneira como ele armazena senhas. Agora, todas as senhas de preenchimento automático são armazenados no Gerenciador de Credenciais em um local chamado de "Credenciais da Web".

### Windows Vault ###

Por incrível que pareça, o Windows Vault foi introduzido pela primeira vez ao público com o lançamento do Windows 7, mas ainda não há informações devido  sua descrição na rede. A documentação sobre este assunto,  interessantemente é completamente ausente, ou, para dizer o mínimo, é superficial. Então, o que é Vault?

Assim, o Windows Vault é um estrutura de armazenamento de dados privados que veio para substituir o Gerenciador de Credenciais. A Microsoft em mais uma tentativa de criar um armazenamento universal de segredos que o Windows parece ter tanta falta.


---


### Junte-se a nós (Join Us) ###

Para participar envie um e-mail ou apenas nos ajude reportando um erro.

To Join us send an email or just help us reporting na issue.

desenvolvimento.aberto@live.com