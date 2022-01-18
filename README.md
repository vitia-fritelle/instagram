# Projeto Instagram

Este projeto foi desenvolvido para a entrega de uma página inspirada no [Instagram](https://www.instagram.com/) de acordo com um layout [Figma](https://www.figma.com/) no curso de programação da [Driven](https://www.driven.com.br/).

## Descrição

Projeto para aplicar um layout responsivo da versão web do Instagram, utilizando HTML e CSS. Tentativa de deixar a página parecida ao máximo com o layout fornecido!

## Requisitos

Sinta-se à vontade para colocar as fotos de exemplo que quiser no seu Instagram! :)

- Layout
    - [ ]  Aplicar layout para desktop, seguindo layout fornecido no [Figma](https://www.figma.com/)
    - [ ]  Aplicar layout para mobile, seguindo layout fornecido no [Figma](https://www.figma.com/)
    - [ ]  O layout sem sidebar deve ser ativado quando a largura da tela for menor que 935px
    - [ ]  O layout para mobile deve ser ativado quando a largura da tela for inferior a 614px
    - [ ]  Não é obrigatório que a sidebar fique fixa conforme o usuário desce na página como ocorre no [Instagram](https://www.instagram.com/) (mas é um bônus)

- Ícones
    - [ ]  Utilize os ícones da biblioteca [Ionicons](https://ionicons.com/).
    
- Stories
    - [ ]  Na caixa dos stories, deve haver itens o suficiente para ultrapassar a largura, mas os itens a mais não devem ser exibidos, conforme layout
    - [ ]  Deve haver, no modo desktop, uma setinha no canto direito dos stories (conforme mostrado no layout do [Figma](https://www.figma.com/))
    - [ ]  A setinha não precisa funcionar ao clicar 
    - [ ]  Não pode haver um scroll horizontal visível

# Bônus

Bônus não são obrigatórios, são sugestões. Fazer as seguintes funcionalidades:

- Vídeo
    - [ ]  Pelo menos um dos posts deve ser um vídeo
    - [ ]  Não é necessário ter o botão de play
    - [ ]  O vídeo deve ser inserido tanto no formato .mp4 e .ogg, para que funcione em qualquer navegador
    - [ ]  O vídeo deve ser iniciado automaticamente
        
    (Para não incomodar o usuário, os navegadores não permitem que um vídeo toque automaticamente a não ser que o som esteja desativado. Então, se colocou o atributo para iniciar o vídeo automaticamente e não funcionou, desative o som dele.)
    
- Sidebar fixa
    
    Se você acessar a página do [Instagram](https://www.instagram.com/) do seu computador e descer na página, perceberá que a barra lateral continua visível, fixa na página.
    
    A ideia deste bônus é implementar este comportamento, isto é, ao descer na página, a coluna permanece no mesmo lugar sempre.
    
- Comentários
    
    Pelos propósitos do projeto, não há comentários dos posts no layout do [Figma](https://www.figma.com/). Estes são os requisitos deste bônus:
    
    - [ ]  Ter comentários nos posts, com botão de like no canto direito em cada comentário
    - [ ]  Uma caixa para digitar o comentário, utilizando a tag `input`
    - [ ]  Um botão ao lado desta caixa para **Publicar**, com cor `#B2DFFC` inicialmente e, ao passar o mouse, fique com a cor `#0095F6` com uma transição que dura `300ms`. Procure pela propriedade *transition* para fazer isso.