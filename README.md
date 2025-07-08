# Bootcamp Dio - Microsoft Azure Administrator Certification AZ-104 -Monitoramento.

O monitoramento no Azure é fundamental para garantir a observabilidade, desempenho, segurança e a disponibilidade dos recursos e aplicações. O serviço central que oferece essas funcionalidades é o Azure Monitor.

🧩 Um pouco do que podemos fazer com seu uso:

  * Monitorar uso de CPU em VMs	
  * Usar Metricas + Alertas.
  * Rastrear falhas de APIs
  * Uso do Application Insights.
  * Verificação de tentativas de login mal-sucedidas em VMs	
  * Logs no Diagnostic Settings e consultar via Log Analytics.
  * Criar dashboard com dados de múltiplas VMs	Usar Workbooks.

🛠️ Podemos ainda:
 
  * Integrar com o Azure Sentinel para SIEM/SOAR.
  * Fazer uso do Grafana com Azure Monitor como fonte de dados.
  * Automatize alertas com Logic Apps ou Azure Automation.


 ### Criação de Recursos no Azure com Monitoramento e Alertas.


 * Criar um Resource Group
    📌 Para organizar os recursos de forma lógica, iniciamos criando um Resource Group.

![alt text](<imagens/1 criar um resource group.png>)

* Criar Tags para os Recursos
    📌 As tags permitem classificar e organizar recursos, o que facilita a gestão e o controle de custos.

![alt text](<imagens/ 2 criar tags para os recursos.png>)

* Criar a Máquina Virtual (VM)
    📌 Criamos uma VM dentro do Resource Group configurado, especificando SO, tamanho, disco, rede e outras opções.

![alt text](<imagens/ 3 criar vm.png>)

* Ativar o Monitoramento Durante a Criação
    📌 Depois de criada(poderia ser junto no processo de criação) a VM, habilitamos o monitoramento com o Azure Monitor, o que permite acompanhar o desempenho e integridade da VM.

![alt text](<imagens/4 apos criada ativar o monitoramento.png>)

* Finalizando a Habilitação do Monitoramento
    📌 Confirme e salve as configurações de monitoramento para que a VM comece a ser monitorada.

![alt text](<imagens/5 ativando monitoramento.png>)

![alt text](<imagens/6 habilitar por fim.png>)

* Criar um Alerta
   📌 Com o monitoramento ativo, criamos uma regra de alerta para ser notificado ao atingir determinados critérios.

![alt text](<imagens/7 Criar o alerta.png>)

* Seleção do Escopo
    📌 Selecionamos o escopo do alerta, que neste caso é a própria VM criada.

![alt text](<imagens/8 Seleção do escopo neste caso a vm.png>)

* Seleção da Condição
    📌 Definimos a condição da métrica que vai disparar o alerta. Por exemplo, alto uso de CPU, falhas de disco etc.

![alt text](<imagens/9 seleção da condição para a regra.png>)

* Criar Grupo de Ação
    📌 Criamos um Grupo de Ação, que define quem será notificado e qual ação será tomada em caso de alerta (ex: e-mail, webhook).

![alt text](<imagens/ 10 criando o grupo de ação.png>)


![alt text](<imagens/11 selecionando como enviar o alerta.png>)

![alt text](<imagens/12 alerta criado.png>)

![alt text](<imagens/13 ativando o alerta com a exclusão.png>)

![alt text](<imagens/14 Recebimento do email de adição ao grupo.png>)

![alt text](<imagens/15 Alerta concluido.png>)






  
