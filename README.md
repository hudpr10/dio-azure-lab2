# Azure - Reforçando Conceitos
## Resumo
-Nesse LAB a monitora nos apresentou as porcentagens dos serviços com base nas regras de indisponibilidade (SLA), a Azure oferece diversas opções desde a menos coberta (99% - o serviço PODE ficar inativo por 1.68h durante a semana) até a mais coberta (99,999% - o serviço PODE ficar inativo por 6 segundos durante a semana), vale relembrar que se caso o serviço fique inativo por mais tempo durante o período a Microsoft fornecerá um voucher para compensar a falha do serviço. Obviamente cada opção de SLA possuí um preço diferente, aquelas com maior cobertura contra as falhas vão ter preços mais elevados.
-Além das porcentagens SLA a monitora mostrou como chegar a documentação e tirar dúvidas a respeito de determinadas configurações do serviço, por exemplo, ao criar uma máquina virtual, muitas das opções de configuração possuem um ícone de informação, permitindo o usuário se informar melhor sobre a configuração e caso necessário acessar a documentação completa feita pela Microsoft.
-Ao criarmos nossos serviços podemos selecionar mais de uma região, isso é muito útil quando precisamos de maior segurança e disponibilidade dos dados que ali estão armazenados, selecionar mais de uma zona permite que os dados sejam armazenados 2 vezes em locais diferentes, e caso um local falhe ainda possuí outro em funcionamento, o que também implica no SLA, na Alta Disponibilidade e no custo. Estratégias de armazenamento com redundância, LRS (local), GRS (geográfica), ZRS (zona) e GZRS (zona geográfica).
-São serviços que podem ser caros mas que podem oferecer maior segurança, contudo é sempre necessário avaliar o cenário e o contexto para entender qual estratégia é a melhor possível, procurando economizar dinheiro e garantir funcionamento.
