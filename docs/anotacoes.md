
Explicação sobre os cod usados na logo:

.brand {
    display: inline-flex;
    flex-shrink: 0;
}

display: inline-flex: transforma o elemento em um contêiner flexível, mas mantém seu comportamento semelhante a um elemento inline. Isso permite que a logo fique alinhada corretamente dentro do .header-container.

flex-shrink: 0: impede que a marca seja diminuída automaticamente quando faltar espaço no cabeçalho. Assim, a logo mantém seu tamanho enquanto o menu ocupa o espaço restante.

A regra relacionada à imagem é:
.brand img {
    display: block;
    height: auto;
    max-width: 190px;
    width: 100%;
}
Ela faz a imagem ocupar até 190px de largura, preservando sua proporção com height: auto. O display: block remove espaços extras que imagens podem apresentar quando usadas como elementos inline.


Detalhamento do código html abaixo:

<button class="menu-toggle" type="button" aria-controls="site-navigation" aria-expanded="false">
    <img src="./assets/img/menu.svg" alt="">
    <span class="sr-only">Abrir menu</span>
</button>

efine um botão de menu e utiliza atributos de acessibilidade (ARIA) para melhorar a experiência de usuários que usam leitores de tela.

aria-controls="site-navigation" - Indica qual elemento da página é controlado por esse botão.
Nesse caso, o botão abre ou fecha o menu identificado por site-navigation.

Isso ajuda tecnologias assistivas a entenderem a relação entre os elementos.

aria-expanded="false" - Informa se o conteúdo controlado está aberto ou fechado.
Quando o usuário clica para abrir o menu, normalmente o JavaScript altera:

<span class="sr-only">Abrir menu</span> - <span class="sr-only">Abrir menu</span>
Diferença

Com aria-label:

O texto fica apenas para tecnologias assistivas.
Não existe no HTML visível.

Com span.sr-only:

O texto existe no DOM.
Pode ser encontrado por ferramentas de busca, tradução e inspeção.
Muitos desenvolvedores preferem essa abordagem por ser mais semântica.