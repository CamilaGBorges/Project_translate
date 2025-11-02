*##Solução Completa de Tradução de Texto em Python com Azure Translator

Tradutor de textos entre diferentes idiomas, aproveitando a Inteligência artificial do serviço Azure Translator.
1. Criar e Configurar o Recurso Azure Translator

O primeiro passo é configurar o serviço de tradução no portal do Azure para obter as credenciais necessárias.

    Acessar o Portal do Azure: Faça login no
    Ícone do siteportal.azure.com
    com sua conta.
    Criar um Novo Recurso: No menu lateral, clique em "Criar um recurso" (ou use a barra de pesquisa) e procure por "Translator".
    Selecionar e Criar: Selecione "Translator" nos resultados da pesquisa e clique em "Criar".
    Preencher Detalhes:
        Assinatura: Escolha sua assinatura do Azure.
        Grupo de Recursos: Crie um novo grupo de recursos ou selecione um existente. Recomenda-se um novo para organizar melhor seus recursos.
        Região: Escolha uma região geográfica próxima a você ou aos seus usuários para menor latência.
        Nome: Dê um nome exclusivo ao seu recurso de Translator.
        Tipo de preço: Selecione o plano de preços que melhor se adapta às suas necessidades e orçamento (por exemplo, "Gratuito" para testes iniciais).
    Revisar e Criar: Revise os detalhes e clique em "Revisar + criar", e depois em "Criar".
    Obter Chave e Endpoint: Após a implantação do recurso, acesse-o. Na seção "Chaves e Ponto de Extremidade" (ou "Keys and Endpoint"), você encontrará a Chave (Subscription Key) e o Ponto de Extremidade (Endpoint). Copie esses valores, pois eles serão usados no seu código Python.

2. Configurar o Ambiente Python

Certifique-se de que seu ambiente Python está pronto para interagir com o Azure Translator.

    Instalar Python: Verifique se você tem o Python 3.x instalado em seu sistema. Se não tiver, baixe e instale-o do site oficial do Python.
    Instalar a Biblioteca requests: Esta biblioteca facilita a realização de requisições HTTP para a API do Azure. Abra seu terminal ou prompt de comando e execute:*##

