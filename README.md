#include <stdio.h>
#include <stdlib.h>

int main () {

	int opcao=0;
	
	while ((opcao!=1 ) && (opcao!=2) && (opcao !=3)){
	
		system("cls");
		printf("MENU \n\n");
	
		printf("1- Cadastro das Notas dos(as) Alunos(as)\n");
		
		printf("2- Alteracao das Notas\n");
		
		printf("3- SAIR\n\n");
		
		printf("escolha uma opcao: ");
		scanf("%i", &opcao);
		
		if(opcao==1){
		
			system("cls");   
			
			char nome, nome2, nome3,nome4,nome5;
			
			float nota1, nota2, nota3, nota4;
			float nota5, nota6, nota7, nota8;
			float nota9, nota10, nota11, nota12;
			float nota13, nota14, nota15, nota16;
			float nota17, nota18, nota19, nota20;
			
			printf("CADASTRO DE NOTAS DOS(AS) ALUNOS(AS) \n\n");
			
			// Cadastro do Primeiro(a) Aluno(a)
			
			printf("Escreva o nome do(a) primeiro(a) aluno(a): \n");	
			scanf("%s", &nome);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota1);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota2);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota3);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota4);
			
			system("pause");
			
			// Cadastro do Segundo(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva o nome do(a) segundo(a) aluno(a): \n");
			scanf("%s", &nome2);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a) \n");
			scanf("%f",&nota5);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a)\n");
			scanf("%f",&nota6);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a)\n");
			scanf("%f",&nota7);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a)\n");
			scanf("%f",&nota8);
			
			system("pause");
			
			// Cadastro do(a) Terceiro(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva o nome do(a) terceiro(a) aluno(a): \n");
			scanf("%s", &nome3);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota9);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota10);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota11);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota12);
			
			system("pause");
			
			// Cadastro do(a) Quarto(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva o nome do(a) quarto(a) aluno(a): \n");
			scanf("%s", &nome4);
			
			printf("Escreva as notas do(a) quarto(a) aluno(a)\n");
			scanf("%f",&nota13);
		
			printf("Escreva as notas do(a) quarto(a) aluno(a)\n");
			scanf("%f",&nota14);
		
			printf("Escreva as notas do(a) quarto(a) aluno(a):\n");
			scanf("%f",&nota15);
		
			printf("Escreva as notas do(a) quarto(a) aluno(a)\n");
			scanf("%f",&nota16);
			
			system("pause");
			
			// Cadastro do(a) Quinto(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva o nome do(a) quinto(a) aluno(a): \n");
			scanf("%s", &nome5);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota17);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota18);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota19);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota20);

			float mediaAluno1 = (nota1 + nota2 + nota3 + nota4)/4;
			float mediaAluno2 = (nota5 + nota6 + nota7 + nota8)/4;
			float mediaAluno3 = (nota9 + nota10 + nota11 + nota12)/4;
			float mediaAluno4 = (nota13 + nota14 + nota15 + nota16)/4;
			float mediaAluno5 = (nota17 + nota18 + nota19 + nota20)/4;
			
			
			system("cls");
			
			printf("A media do primeiro aluno e %.1f \n", mediaAluno1);
			
			printf("A media do segundo aluno e  %.1f \n", mediaAluno2);
			
			printf("A media do terceiro aluno e %.1f \n", mediaAluno3);
			
			printf("A media do quarto aluno e %.1f \n", mediaAluno4);
			
			printf("A media do quinto aluno e %.1f \n", mediaAluno5);
			
			system("pause");
			system("cls");
		
				 if (mediaAluno1<4){
				 
				printf("O primeiro aluno esta reprovado\n");				
				}
				else if (mediaAluno1>=6){
					 printf("O primeiro aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno1<6){
					 	 printf("O primeiro aluno esta de recuperacao\n");
						 }
						 
						system("pause");
						 
				if (mediaAluno2<4){
				 
				printf("O segundo aluno esta reprovado\n");				
				}
				else if (mediaAluno2>=6){
					 printf("O segundo aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno2<6){
					 	 printf("O segundo aluno esta de recuperacao\n");
						 }
						 
						system("pause");
						
				if (mediaAluno3<4){
				 
				printf("O terceiro aluno esta reprovado\n");				
				}
				else if (mediaAluno3>=6){
					 printf("O terceiro aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno3<6){
					 	 printf("O terceiro aluno esta de recuperacao\n");
						 }
						 
						 system("pause");
						 
				if (mediaAluno4<4){
				 
				printf("O quarto aluno esta reprovado\n");				
				}
				else if (mediaAluno4>=6){
					 printf("O quarto aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno4<6){
					 	 printf("O quarto aluno esta de recuperacao\n");
						 }
						 
						 system("pause");
						 
				if (mediaAluno5<4){
				 
				printf("O quinto aluno esta reprovado\n");				
				}
				else if (mediaAluno5>=6){
					 printf("O quinto aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno5<6){
					 	 printf("O quinto aluno esta de recuperacao\n");
						 }
						 
						 system("pause");
			
		} 
		if ( opcao==2 ) {
			
			system("cls");
			printf("Alteracao de Notas\n\n");
			
			
			
			char nome, nome2, nome3,nome4,nome5;
			
			float nota1, nota2, nota3, nota4;
			float nota5, nota6, nota7, nota8;
			float nota9, nota10, nota11, nota12;
			float nota13, nota14, nota15, nota16;
			float nota17, nota18, nota19, nota20;
			
			// Altereção do Primeiro(a) Aluno(a)
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota1);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota2);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota3);
			
			printf("Escreva as notas do(a) primeiro(a) aluno(a)\n");
			scanf("%f",&nota4);
			
			system("pause");
			
			// Altereção do Segundo(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva as notas do(a) segundo(a) aluno(a) \n");
			scanf("%f",&nota5);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a)\n");
			scanf("%f",&nota6);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a)\n");
			scanf("%f",&nota7);
			
			printf("Escreva as notas do(a) segundo(a) aluno(a)\n");
			scanf("%f",&nota8);
			
			system("pause");
			
			// Altereção do(a) Terceiro(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota9);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota10);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota11);
			
			printf("Escreva as notas do(a) terceiro(a) aluno(a)\n");
			scanf("%f",&nota12);
			
			system("pause");
			
			// Altereção do(a) Quarto(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva as notas do(a) quarto(a) aluno(a)\n");
			scanf("%f",&nota13);
		
			printf("Escreva as notas do(a) quarto(a) aluno(a)\n");
			scanf("%f",&nota14);
		
			printf("Escreva as notas do(a) quarto(a) aluno(a):\n");
			scanf("%f",&nota15);
		
			printf("Escreva as notas do(a) quarto(a) aluno(a)\n");
			scanf("%f",&nota16);
			
			system("pause");
			
			// Altereção do(a) Quinto(a) Aluno(a)
			
			system("cls");
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota17);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota18);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota19);
			
			printf("Escreva as notas do(a) quinto(a) aluno(a):\n");
			scanf("%f",&nota20);

			float mediaAluno1 = (nota1 + nota2 + nota3 + nota4)/4;
			float mediaAluno2 = (nota5 + nota6 + nota7 + nota8)/4;
			float mediaAluno3 = (nota9 + nota10 + nota11 + nota12)/4;
			float mediaAluno4 = (nota13 + nota14 + nota15 + nota16)/4;
			float mediaAluno5 = (nota17 + nota18 + nota19 + nota20)/4;
			
			
			system("cls");
			
			printf("A media do primeiro aluno e %.1f \n", mediaAluno1);
			
			printf("A media do segundo aluno e  %.1f \n", mediaAluno2);
			
			printf("A media do terceiro aluno e %.1f \n", mediaAluno3);
			
			printf("A media do quarto aluno e %.1f \n", mediaAluno4);
			
			printf("A media do quinto aluno e %.1f \n", mediaAluno5);
			
			system("pause");
			system("cls");
		
				 if (mediaAluno1<4){
				 
				printf("O primeiro aluno esta reprovado\n");				
				}
				else if (mediaAluno1>=6){
					 printf("O primeiro aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno1<6){
					 	 printf("O primeiro aluno esta de recuperacao\n");
						 }
						 
						system("pause");
						 
				if (mediaAluno2<4){
				 
				printf("O segundo aluno esta reprovado\n");				
				}
				else if (mediaAluno2>=6){
					 printf("O segundo aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno2<6){
					 	 printf("O segundo aluno esta de recuperacao\n");
						 }
						 
						system("pause");
						
				if (mediaAluno3<4){
				 
				printf("O terceiro aluno esta reprovado\n");				
				}
				else if (mediaAluno3>=6){
					 printf("O terceiro aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno3<6){
					 	 printf("O terceiro aluno esta de recuperacao\n");
						 }
						 
						 system("pause");
						 
				if (mediaAluno4<4){
				 
				printf("O quarto aluno esta reprovado\n");				
				}
				else if (mediaAluno4>=6){
					 printf("O quarto aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno4<6){
					 	 printf("O quarto aluno esta de recuperacao\n");
						 }
						 
						 system("pause");
						 
				if (mediaAluno5<4){
				 
				printf("O quinto aluno esta reprovado\n");				
				}
				else if (mediaAluno5>=6){
					 printf("O quinto aluno esta aprovado\n");
					 	} 
						 else if (mediaAluno5<6){
					 	 printf("O quinto aluno esta de recuperacao\n");
						 }
						 
						 system("pause");
			
		}
	  }	
	
		



	return 0;
}
