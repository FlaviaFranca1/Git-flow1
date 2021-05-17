# Git-flow1
git-flow fluxo
Master está aqui onde temos todo o código de produção, todas as novas funcionlidade que estamos desenvolvendo, em algum momento será mesclado ou associado a essa filial mestre.

Develop contém o código do nosso próximo deploy, isso significa que, como recursos ou funcionalidades, será finalizado e será adicionado nesta remificação para posteriormente passar por mais uma etapa antes de ser associado a um mestre.

Feature são branches para o desenvolvimento de uma funcionalidade específica, eles devem ter o nome iniciado por feature, por exemplo: feature/payment-system. É importante saber que essas ramificações de recursos são criadas sempre a partir do desenvolvimento da ramificação.

Release tem uma confiaça maior no desenvolvimento de uma filial e se encontra no nível de preparação para se juntar a um mestre e no desenvolvimento (caso alguma coisa tenha sido modificada na ramificação em questão).

Hotfix é um ramo usado para corrigir erros encontrados na sistema. Elas são  criadas a partir do mestre e não as alterações finais da filia (hotfix) devem ser juntadas tanto ao mestre da filial quanto ao desenvolvimento da filial.
