**###CONCEITOS**

**S3**; Amazon Simple Storage Service é um serviço oferecido pela Amazon Web Services que fornece armazenamento de objetos por meio de uma interface de serviço da web.

**Baldes**; Container de objetos

**Objetos**; Qualquer tipo de arquivo ou metadados que descreva o arquivo

**Metadata**; Arquivo que descreve outros arquivos
Todo objeto capaz de ser armazenado e classificado pode ser identificado como metadados. Os metadados são um tipo de informação estruturada, ou seja, cujo significado é amplamente conhecido. Um bom exemplo disso é quando salvamos uma imagem em um computador ou celular.


Desta forma usamos um balde S3 para hospedar um website estático, este website pode sustentar qualquer nível concebível de tráfego por um custo baixo e sem precisar estabelecer, monitorar ou manusear qualquer servidor web.

Primeiro exercício: Criei um S3 bucket e configurei.

**ETAPAS E CONCEITOS (28)**

As primeiras etapas foram apenas explicativas, começou a prática a partir da sétima etapa.
Os conceitos aprendidos foram;

Etapa 7 (criação do nome):
O nome de um bucket S3 é único em todo o globo e compartilhado em todas as contas da AWS, depois que um bucket é criado seu nome não pode ser utilizado por mais nenhum bucket em qualquer conta da AWS até que o mesmo tenha sido excluído.

Etapa 9 (configurações):
Por padrão, novos depósitos, pontos de acesso e objetos não permitem acesso público. No entanto, os usuários podem modificar políticas de bucket, políticas de ponto de acesso ou permissões de objeto para permitir o acesso público. As configurações do Amazon 53 Block Public Access substituem essas políticas e permissões para que você possa limitar o acesso público a esses recursos.

Etapa 10 (configurações do default):Por padrão, os dados não são criptografados em seu bucket do Amazon S3. Uma prática recomendada comum é criptografar seus dados no lado do cliente ou por meio das opções de criptografia no lado do servidor do Amazon S3.

Etapa 11: Depois da criação, podemos acessar o bucket através do console, onde podemos fazer todas as outras operações sem nenhum código.

Etapa 12 (depois da criação do bucket): Seus dados armazenados no Amazon S3 são chamados de objetos. Um objeto é um arquivo e quaisquer metadados que descrevem esse arquivo. O Amazon S3 armazena arquivos de maneira que o conteúdo não seja lido pelo Amazon S3. Os metadados são um conjunto de pares chave-valor que descrevem o objeto.

Etapa 13: Uma chave é o identificador exclusivo de um objeto dentro de um bucket. Cada objeto em um balde tem exatamente uma chave. A combinação de um bucket, chave e ID de versão identifica exclusivamente cada objeto. O Amazon 53 é como um mapa de dados entre "bucket + key + version" e o próprio objeto. Cada objeto no Amazon $3 pode ser endereçado exclusivamente por meio da combinação do endpoint de serviço da web, nome do bucket, chave e (opcionalmente) uma versão.

Etapa 14: Os buckets suportam um número ilimitado de objetos de qualquer tamanho, podendo estes serem imagens, textos ou arquivos de áudio. 

Etapa 16 (propriedades): Você pode usar o Amazon S3 para hospedar um site estático configurando seu bucket para hospedagem de site estático, definindo permissões e adicionando um documento de índice. Opções como redirecionamentos, registro e documentos de erro também estão disponíveis.

Etapa 17 (hospedando o website): 

Amazon S3 apoia dois tipos de urls:

**virtual-hosted-style:**
https://bucket-name.s3.Region.amazonaws.com/key

**path-style:**
https://s3.Region.amazonaws.com/bucket-name/keyname

Etapa 20 (permissões):
Por padrão, todos os recursos do Amazon S3 (buckets, objetos e sub-recursos relacionados) são privados. Somente o proprietário do recurso pode acessá-los. O proprietário do recurso pode opcionalmente conceder permissões de acesso a outros escrevendo uma política de acesso.

Etapa 21 (políticas): A política de bucket e a política de usuário são duas das opções de política de acesso que você pode usar para conceder permissões aos recursos do Amazon S3. Ambas as opções usam linguagem de política de acesso baseada em JSON. Um nome de recurso da Amazon (ARN) identifica exclusivamente os recursos da AWS.

Etapa 25 (propriedades): Com o Amazon S3, você pode fazer upload de objetos de até 5 GB com uma única operação de colocação. Para objetos maiores, com tamanho de até 5 TB, use a API de multipart upload.

Depois de terminar, modifiquei o nome do "index.html" pra "waves.html"by
