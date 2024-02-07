
# Hospedagem de site estático

O projeto de hospedagem de site estático na AWS envolve a utilização dos serviços oferecidos pela Amazon Web Services (AWS) para hospedar um site estático de forma eficiente e escalável. Um site estático é composto por arquivos HTML, CSS, JavaScript, imagens e outros recursos que não requerem processamento do lado do servidor.

Para hospedar um site estático na AWS, geralmente utiliza-se o Amazon S3 (Simple Storage Service) para armazenar os arquivos do site. O Amazon S3 é um serviço de armazenamento em nuvem altamente escalável e confiável. Os arquivos do site são armazenados em um bucket do S3, que é configurado para servir conteúdo estático para os visitantes do site.


## Criar um bucket no Amazon S3 para Hospedagem de site estático:
       1° Faça login no Console de Gerenciamento da AWS em (https://https://aws.amazon.com/)
       2° Vá para o serviço Amazon S3.
       3° Clique em "Criar bucket".
       4° Escolha um nome único para o seu bucket (por exemplo, "meu-portfolio").
       5° Selecione a região AWS desejada.
       6° Clique em "Criar bucket".
       



![App Screenshot](/img/01.drawio.png)


#
        7° Selecionamos AWS region como us-east-1 N.Virginia.
        Quando as ACLs (Listas de Controle de Acesso) estão habilitadas, os objetos neste bucket podem ser de propriedade de outras contas da AWS. O acesso a este bucket e seus objetos pode ser especificado usando ACLs. No entanto, é recomendável desabilitar as ACLs, a menos que você precise controlar o acesso para cada objeto individualmente ou permitir que o escritor do objeto seja o proprietário dos dados que eles carregam. Utilizar uma política de bucket em vez de ACLs para compartilhar dados com usuários fora da sua conta simplifica a gestão de permissões e auditorias. 
        8° Selecionamos opção Object writer do objeto continua sendo o proprietário do objeto. É importante reconhecer que as configurações de Bloqueio de Acesso Público para este bucket podem resultar em tornar este bucket e os objetos dentro dele públicos.
       

![App Screenshot](/img/02.drawio.png)


#
        9° Desabilitamos as configurações de Bloqueio de Acesso Público para este bucket, reconhecemos que as configurações atuais podem resultar na possibilidade deste bucket e dos objetos dentro dele se tornarem públicos.

![App Screenshot](/img/03.drawio.png)

        10° Buccket criado

![App Screenshot](/img/04.drawio.png)

        11° Selecionamos properties 

![App Screenshot](/img/05.drawio.png)

        12° Clicamos em edit 

![App Screenshot](/img/06.drawio.png)
