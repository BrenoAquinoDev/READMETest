# Introdução
Esse aplicativo permite o usuario a procurar por filmes em uma larga base de dados. É possivel que filmes sejam favoritados, ver os vídeos dos filmes (como os trailers), ver a sinopse, ver o titulo e ver a data de lançamento de cada filme.

# Vídeo de Demonstração
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/lQKpaUJWfnY/0.jpg)](https://www.youtube.com/watch?v=lQKpaUJWfnY)

# Arquitetura e Organização do Projeto
Foi escolhida a arquitetura MVVM, pois com ela é permitido que as ViewController possam ficar encarregadas somente de exibir os dados pertinentes já tratados. Os tratamentos de dados são feitos nas classes ViewModel. Elas se responsabilizam de pegar os dados do banco (Realm) e trazer pra ViewController já em forma para ser exibido.

O projeto também utiliza classes gerenciais para definir fluxos e tratamento de erros de maneira geral para o aplicativo todo,  evitando a repetiço de codigo em diversos locais do projeto.

# Biliotecas de Terceiros
- Alamofire
- ObjectMapper
- AlamofireObjectMapper
- Realm
- Kingfish
- SwiftGen
- Reusable
- SwiftMessages
- StatefulViewController (essa biblioteca foi integrada ao projeto em Application -> Extension -> StatefulViewController, pois era necessario fazer pequenos ajustes para tornar a funcionalidade dela mais geral para o projeto)

# Possíveis Melhorias
Melhoraria nas animações de transições, incluiria mais informações do filme na tela de detalhes, implementaria mais recursos que o iOS proporciona (widget etc), melhoraria o design do aplicativo.

# Requisitos Obrigatórios
Todos os requisitos obrigatórios foram implementados
