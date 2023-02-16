**#CONCEITOS**

**EC2**; Amazon Elastic Compute Cloud é um serviço web que fornece capacidade de computação confiável e escalável na nuvem para que você possa iniciar servidores  virtuais em minutos.

**Instância**; Servidor virtual na nuvem aws. Com o EC2 é possível definir e configurar o sistema operacional e as aplicações que são executadas em sua instância.

**Island stabilization system**; A ilha melhora a confiabilidade e a disponibilidade de seu sistema de estabilização ao mover seu módulo computacional para a infraestrutura global da AWS.

**Computional module**; O módulo computacional pode se mover para a nuvem usando a capacidade de computação das instâncias do Amazon Elastic Compute Cloud (Amazon EC2).
Para melhorar a disponibilidade, o módulo computacional é executado em instâncias do Amazon EC2 implantadas em zonas de disponibilidade (AZs) separadas. Cada região da AWS consiste em dois ou mais AZS com um compromisso de contrato de nível de serviço (SLA) de 99,99%.

Amazon Elastic Block Store (Amazon EBS; O Amazon Elastic Block Store (Amazon EBS) é um serviço de armazenamento em bloco eficiente e de alto desempenho projetado para uso com o Amazon EC2.

Exercício: 
Iniciar uma instância do Amazon EC2
Configurar um script de dados do usuário para exibir os detalhes da instância em um navegador
Lançar uma segunda instância do Amazon EC2 em uma zona de disponibilidade diferente da mesma região aws

**ETAPAS E CONCEITOS (17)**

Os conceitos aprendidos foram;

Etapa 4 (lançamento da instância):
Uma instância EC2 é um servidor virtual na nuvem.

Etapa 5/6 (ami):
Uma Amazon Machine Image (AMI) fornece as informações necessárias para iniciar uma instância. Você deve especificar uma AMI ao executar uma instância. Você pode iniciar várias instâncias de uma única AMI quando precisar de várias instâncias com a mesma configuração. Você pode usar AMI's diferentes para iniciar instâncias quando precisar de configurações diferentes.
Quando você inicia uma instância, o tipo de instância que você especifica determina o hardware do computador host usado para sua instância. Cada tipo de instância oferece diferentes recursos de computação, memória e armazenamento e são agrupados em famílias de instâncias com base nesses recursos.

Etapa 7 (Key): O Amazon EC2 usa criptografia de chave pública para criptografar e descriptografar informações de login. A criptografia de chave pública usa uma chave pública para criptografar um dado e, em seguida, o destinatário usa sua chave privada para descriptografar os dados. As chaves pública e privada são conhecidas como um par de chaves.

Etapa 8 (vpc e subnet): O Amazon EC2 está hospedado em vários locais em todo o mundo. Esses locais são compostos por regiões, zonas de disponibilidade e zonas locais. Cada região é uma área geográfica separada com vários locais isolados, conhecidos como zonas de disponibilidade.
Uma nuvem privada virtual (VPC) é uma rede virtual dedicada à sua conta da AWS. Enquanto uma VPC reside em uma região da AWS, uma sub-rede deve residir em uma única zona de disponibilidade.

Etapa 9 (grupo de segurança): Um grupo de segurança atua como um virtual firewall que controla o tráfego para uma ou mais instâncias. Ao ativar uma instância, você pode especificar um ou mais security groups; caso contrário, o security group padrão será usado. Você pode adicionar regras a cada grupo de segurança que permite o tráfego de ou para suas instâncias

Etapa 10 (default): Quando você inicia uma instância, o volume do dispositivo raiz contém a imagem usada para inicializar a instância.

Etapa 11 (script): Este script de dados do usuário inicia um servidor web, usando a porta 80, para exibir informações internas sobre a instância. Ao iniciar uma instância no Amazon EC2, você tem a opção de passar dados do usuário para a instância que podem ser usados ​​para executar tarefas comuns de configuração automatizada e até mesmo executar scripts após o início da instância.

Etapa 15 (depois de criar instância): Uma instância entra no estado pendente quando é iniciada pela primeira vez. Ele muda para um estado de execução quando está pronto para uso.

Etapa 16 (rodando a instância): 



Depois de terminar, tive que criar uma nova instância que estivesse em uma zona diferente do primeiro, essas modificações foram feitas de acordo com etapa 8.




