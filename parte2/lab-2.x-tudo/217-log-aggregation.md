### Agregação de Logs

Devido a facilidade de criar e escalar aplicações, torna-se praticamente impossível rastrear algum erro de forma individual procurando em cada container. Para resolver este problema o Openshift possui uma solução de agregação de logs baseada no ElasticSearch, Fluentd e Kibana \(EFK\). O acesso aos logs é feito através da console gráfica do Kibana.

##### Na console do Openshift

* Navegue até a tab de logs de um dos pods.
* Selecione a opção `Archive`

![](https://storage.googleapis.com/workshop-openshift/log-aggregation.png)

É possível criar relatórios e consolidar em dashboards, com informações mostrando o crescimento de erros da aplicação `x` nos últimos meses ou semanas, etc...

##### 

##### Mais informações:

[https://docs.openshift.com/container-platform/3.6/install\_config/aggregate\_logging.html](https://docs.openshift.com/container-platform/3.6/install_config/aggregate_logging.html)

