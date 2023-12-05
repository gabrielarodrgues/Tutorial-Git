# Tutorial-Git 
O comando git remote permite criar, ver e excluir conexões com outros repositórios. As conexões remotas são mais parecidas com marcadores em vez de links diretos para outros repositórios. Em vez de dar acesso em tempo real a outro repositório, eles funcionam como nomes convenientes que podem ser usados para fazer referência a uma URL não tão conveniente.
O comando git remote é, em essência, uma interface para gerenciar uma lista de entradas remotas que são armazenadas no arquivo ./.git/config do repositório. Os comandos a seguir são usados para ver o estado atual da lista remota.
O comando git remote é também uma conveniência ou método "auxiliar" para modificar o arquivo ./.git/config de um repositório. Os comandos apresentados abaixo permitem gerenciar conexões com outros repositórios. Os comandos a seguir vão modificar o arquivo /.git/config do repositório. O resultado dos comandos a seguir também pode ser alcançado editando direto o arquivo ./.git/config com um editor de texto.
Quando você clona um repositório com git clone, ocorre a criação automática de uma conexão remota chamada origem, que aponta de volta para o repositório clonado. É um recurso útil para os desenvolvedores criarem uma cópia local de um repositório central, pois oferece uma maneira fácil de enviar pull de alterações de upstream ou publicar commits locais. Esse comportamento é também o motivo pelo qual a maioria dos projetos baseados em Git chama de origem o seu repositório central.