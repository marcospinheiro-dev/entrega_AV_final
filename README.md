# O que é uma Activity?
## É uma atividade, uma tela no android visível ao usuário.
##
# Como funciona o ciclo de vida de uma Activity?
## O ciclo de vida de uma Activity, que mostra a interação visível da interface ao usuário do aplicativo android, tem uma sequência de métodos que são ativado durante o ciclo que são:
- Do clic inicial até o momento em que é visível na tela do dispositivo são executados 3 métodos: onCreate(), onStar() e onResume.
- ao acionar outra activity ou minimizar a aplicação, entra o método onPause.
- Caso o sistema esteja pausado por um certo tempo, entra no método onStop()
- Por fim, caso não seja reativado a atividade (onRestart()), então o sistema executa onDestroy().
##

