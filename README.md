# lista-2-de-lab.Algoritmos-
Lista 2
Lista-2, vetores
//QUESTÃO-1//
#include<stdio.h> //declaração de blibiotecas//
#include<stdlib.h>
#include<locale.h>
Int main(void){
Int tamanho,i.menor,maior,soma;// essa linha foi feita a declaração das 
variáveis//
setlocale(LC_ALL,”portuguese”);
printf(“universidade federal rural do semi-àrido-Ufersa\n”);
printf(“disciplina:PEX1243\n);
printf(“Aluno: Samuel A. da Cruz\n”);
printf(“informe a tamanho do vetor:\n”);
scanf(“%d”,&tamanho);
int*vetor=(int*)malloc(tamanho*sizeof(int));//solicita o tamanho do vetor//
 if(vetor==NULL) { 
 printf(“Não há espaço suficiente na memória!!!”);
exit(1);
}
 For(i=0;i<tamanho;i++) { //esse laço de repetição tem por função verificar e 
faz o loop até a afirmação ser falsa//
Printf(“digite o tamanho do vetor”);
Scanf(“&d”,&vetor[i]);
If(maior<vetor[i]){ //verifica qual o maior número//
 Maior=vetor[i];// tem por função armazenar o maior vetor em vetor//
}
If(maior>vetor[i]{ //verifica qual o menor número//
 Menor=vetor[i];// tem por função armazenar o menor vetor em vetor//
}
//QUESTA-2//
#include<stdio.h>// declaração de bibliotecas//
#include<stdlib.h>
#include<locale.h>
Int main(void){
Int quantdd,i;
Media=0.0;
Setlocale(LC_ALL,”portuguese”);
Printf(“\tUniversidade Federal do Semi-Árido –Ufersa\n”);
Printf(“\tdisciplina: PEX1243\n”);
Printf(“\tAluno: Samuel A. da Cruz”);
Printf(“\n\n”)
Printf(“\tInforme a quantidade de alunos:”)//faz a solicitação da quantidade de 
alunos//
 Scanf(“%d”,&quantdd);
Float*vetor_notas=(float*)malloc(quantdd*sizeof(float));//fazendo o uso da 
alocação dinâmica//
If(vetor_notas==NULL{ 
 Printf(“Não há espaço suficiente na memória!!!”);
Exit(1); // tem por função finalizar o programa caso não tenha espaço 
suficiente disponível na memória//
For(i=0;i<quantidade;i++);{ //passa pela quantidade de notas informadas no 
primeiro printf//
Printf(“\tdigite a %d.o notas”,i+1);
Scanf(“%d”,&vetor_notas[i]);
Media=media+vetor_notas[i]; // nessa linha faz a soma da media//
Return0;
}
//QUESTÃO-3//
#include<stdio.h>// declaração de bibliotecas//
#include<stdlib.h>
#include<locale.h>
Void preenche_ordenado(int n, int *v);//protótipo da função declarado//
Int main(void){
Int n,i,s;
Int main(void){// essa linha é o programa principal//
Int n,i,s; // essa linha é a declaração das variáveis//
Setlocale(LC_ALL,”´portuguese”);
Printf(“\Tuniversidade Rural do semi-árido Ufersa\n”);
Printf(“\tdisciplina:PEX1243\n);
Printf(“\tAluno:Samuel A. da Cruz”);
Printf(\n\n);
Printf(“informe os elementos dos vetores:”);// solicita a quantidade de número 
do vetor;
 Scanf(“%d”,&n); // onde recebe os valores fornecidos no printf//
int*vetor=(int*)malloc(n*sizeof(int)); // linha onde faz-se alocação dinâmica dos 
valores//
if(vetor==NULL){ //linha de verificação se há espaço na memória
suficiente//
printf("não há memoria!");
exit(1);//tem por função finalizar o programa caso não tenha 
espaço de memória suficiente//
}
for(i=0;i<n;i++){ //laço de repetição que pede e passa por cada um dos números
digitados//
printf("Digite a quantidade de números: "); // solicita a quantidade de números//
scanf("%d", &vetor[i]);//onde ocorre o recebimento dos 
valores fornecidos//
preenche_ordenado(n, vetor); 
preenche_ordenado(n, vetor); //linha que faz chamada do 
vetor//
}
for(int j=n-1;j>=0;j--){ // linha que faz o decremento dos números para exibir ao 
contrario//
printf("[%d]\n", vetor[j]);
printf("[%d]\n", vetor[j]); //faz a apresentação dos vetores 
aleatórios//
}
printf("\n")
free(vetor); //faz se o uso do free para liberar memória//
return 0;
return 0; //fim de programa//
}
void preenche_ordenado(int n, int *v){
int j, resposta;
for(int i=0;i<n;i++){
void preenche_ordenado(int n, int *v){ // preenche os vetores aleatórios//
int j, resposta; //linha onde ocorre a declaração de variável//
for(int i=0;i<n;i++){ // laço de repetição alinhado que tem por função passar
pelos números do vetor//
for( j=0;j<n;j++);
resposta=v[j];
resposta=v[j]; // linha onde recebe o vetor e faz o armazenamento em 
uma nova variável //
if(resposta>v[j]){
v[i]=v[j]){
v[i]=v[j];
v[i]=v[j]; //faz a troca de posição//
v[j]=resposta;
}
}
}
//QUESTÃO-4//
#include<stdio.h> //declaração de bibliotecas//
#include<stdlib.h> 
#include<locale.h> 
#define macro RAND_MAX //nessa linha faz-se a definição de uma variável fixa 
para os números aleatórios//
int main(void){
int j;
double num, *vetor;
setlocale(LC_ALL, "Portuguese");
printf("Universidade Federal Rural do Semi-Árido-Ufersa\n ");
printf("Diciplina: PEX1243 \n");
printf("Aluno:Samuel A. da Cruz ");
printf("\n\n");
printf("\Digite o numero dos vetores: "); //solicita o número de vetores//
scanf("%f", &num);
vetor=(double*) malloc(num*sizeof(double));//essa linha executa e abre o 
espaço da memória com uso da função malloc//
printf("Intervalo da rand = [0,%d] \n", RAND_MAX);//traz a informação do 
intervalo de rand//
for(j=1; j<=10; j++){ // laço que tem a função de passar pelos num de repetição
de 10 fixos//
printf("Numero %d = %d \n", j, rand()); // essa linha são de 
números aleatórios//
}
 for(j=1; j<=num; j++){ // laço que repete aleatoriamente os números
fornecidos dos usuários//
printf("Numero %d = %d \n", j, rand()); //faz exibição dos números aleatórios//
free(vetor); // libera o espaço da memoria
return 0;
}
}
