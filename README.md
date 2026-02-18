O JaCoCo (Java Code Coverage) é a ferramenta padrão para isso no ecossistema Java.
Para executar todos os testes (unitários e de integração) e gerar o relatório de cobertura, use o Maven:
```
mvn clean verify
```

Após a execução, o relatório HTML será gerado em:
```
target/site/jacoco/index.html
```

Abra este arquivo em seu navegador. O relatório mostrará uma visão geral da cobertura por pacote, classe e até por linha de código, indicando quais partes foram cobertas e quais não foram.