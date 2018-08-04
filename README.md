# TriVendas
TriVendas é um sistema de busca e listagem de produtos em sites da internet através de Web crawling.
- versao atual 1.1.0
## Requisitos
- Java 1.8
- Maven
- Jsoup
- JavaFX 2.0
  * ```Maven
    <dependency>
          <!-- jsoup HTML parser library @ https://jsoup.org/ -->
          <groupId>org.jsoup</groupId>
          <artifactId>jsoup</artifactId>
          <version>1.11.3</version>
     </dependency>
<img width = "200" height = "125" src="https://github.com/JesuisOriginal/TriVendas/blob/master/src/br/ufrpe/trivendas/gui/resources/images/Jsoup.png" alt="Web App"/>           
- Rest

## Funcionalidades
- Buscar produtos pelo Aliexpress e pelo Walmart
- Mostrar resultados da busca ao usuario, incluindo informação como nomes, fornecedores e preços.
- Organização dos resultados por preço (mais barato para o mais caro)

## Instalação e Execução
* Baixar o arquivo Trivender.jar
- Salvar em algum local do seu PC
- Crt + R, depois digitar CMD e em seguida apertar Enter
- Inserir o seguinte comando no Windows
   * ```CMD
        Java Trivender.jar
## Arquitetura
* ![Diagram](https://raw.githubusercontent.com/JesuisOriginal/TriVendas/master/src/main/java/br.ufrpe.trivendas/gui/resources/images/diagram1_0_1.png?token=Afwk_7pkhm0EVMHiXnkZK3mUg9K6IuIBks5bYcg5wA%3D%3D)
