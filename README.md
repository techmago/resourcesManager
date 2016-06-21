Leonardo Weiss Ribeiro - GRR20103242

Luis Alexandre D. Brandão - GRR20085461

# Descrição

Trabalho desenvolvido na disciplina de Técnicas Alternativas de programação, na Universidade Federal do Paraná.

O objetivo desse trabalho, era desenvolver um sistema de controle de recursos para o departamento de informática. A ideia é permitir que professores façam reserva dos recursos desejados (Salas, projetores, equipamentos), tendo acesso a uma ferramenta digital para isso.

Hoje, tal situação é uma realidade do departamento. As reservas de equipamentos e salas são realizada utilizando cadernos, onde o professor anota numa pagina pré-determinada o dia e hora que algo está sendo emprestado.

# Documentação
Como copilar:
```
javac -classpath ".:./*" controlN.java modelN.java visionN.java
```

Como executar:
```
java -classpath ".:./*" visionN
```

Notas:
```
1. Para executar/copilar o codigo, é necessário que no diretorio do fonte, estejam os arquivos:
		sqlite-jdbc-3.7.2.jar
		swingx-all-1.6.4.jar

2. Após compilado, o programa, na primeira execução, cria um novo banco de dados automaticamente, caso ele não exista.
	É necessario usuario e senha para a utilização do programa. Quando o banco é criado, tambem é criado o usuario padrão "admin" com a senha "admin"
```
