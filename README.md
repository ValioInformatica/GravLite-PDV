# O que é o projeto GravLite PDV?
O GravLite PDV é um sistema PDV (Ponto de Venda) para o Varejo que faz parte de uma suite de aplicativos denominados GRAVIS*(APPS) da empresa Valio informática, onde apenas o GravLite PDV é OPEN SOURCE e desenvolvido para atender 1 ponto de venda. Este projeto pretende ajudar pequenos varejistas e desenvolvedores de sistema.

É um sistema limitado a 1 PDV? Não, o desenvolvimento deste projeto é focado para que o GravLite PDV possa comunicar-se com aplicações retaguarda, portanto este projeto limita-se em apenas desenvolver o PDV.

## O projeto GravLite PDV prevê as seguintes funcionabilidades básicas:
### Administração do PDV
* Cadastro de usuários (Caixas);
* Cadastro de produtos com os campos necessários;
* Cadastro de serviços com os campos necessários;
*  Cadastro e configuração financeira (Cartões, TEF);
* Alteração de preços;
* Relatorio de fluxo de produtos passados pelo PDV
* Relatorio de vendas do PDV;
* Gerar arquivo de balança;

### Funções do PDV
* Sistema de venda, emissão e impressão de CF-e SAT;
* Sistema de venda, emissão e impressão de NFe;
* Sistema de ordem de serviços, emissão e impressão de NFSe;

### Compatibilidade com SAT's
* Emulador SEFAZ (testado);
* Tanca (não testado);
* Daruma (não testado);
* Bematech (não testado);
* Dimep (não testado);
* ...

### Compatibilidade com impressoras não fiscais
* Bematech MP4500 TH (não testado);
* Epson TM-T20 (não testado);
* Tanca TP-650 (não testado);
* Daruma DR800 (não testado);
* ...

### Tecnologias utilizadas
* Node.js;
* electron;
* jQuery;
* MariaDb;
