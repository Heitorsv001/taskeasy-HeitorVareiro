# TaskEasy — estrutura inicial

Projeto Java de console preparado no NetBeans. A implementação atual contém apenas a classe de entrada, que imprime `Bem-vindo ao sistema TaskEesy`.

Não há gerenciamento de tarefas, menus interativos, cadastro, persistência ou interface gráfica implementados. O nome TaskEasy descreve o projeto; não indica a existência dessas funcionalidades.

## Organização e ferramentas

- Java, com `javac.source=21` e `javac.target=21` em `nbproject/project.properties`.
- Estrutura de projeto NetBeans e scripts de build Apache Ant.
- Código em `taskeasy-heitorVareiro/src/taskeasy/heitorvareiro/TaskeasyHeitorVareiro.java`.
- Sem bibliotecas externas ou banco de dados.

O repositório também contém arquivos compilados e configurações locais da IDE. Para executar, prefira compilar o código-fonte.

## Execução pelo terminal

Com JDK 21 instalado:

```sh
git clone https://github.com/Heitorsv001/taskeasy-HeitorVareiro.git
cd taskeasy-HeitorVareiro/taskeasy-heitorVareiro
mkdir -p out
javac -encoding UTF-8 -d out src/taskeasy/heitorvareiro/TaskeasyHeitorVareiro.java
java -cp out taskeasy.heitorvareiro.TaskeasyHeitorVareiro
```

Os comandos são para um terminal compatível com shell POSIX. Como alternativa, abra a pasta `taskeasy-heitorVareiro` como projeto no NetBeans e selecione um JDK 21. Não há variáveis de ambiente específicas, serviços ou dependências da aplicação a configurar.

## Estado atual

É uma estrutura inicial de estudo, sem aplicação de gerenciamento de tarefas desenvolvida. O código-fonte é idêntico ao encontrado em [testeEngenharia](https://github.com/Heitorsv001/testeEngenharia); os repositórios não demonstram funcionalidades diferentes.

Os arquivos XML do projeto foram analisados sem erros de sintaxe XML. Compilação e execução não foram verificadas nesta revisão porque o ambiente não dispõe de JDK. Não há testes automatizados nem capturas de tela identificadas.

Mantido na conta [Heitorsv001](https://github.com/Heitorsv001). Repositório original: [Heitorsv001/taskeasy-HeitorVareiro](https://github.com/Heitorsv001/taskeasy-HeitorVareiro).
