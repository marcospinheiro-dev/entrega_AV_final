# O que é uma Activity?
## É uma atividade, uma tela no android visível ao usuário.
##
# Como funciona o ciclo de vida de uma Activity?
## O ciclo de vida de uma Activity, que mostra a interação visível da interface ao usuário do aplicativo android, tem uma sequência de métodos que são ativado durante o ciclo que são:
- Do clic inicial até o momento em que é visível na tela do dispositivo são executados 3 métodos: onCreate(), onStar() e onResume.
- Ao acionar outra activity ou minimizar a aplicação, entra o método onPause.
- Caso o sistema esteja pausado por um certo tempo, entra no método onStop()
- Por fim, caso não seja reativado a atividade (onRestart()), então o sistema executa onDestroy().
##
# O que é e qual a função do Adapter e do Viewholder?
## O Adapter é responsável por fazer uma exibição para cada ítem em um conjunto de dados. É a ponte entre a view e alguma fonte de dados.
## O Adapter cria o objeto viewholder que será um ítem da RecyclerView.
##
# O que é o Retrofit e por que utilizar ao invés de criar as chamadas manualmente?
## é uma biblioteca utilizada como um REST client(Android/Java) para fazer os Http Requests, usando retrofit é mais fácil implementar, menos linha de código usando uma BASE_URL em uma interface.


