<div class="header">
  <h1>Ignite Challenges ReactJS</h1>
  <p>Repository to store the Ignite Challenges Projects.</p>
</div>
<div>
    <div class="challenge">
        <h1>Challenge #01</h1>
        <h2>Descrição do Challenge:</h2>
        <p>
            Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS.<br>
            Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.<br>
            <b>1º</b> Adicionar uma nova tarefa<br>
            <b>2º</b> Remover uma tarefa<br>
            <b>3º</b> Marcar e desmarcar uma tarefa como concluída<br>
        </p>
        <hr>
        ![demo01](https://user-images.githubusercontent.com/73009630/168482832-ff1a883d-36e6-4bb5-ac30-66fb9e5937b4.gif)
    </div>
    <div class="challenge">
        <h1>Challenge #02</h1>
        <h2>Descrição do Challenge:</h2>
        <p>
        Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS.<br>
        Essa será uma aplicação onde o seu principal objetivo é refatorar uma página para listagem de filmes de acordo com gênero.<br>
        A aplicação já está totalmente funcional mas grande parte do seu código está diretamente no arquivo `App.tsx`. Para resolver isso da melhor forma, é necessário dividir a aplicação em <b>pelo menos</b> duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.<br>
        <b>1º</b> A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;<br>
        <b>2º</b> Na sidebar é possível selecionar qual categoria de filmes deve ser listada;<br>
        <b>3º</b> A primeira categoria da lista (que é "Ação") já deve começar como marcada;<br>
        <b>4º</b> O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.<br>
        </p>
        <hr>
        ![demo02](https://user-images.githubusercontent.com/73009630/168482866-3e561d7c-3bb8-46a0-8599-7dddfc3ad2bc.gif)

    </div>
</div>

<style>
    .header h1{
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .header p{
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 18px;
    }

    .challenge{
        padding: 10px;
        width: auto;
        height: auto;
        border: 2.6px solid;
        border-radius: 3px;
    }

    .challenge h1{
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .challenge p{
        text-align: justify;
        font-size: 16px;
    }
</style>
