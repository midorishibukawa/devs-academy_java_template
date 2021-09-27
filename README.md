# Como utilizar este modelo do zero

Para utilizar este modelo do zero, sem repositórios pré-existentes, siga as seguintes instruções:

1. Bifurque este repositório

2. Clone a bifurcação em sua máquina local

3. Utilize o modelo à vontade

Sinta-se livre para utilizar quaisquer partes do modelo como bem entender!

# Como utilizar este modelo com repositórios pré-existentes

É possível simplesmente copiar todos os arquivos `.java` para os diretórios de seus respectivos exercícios, mas fazê-lo implica em perder todos os commits de repositórios pré-existentes.

Para migrar de múltiplos repositórios para um único repositório utilizando este modelo, siga as seguintes instruções:

1. Bifurque este repositório

2. Clone a bifurcação em sua máquina local

3. Execute o seguinte comando para cada repositório (substitua `{{ ??? }}` pelo valor indicado):
    <pre><code>
    git subtree add <i>{{ caminho para o diretório do repositório no modelo }}</i> {{ caminho para o repositório original }} {{ nome da branch }}
    </code></pre>

    Obs. 1: No lugar do `caminho para o repositório original`, é possível utilizar o caminho para o diretório git local de sua máquina (p.ex.: ../caminho/para/o/diretorio/git/local).

    Obs. 2: Caso você **não** deseje manter um histórico de commits único no monorrepositório, adicione a flag `--squash` ao final do comando.

4. Faça um commit para salvar as alterações

5. Faça um push para enviar o novo monorrepositório para o repositório remoto

# Devs Academy: Atividades Java
Atividades de Java para o curso Desenvolvimento Web Full-Stack Devs Academy da Digital House em parceria com a Deloitte.

Índice:

1. [Introdução à POO](src/_01_introducao_a_poo)
    - [Exercício 01](src/_01_introducao_a_poo/exercicio_01)
    - [Exercício 02](src/_01_introducao_a_poo/exercicio_02)

2. [POO e Java](rc/_02_poo_e_java)
    - [Exercício 01](src/_02_poo_e_java/exercicio_01)
    - [Exercício 02](/src/_02_poo_e_java/exercicio_02)
    - [Exercício 03](src/_02_poo_e_java/exercicio_03)
    - [Exercício 04](src/_02_poo_e_java/exercicio_04)
    - [Exercício 05](src/_02_poo_e_java/exercicio_05)
    - [Desafio](src/_02_poo_e_java/desafio)

3. [Herança e Classe Abstrata](src/_03_heranca_e_classe_abstrata)
    - [Exercício 01](src/_03_heranca_e_classe_abstrata/exercicio_01)
    - [Exercício 02](src/_03_heranca_e_classe_abstrata/exercicio_02)

4. [Loops e Arrays](src/_04_loops_e_arrays)
    - [Exercício 01](src/_04_loops_e_arrays/exercicio_01)
    - [Exercício 02](src/_04_loops_e_arrays/exercicio_02)
    - [Exercício 03](src/_04_loops_e_arrays/exercicio_03)
    - [Exercício 04](src/_04_loops_e_arrays/exercicio_04)
    - [Exercício 05](/src/_04_loops_e_arrays/exercicio_05)
    - [Exercício 06](src/_04_loops_e_arrays/exercicio_06)
    - [Exercício 07](src/_04_loops_e_arrays/exercicio_07)
    - [Exercício 08](src/_04_loops_e_arrays/exercicio_08)
    - [Exercício 09](src/_04_loops_e_arrays/exercicio_09)
    - [Exercício 10](src/_04_loops_e_arrays/exercicio_10)

5. [Testes e Debugs](src/_05_testes_e_debugs)

6. [Interfaces](src/_06_interfaces)
    - [Atividade 01](src/_06_interfaces/atividade_01)
      - [Exercício 01](src/_06_interfaces/atividade_01/exercicio_01)
      - [Exercício 02](src/_06_interfaces/atividade_01/exercicio_02)
    - [Atividade 02](src/_06_interfaces/atividade_02)
      - [Exercício 01](src/_06_interfaces/atividade_02/exercicio_01)
      - [Exercício 02](src/_06_interfaces/atividade_02/exercicio_02)

7. [Equals, Override, Overload, This](sc/_07_equals_override_overload_this)

8. [Collection (Estrutura de Dados)](src/_08_collection_estrutura_de_dados)
    - [Atividade 01](src/_08_collection_estrutura_de_dados/atividade_01)
      - [Exercício 01](src/_08_collection_estrutura_de_dados/atividade_01/exercicio_01)
      - [Exercício 02](src/_08_collection_estrutura_de_dados/atividade_01/exercicio_02)
      - [Exercício 03](src/_08_collection_estrutura_de_dados/atividade_01/exercicio_03)
      - [Exercício 04](src/_08_collection_estrutura_de_dados/atividade_01/exercicio_04)
    - [Atividade 02](src/_08_collection_estrutura_de_dados/atividade_02)
      - [Exercício 01](src/_08_collection_estrutura_de_dados/atividade_02/exercicio_01)
      - [Exercício 02](src/_08_collection_estrutura_de_dados/atividade_02/exercicio_02)
      - [Exercício 03](src/_08_collection_estrutura_de_dados/atividade_02/exercicio_03)
      - [Exercício 04](src/_08_collection_estrutura_de_dados/atividade_02/exercicio_04)
      - [Exercício 05](src/_08_collection_estrutura_de_dados/atividade_02/exercicio_05)
 
9. [Exceções](src/_09_excecoes)
    - [Exercício 01](src/_09_excecoes/exercicio_01)
    - [Exercício 02](src/_09_excecoes/exercicio_02)
    - [Exercício 03](src/_09_excecoes/exercicio_03)
