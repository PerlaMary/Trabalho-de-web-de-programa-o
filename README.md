# Trabalho-de-web-de-programa-o
TRABALHO DE PROGRAMAÇÃO DE WEB 


1 QUESTAO :var valorum = 13;

if(valorum > 10){
	document.write(valorum + " É MAIOR QUE 10 ! " );
}
if(valorum < 10){
	document.write(valorum + " NÃO É MAOIR QUE 10 ! " )
}




2 QUESTÃO :

var bimestreum = 10;
var bimestredois = 8;
var bimestretres = 7;
var bimestrequatro = 5;
var totaladicao = bimestreum + bimestredois + bimestretres + bimestrequatro ;
    console.log(totaladicao);

var totaldivisao = totaladicao / 4 ;
     console.log(totaldivisao);
             document.write("MÉDIA FINAL: " +totaldivisao);


var nota = 7.5 ;
   if(nota >= 5 ){
	document.write(" \n Aprovado<br>");
}else if((nota < 5) && (nota >= 5)){
	document.write(" \n Recuperação<br>");
}else{
	document.write(" \n Reprovado<br>");
}




3 questão:
 
        let empregado = [18,19,20]
        let anoNasc = 1956;
        let anoAtual = 2022;
        let idade = anoAtual - anoNasc;
        let tempTrabalho = idade - 35;

        if(idade >=60 && tempTrabalho >= 25){
            document.write("Empregado: "+ empregado[2] + "<br>Idade: " + idade + " anos. <br> Ingressou na empresa á: " + tempTrabalho + " anos <br>Requer aposentadoria")
            

        }else if (idade >= 65 || tempTrabalho >= 30){
            document.write("Empregado: "+ empregado[2] + "<br>Idade: " + idade + " anos. <br> Ingressou na empresa á: " + tempTrabalho + " anos <br>Requer aposentadoria")
        }
        
        else {
            document.write("Empregado: "+ empregado[2] + "<br>Idade:"  + idade + " anos. <br> Ingressou na empresa á: " + tempTrabalho + " anos <br>Não requer aposentadoria")
        }



4 questao: 
var quantidadeAdiquerida = 3;
var precoUnitario = 10;

var total = quantidadeAdiquerida * precoUnitario;
var desconto = 30 * 0.02 ;
var toltalpagar = total - desconto;



    document.write("Produto: ARROZ");
document.write("<br> Quantidade adquirida: " + quantidadeAdiquerida);
document.write("<br> Preço unitário: " + precoUnitario);
document.write(" <br>Total: " + total);
document.write("<br> total a pagar: " +toltalpagar);
document.write("<br> Desconto: " );


        if (quantidadeAdiquerida <= 5) {
            document.write("desconto será de 2%")
        } else if (quantidadeAdiquerida > 5 && quantidadeAdiquerida <= 10) {
            document.write("<br>desconto será de 3%")
        } else if (quantidadeAdiquerida > 10) {
            document.write("desconto será de 5%")
        }




5 queatao: 
let code = 14;

if(code == 1){
  console.log("Alimento não-perecível");
  
}else if(code >= 2 && code <= 4){
  console.log("Alimento perecível");
  
}else if(code == 5 || code == 6){
  console.log("Vestuário");
  
}else if(code == 7){
  console.log("Higiene Pessoal");
  
}else if(code >= 8 && code <= 15){
  console.log("Limpeza e Utensilios Domėsticos");
  
}else{
  console.log("código inválido");
  
}



6 questao:
let productCode = 100;
let quantity = 4;
let productPrice = 1.70;
let totalValue = productPrice * quantity;
let TotalValue = totalValue.toLocaleString("pt-BR", {style: "currency", currency: "BRL"});

switch(productCode){
  case 100:
   console.log(`
    <strong>
    Código do produto: ${productCode}<br>
    Quantidade: ${quantity}<br>
    Valor total: ${TotalValue}
    </strong>
    `)
  break
  case 101:
   console.log(`
    <strong>
    Código do produto: ${productCode}<br>
    Quantidade: ${quantity}<br>
    Valor total: ${TotalValue}
    </strong>
    `)
  break
  case 102:
   console.log(`
     <strong>
     Código do produto: ${productCode}<br>
     Quantidade: ${quantity}<br>
     Valor total: ${TotalValue}
     </strong>
      `)
  break
  case 103:
   console.log(`
     <strong>
     Código do produto: ${productCode}<br>
     Quantidade: ${quantity}<br>
     Valor total: ${TotalValue}
     </strong>
      `)
  break
  case 104:
   console.log(`
     <strong>
     Código do produto: ${productCode}<br>
     Quantidade: ${quantity}<br>
     Valor total: ${TotalValue}
     </strong>
      `)
  break
  case 105:
   console.log(`
     <strong>
     Código do produto: ${productCode}<br>
     Quantidade: ${quantity}<br>
     Valor total: ${TotalValue}
     </strong>
      `)
  break
  default: console.log("<strong>Digite o código de um produto</strong>");
}



7: 

let i = 101;


for(let i = 101; i < 111; i++){
    
	document.write("<br>" +i)

}




8 questao:
ver n = 20;
    for ( let i = 1, i <= n; n ++ ){
    


     document.write ( "<br> " + i )
}
     














9 questao:

function tabuada() {
    for (var count=1; count<=10; count++)
    document.write("8 x" + count + "=" + (8 * count) + "<br/>");
}












10 questao:



for(let i = 1; i < 11; i++){
	document.write("<br>" +i)
}

for(let i = 10; i > 0; i--){
	if( i === 5){
		continue;
	}
	document.write("<br>" +i)
} 
