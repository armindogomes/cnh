# CNH
## Sobre
Projeto cujo objetivo é permitir que se valide numericamente a CNH brasileira. Ainda em estado experimental.

Para usar o componente é bem simples. Use o snippet abaixo como segue:

    var numeroCNH = "01234567890";
    var validarCNH = new CNH();
    var resultado = validarCNH.Validar(numeroCNH);
    
Os testes falharam para uma quantidade pequena de entradas, o que nos leva a crer que não deve ser usado em produção de forma alguma.

Contribuições são bem vindas.

O código deste projeto teve como base um tópico de um forum de discussão que pode ser acessado [aqui](http://www.devmedia.com.br/forum/validacao-do-numero-de-registro-de-cnh/354889)

## Testes

Números válidos de CNH podem ser obtidos aqui:

[DETRAN SUSPENDE CARTEIRAS DE MAIS DE 900 MOTORISTAS](http://www.detran.rj.gov.br/_monta_aplicacoes.asp?doc=9073&cod=14&tipo=exibe_noticias&pag_noticias=true)

[EDITAL DE NOTIFICAÇÃO N° 001/2015](http://www2.detran.ba.gov.br/EditalNotificacao_N%C2%BA001-2015.pdf)
