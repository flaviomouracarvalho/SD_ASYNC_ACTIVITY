# Atividade de Sistemas Distribuidos - 'Chamadas Assíncronas'
<h3>1. qual problema percebeu ao realizar tais alterações?</h3>
<p>A vinda da mensagem de Mensagem 'dados obtidos do Servidor!' está vindo primeiro e depois com um certo delay está mostrando as url referente a resposta do servidor, então sobrescrevendo os dados.</p>
<h3>2 - explique porque o problema ocorreu e o qual a relação com chamadas assíncronas?</h3>
<p>Como o JavaScript executa as chamadas assincronas em segundo plano, a proxima instrução e executada e com isso a mensagem e mostrada antes dos dados serem obtidos</p>
<h3>3 - altere o código para resolver o problema.</h3>
<p>Criei uma nova função mensage, inserindo em uma nova div, e tambem uma função principal que executa as duas funções acima, com o proposito dos dados do servidor e a mensagem serem mostrados juntos, a função request recebeu a chamada await, para que a proxima função possa ser executado depois que a primeira função for concluida. </p>
