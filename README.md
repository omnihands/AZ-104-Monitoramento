# AZ-104-Monitoramento
 Implementando Monitoramento no Azure

Etapa 1) Monitoramento
 1.1 Criando Alerta. 
  1.1.1 Acessar o Azure monitor> VM insights e configurar o Insight
  1.2.1 Caso não haja nenhum host em monitoramento, seguir para a aba não monitorado e habilitar o monitoramento.
   1.2.1.1 Nesse momento é criado um agente dentro VM para poder enviar as informações para o Azure Monitor.
  Após o processo de conclusão a maquina deve apresentar na aba monitorado
  1.3.1 Monitorar > Alerta
   1.3.1.1 Criar > Regra de alerta, após essa etapa escolher o recurso.
   1.3.1.2 Após escolher o recurso precisamos escolher a condição. Importante selecionar o event Level. no caso do exemplo seria severo devido ser a exclusão de maquina.
   1.3.1.3 Ações. Qual ção sera tomada como enviar e-mail, sms entre outros.
  1.4 Após a criação
  1.4.1 sempre que a ação for feita vira de acordo com os paramentros feitos nas opções anteriores.
  Lembrando que rever os alertas monitor >alerta
  
