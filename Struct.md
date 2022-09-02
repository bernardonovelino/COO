#include <stdio.h>
int main() {

struct ficha_de_endereco {
	char rua;
	int numero;
	char bairro;
	char cidade;
	int CEP;
	char estado[2];
	};
	
struct ficha_pessoal {
	char nome[50];
	char email;
	int telefone[11];
	
	struct  ficha_de_endereco endereco;	
}cad_pessoal [2];



}	
	//como puxar o endereço da struct acima?
	//a struct fica dentro ou fora da função main?