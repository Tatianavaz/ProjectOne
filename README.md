# ProjectOne


/* Considerar apenas o que está abaixo */

<!DOCTYPE html>
<html>
<head>
<title>Projectone.htm</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta charset="utf-8"/>
</head>
<body>
<h3>Programa de Boas Vindas com Concatenação de campos!</h3>
<!-- Definição de Formulário -->
<form name="FormConcatena" action=" " method="post">
 Digite o nome............: <input type="text" name="f_nome" /><br/>
 Digite o sobrenome...: <input type="text" name="f_sobrenome" /><br/>
 <input type="button" name="btn_concatena" value="Concatenar" onclick="concatena()" />
 <input type="reset" name="btn_cancela" value="Cancelar" />
</form>
<!-- Definição do código JavaScript -->
<script language="javascript">
<!--
/* Objetivo: Capturar nome e sobrenome do usuário, concatenar (juntar) os campos e
apresentar uma saudação personalizada
Elementos de Entrada: método form do objeto document
Elementos de Saída: método alert do objeto window
*/
/* Definição das Variáveis */
var js_nome;
var js_sobrenome;
var js_nomecompleto;
function concatena( ) {/* Entrada de Dados */
js_nome = document.FormConcatena.f_nome.value;
js_sobrenome = document.FormConcatena.f_sobrenome.value;
/* Processamento de Dados */
js_nomecompleto = js_nome + ' ' + js_sobrenome;
/* Saída de Dados */
window.alert('Ol\u00e1 ' + js_nomecompleto);
}
//-->
</script>
</body>
</html>
