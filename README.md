# Titulo: Desaﬁo#3 - VTEX IO + AWS

## Descrição : Você foi contratado para desenvolver o ecommerce.

### Funcionalidades

- [x] Template de criação
        [x] ● Criar a solução a partir de um boiler template padrão da Vtex IO

        RESPOSTA: foi usado o : git clone https://github.com/vtex-apps/minimum-boilerplate-theme.git
        <h1 align="center">
            <img alt="Next" title="#Next" src="./assets/screenshots/preview-site.PNG" />
        </h1>

        ![osbornelive](https://github.com/osbornelive/vtexa320/blob/main/store/assets/screenshots/preview-site.PNG)


- [x] Layout
        ● Observação - A réplica não precisa ser uma cópia ﬁel deste layout mas tentar se aproximar o máximo que conseguir
        
        ● Utilizar o Markdown + o css para formatação -
            https://pt.wikipedia.org/wiki/Markdown
        
        ● Flex Layout para criar as cores em css -
            https://vtex.io/docs/components/all/vtex.ﬂex-layout@0.17.0/
        
        ● Dar prioridade as páginas criada nos arquivos.jsonc colocando comentários dos blocos criados
        
        ● Utilizar o Slider layout para mostrar os produtos em destaque -
            https://vtex.io/docs/app/vtex.slider-layout

        ● Criar um componente Tab Layout para separar os produtos por categoria
            https://vtex.io/docs/components/all/vtex.tab-layout@0.4.3/

        ● Criar um bloco de lista de produtos -
            https://vtex.io/docs/app/vtex.product-list@0.31.0/
            Sugestão paginado por 8 itens da categoria

        ● Criar Minicard para lista dos produtos no carrinho
            https://vtex.io/docs/components/content-blocks/vtex.minicart@2.60.0/

        ● Ao clicar no produto ir para tela com Product Summary
            https://vtex.io/docs/components/all/vtex.product-summary@2.53.0/


- [ ] Layout Mobile
        https://vtex.io/docs/components/all/vtex.ﬂex-layout@0.17.0/
        Dar prioridade as páginas criada nos arquivos.jsonc colocando comentários dos blocos criados

        ● Criar um componente customizado para falar com suporte no whatsapp, no rodapé
            ● ● Utilizar o Vtex Componentes com React para criar o componente
                https://vtex.io/docs/components/all/vtex.store-components@3.150.0/
            ○
            ○ API whatsapp - https://www.convertte.com.br/gerador-link-whatsapp/

- [ ] Layout Mobile
    Criar um componente customizado para cadastrar leads (possíveis clientes prospectos)
        ○ Nome
        ○ Email
        ○ Telefone

        ○ Este componente pode servir de isca digital, fazendo dando umaboniﬁcação para o prospecto que preencher as informações da lead.Utilizar o Vtex Componentes com React para criar o componente https://vtex.io/docs/components/all/vtex.store-components@3.150.0/


- [ ] AWS API Gateway
        ● Com o objetivo de armazenar as leads que o Vtex componente irá utilizar no
    React, criar uma API Gateway na AWS para colocar as informações -
    https://aws.amazon.com/pt/api-gateway/
        ● Um exemplo de arquivo API Gateway para estudo:
        ● https://github.com/awslabs/aws-api-gateway-developer-portal/blob/master/cloudformation/template.yaml
        ● https://github.com/mattpodolak/email-api-lambda
        ● https://github.com/amazon-archives/realworld-serverless-application/blob/master/backend/sam/app/api.template.yaml   


- [ ] Opcional
        ● Criar um item no adm do vtex para trazer o conteúdo das leads cadastradas na API Gateway AWS - Conteúdo vídeo 9 do curso

- [x] Template de criação
 
