<h1 align="center">QUERY-FILMS</h1>

É sistema de consulta de filme que possue quatro metodos de consulta:

1. Atores que interpretaram a si próprios.
   
  - `Consultas.java`
    
     ```java
     public Set<String> atoresQueInterpretaramSiProprios() {
       // codigo.
     }
     ```
   
2. Atores que atuaram em filmes de um determinado diretor, por ordem alfabética.
   
- `Consultas.java`
  
    ```java
     public List<String> atoresQueAtuaramEmFilmesDoDiretorEmOrdemAlfabetica(String diretor) {
       // codigo.
     }
     ```

3. Filmes em que o diretor atuou (ou pelo menos um deles), por ordem de lançamento (mais recentes primeiro).

- `Consultas.java`
  
    ```java
      public List<Filme> filmesEmQuePeloMenosUmDiretorAtuouMaisRecentesPrimeiro() {
        // codigo.
      }
     ```

4. Filmes lançados em um determinado ano, agrupados por categoria.

- `Consultas.java`
  
    ```java
      public Map<String, Set<Filme>> filmesLancadosNoAnoAgrupadosPorCategoria(int ano) {
        // codigo.
      }
     ```

Todos os metodos manipulam os dados de uma classe que representa um filme:

```java
import java.util.Map;
import java.util.Set;

public class Filme {

  public final String titulo;
  public final int anoDeLancamento;
  public final Set<String> categorias;
  public final Set<String> diretores;
  public final Set<String> atores;
  public final Set<String> personagens;
  public final Map<String, Set<String>> atoresPorPersonagem;

  // ...
}
```

### Languagens/Frameworks/Ferramentas

[![My Skills With Front-End](https://skillicons.dev/icons?i=java,maven)](https://skillicons.dev)

## 🚀 Instalando o projeto

Para instalar o projeto, siga estas etapas:

```
mvn install
```
