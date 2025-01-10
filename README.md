# PHP-AULA-CURSO  <?php
//SWITCHS CASE

$cidade = "RJ";

switch($cidade){
  case "BH";
  echo "Belo Horizonte";
 break;
 
 case "SP";
 echo "São Paulo";
 break;
 
 case "RJ";
 echo "Rio de Janeiro";
 break;
}
	
?>

<?php
//TERNARIA
$idade = 20; echo($idade >= 18) ? "Adulto" : "Criança";
?>

//loop foor

<?php
//loop for 
for($i = 0; $i<10; $i++){
  echo "Numero "  .$i;
  echo "\n";
}
?>



<?php
//loop FOREACH 

$alunos = ["aluno 1", "aluno 2", "aluno 3"];
FOREACH ($alunos as $alunos){
   echo "Pessoa : ".$alunos;
   echo "\n";

}
?>

<?php
//loop WHILE
$cont = 0;

WHILE($cont <= 10){
  echo "Contador valendo ".$cont;
  echo "\n";
  
  $cont++;



}
?>


<?php
//loop DO WHILE
$cont = 0;

do{
  echo $cont;
  $cont++;
} while ($cont < 10);



?>
