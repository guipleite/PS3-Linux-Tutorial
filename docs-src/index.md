# Coloque aqui o nome do tutorial de vocês

- **Alunes:** .../ ... /...
- **Curso:** Engenharia da Computação
- **Semestre:** 9
- **Contato:** corsiferrao@gmail.com
- **Ano:** 2020

## Começando

Para seguir esse tutorial é necessário:

- **Hardware:** DE10-Standard e acessórios
- **Softwares:** Quartus 18.01
- **Documentos:** [DE10-Standard_User_manual.pdf](https://github.com/Insper/DE10-Standard-v.1.3.0-SystemCD/tree/master/Manual)

## Motivação

Expliquem porque quiseram fazer esse tutorial.

----------------------------------------------

!!! info 
    Essas duas partes são obrigatórias no tutorial:
    
    - Nome de vocês
    - Começando
    - Motivação

## Recursos Markdown

Vocês podem usar tudo que já sabem de markdown mais alguns recursos:

!!! note 
    Bloco de destaque de texto, pode ser:
    
    - note, example, warning, info, tip, danger
    
!!! example "Faça assim"
    É possível editar o título desses blocos
    
    !!! warning
        Isso também é possível de ser feito, mas
        use com parcimonia.
    
??? info 
    Também da para esconder o texto, usar para coisas
    muito grandes, ou exemplos de códigos.
    
    ```txt
    ...
    
    
    
    
    
    
    
    
    
    
    
    oi!
    ```
    
- **Esse é um texto em destaque**
- ==Pode fazer isso também==

Usar emojis da lista:

:two_hearts: - https://github.com/caiyongji/emoji-list


```c
// da para colocar códigos
 void main (void) {}
```

É legal usar abas para coisas desse tipo:
    
=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

Inserir vídeo:

-  Abra o youtube :arrow_right: clique com botão direito no vídeo :arrow_right: copia código de incorporação:

<iframe width="630" height="450" src="https://www.youtube.com/embed/UIGsSLCoIhM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

!!! tip
    Eu ajusto o tamanho do vídeo `width`/`height` para não ficar gigante na página
    
Imagens você insere como em plain markdown, mas tem a vantagem de poder mudar as dimensões com o marcador `{width=...}`
    
![](icon-elementos.png)

![](icon-elementos.png){width=200}
