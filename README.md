# React-background
:books: como o React funciona no seu background ? você sabe?
<br>
Ele utiliza de tres plugins, webpack, babel e o próprio react
<br>
webpack -> ele é responsável por comprimir o código, e no caso fazer tbm fazer o live server.<br>
babel -> sua principal finalidade é um transforma código novo em antigo para que todos os browser entendam. mas, no react ele é responsavel por transforma React.createElement em jsx <br>
react & reactDom -> esse é o principal, react que faz o babel funcionar, porque é nele que temos o método "react.createElemet()" que o babel converte para jsx, e reactDom coloca no html.
