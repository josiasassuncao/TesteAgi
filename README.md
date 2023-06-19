# TesteAgi
Teste Agibank
Orientações
- Após instalar o JMeter, carregue o arquivo "Blaze Demo.jmx"
- Os arquivos user.csv e cities.csv, para facilitar a execução, devem estar no mesmo diretório do arquivo do teste.
- O passo "Comprar passagem" possui asserções que validam a compra da passagem.

Tempo médio (90%): 2,4 segundos
Conclusão: 
- Como o critério de aceite é de um tempo inferior a 2 segundos, o teste falhou. Já que os testes indicaram que para o cenário proposto, o tempo foi superior a 2 segundos. 
- Apesar disso, a compra não falhou. Em todos os testes realizados, a compra da passagem foi realizada com sucesso. É importante salientar que como o teste foi realizado localmente, talvez o resultado tenha sido prejudicado. Para uma melhor confiabilidade, o ideal é executar o script em um servidor, já que a latência pode sofrer grandes alterações de uma execução para outra (em máquinas diferentes).
- Outro ponto importante notado nos testes foi que o acesso a home é o teste mais demorado, em algumas execuções foi esse passo que jogou a média da execução para cima. Ficando os demais passos dentro do critério de aceite.
