# exercicio-javascript

/* Codigo Condição de pagamento;
1 - À vista Debito, recebe 10% de desconto;
2 - À vista no Dinheiro ou PIX, recebe 15% de desconto;
3 - Em duas vezes, preço de Etiqueta sem juros;
4 - Acima de duas vezes, preço normalde etiqueta mais juros de 10%;
*/
const precoEtiqueta = 100;
const formaDePagamento = 3;
if (formaDePagamento === 1){
    console.log(precoEtiqueta -(precoEtiqueta * 0.1));
}else if(formaDePagamento === 2){
    console.log(precoEtiqueta -(precoEtiqueta * 0.15));
}else if(formaDePagamento === 3){
     console.log(precoEtiqueta);
     console.log("2X 50")
}else{
    console.log(precoEtiqueta + (precoEtiqueta * 0.1));
}
