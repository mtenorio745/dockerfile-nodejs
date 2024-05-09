CP1 - 2TCNR - CLOUD DEVELOPER

A atividade prática está na branch "code"

1 - Qual é a principal diferença entre Containers e Docker?
a) Containers são uma tecnologia de virtualização de sistema operacional, enquanto Docker é uma plataforma para criar, implantar e gerenciar contêineres.

2 - Como o Docker utiliza namespaces e cgroups para isolar processos e limitar o acesso a recursos do sistema operacional hospedeiro?

a) Namespaces são usados pelo Docker para fornecer um ambiente isolado para os processos em execução dentro de um contêiner, enquanto cgroups são usados para limitar o uso de recursos do sistema, como CPU, memória e rede.

3 - Neste exercício, será explorado uma aplicação prática de Dockerfile seguindo o dia a dia de Ana, uma desenvolvedora Python, em sua jornada para garantir consistência e replicabilidade em seu ambiente de desenvolvimento:

A - Por que Ana decidiu usar um Dockerfile em seu projeto?

Resposta: Ana optou por usar um Dockerfile porque percebeu que isso ajudaria a manter o ambiente de desenvolvimento igualzinho em todas as máquinas da equipe. Isso é super útil porque, usando o Dockerfile, ela consegue especificar qual versão do Python usar, quais bibliotecas instalar (como as de machine learning que ela precisa), e até mesmo copiar o código-fonte para dentro do contêiner. É como ter uma receita de bolo que garante que o bolo saia igual em qualquer cozinha que você usar. Isso evita aquele drama de algo funcionar no computador de um e no do outro não, além de facilitar bastante a vida quando alguém novo entra no time.

B - Quais são as etapas que Ana precisa seguir para testar o serviço em um ambiente de teste usando apenas o Dockerfile?

Resposta: Para testar seu serviço usando o Dockerfile, Ana segue alguns passos bem diretos, mas importantes. Primeiro, ela cria uma imagem usando o comando docker build. Isso é como pegar todos os ingredientes (código, bibliotecas, configurações) e preparar o prato. Depois, ela usa esse "prato" para rodar um contêiner, que é como testar a receita em um mini-ambiente seguro, usando o comando docker run. Enquanto o contêiner está rodando, ela pode espiar como as coisas estão indo, usando docker logs para ver os logs e docker stats para checar se o contêiner está usando muitos recursos, como memória ou CPU. Se alguma coisa precisar de ajuste, ela volta, mexe no código ou nas configurações do Dockerfile, e tenta de novo. Depois de testar, ela limpa a cozinha, digo, o ambiente de teste, parando e removendo o contêiner e as imagens que não precisa mais. É um ciclo de testar, ajustar e testar de novo, até ficar tudo certinho!

 ![image](https://github.com/mtenorio745/dockerfile-nodejs/assets/128000034/44daa20b-b2b8-4514-b37d-8a90637b7c9a)
![image](https://github.com/mtenorio745/dockerfile-nodejs/assets/128000034/cdbd30d7-4c3b-420c-abbb-527138971991)
