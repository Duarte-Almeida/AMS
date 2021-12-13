# Org/Participant/Role and their activities

#### uaTEC
* Fazer relANL
* Fazer um relEND
* Analisar o relINT

#### ugTEC
* Fazer um plnINT
* Analisar o relINT

#### eINT
* Executar o plnINT
* Desligar a máquina manualmente
* Ligar a máquina manualmente
* Fazer o relINT

#### appCTR
* Informar a appMNG quando uma máquina é desligada

#### appMNG
* Gerar eventos
* Informar gePRO acerca de algum evento

#### arPRO
* Usar máquina

#### gePRO
* Reservar na appMNG o intervalo de tempo que uma arPRO sua irá utilizar uma máquina

# Object/Message
* relANL
* relEND
* plnINT
* relINT

# Eventos que dão início à manutenção

* uaTEC regista nova versão de appCTR;
* appCTR informa que foi desligada manualmente;
* TWIN avisa de avaria identificada;
* TWIN avisa de avaria inferida;
* TWIN avisa de impossibilidade de se atingir um ponto de carregamento das baterias por distância excedida;
* Avaria inferida porque não está a decorrer instalação da appCTR e a mesma não reportou nada dentro de intervalo de tempo para tal definido pelo fornecedor.

# Apontamentos adicionais relativos à manutenção

* Enquanto decorre uma execução do processo de manutenção para uma máquina, ela não pode ser reservada por algum gePRO
* Todos os relatórios relativos à execução de um processo de manutenção são editados ou consultados diretamente na appMNG.