# TatianeMendonca
PARADIGMAS DE LINGUAGEM DE PROGRAMAÇÃO EM CIÊNCIA DE DADOS - Trilha 1
arquivo = open('arq01.txt','w')
arquivo.write("Lei de Zipf\n")
arquivo.write("Criando um arquivo de texto com Python\n")
arquivo.write("Arquivo criado por Tatiane M S Guimaraes\n")
arquivo.close()
print("\n")
texto = input("A Lei de Zipf é uma lei empírica formulada utilizando estatísticas matemáticas que se refere ao fato de que para muitos tipos de dados estudados nas ciências físicas e sociais, a distribuição de frequência de classificação é uma relação inversa:\n")
arquivo = open('arq01.txt','a')
arquivo.write(texto + "\n")
print("Pesquisa " + oython.linguagem + " Google Chrome " + arquivo.mode)
arquivo.close()

print("\nTexto alterado:")
arquivo = open('arq01.txt','r')
for linha in arquivo:
    linha = linha.rstrip()
    print (linha)
arquivo.close()
