# #AzureSolutionlet - Analisando imagens

>Este Hands-On Labs faz parte da série #AzureSolutionlets, onde resolveremos problemas específicos através de rápidos deploys utilizando o [Microsoft Azure](https://azure.microsoft.com/pt-br/). O vídeo relacionado a esta solução pode ser encontrado [aqui](#).

Através deste Hands-On Labs você aprenderá a utilizar as [APIs de Visão Computacional](https://www.microsoft.com/cognitive-services/en-us/computer-vision-api) para extrair informações de imagens. Essas APIs fazem parte do pacote de [Serviços Cognitivos da Microsoft](https://www.microsoft.com/cognitive-services) que permite que os desenvolvedores adicionem facilmente recursos poderosos e inteligentes em suas aplicações.

Para demonstrar esses conceitos, utilizaremos uma aplicação Web, hospedada no Microsoft Azure, que pode se conectar ao serviço de imagens Flickr para poder categorizar fotos, facilitando assim sua busca.

Para poder reproduzir os passos que descreveremos aqui, você precisará de uma conta trial no Azure. Ao criar sua conta trial, você receberá R$ 750,00 para gastar em todos serviços do Azure, como máquinas virtuais, bancos de dados SQL, sites e muitos outros. Caso você já possua uma subscrição ativa do Azure, por favor pule o Passo 0.

### Passo 0: Criar conta trial do Microsoft Azure
Acesse [https://azure.microsoft.com/pt-br/pricing/free-trial](https://azure.microsoft.com/pt-br/pricing/free-trial) e clique no botão **Teste agora**:

![](/images/azure-solutionlets-image-tagging-01.png)

Logue-se com uma conta Microsoft (hotmail, live, etc). Em seguida, preencha seus dados. É necessário um telefone celular para verificar sua identidade, bem como um cartão de crédito válido. Após ler os termos e, caso concorde com eles, cheque *Eu concordo..."* seguido do clique em **Inscrever-se**:

![](/images/azure-solutionlets-image-tagging-02.png)

Você será uma levado a uma página onde deve aguardar alguns instantes até que sua subscrição esteja pronto para uso. Uma vez pronta, clique no botão verde para continuar e ser levado à tela inicial do Microsoft Azure:

![](/images/azure-solutionlets-image-tagging-03.png)

