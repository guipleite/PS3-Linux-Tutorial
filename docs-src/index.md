# PS3 Hack

- **Alunes:** Gabriel Monteiro / Guilherme Leite / Hugo Carl
- **Curso:** Engenharia da Computação
- **Semestre:** 9
- **Contato:** corsiferrao@gmail.com, guilhermepl3@al.insper.edu.br
- **Ano:** 2020

## Starting

To follow this tutorial you will need:

- **Hardware:** PS3 Fat, USB Flash Drive
- **Software:** A Linux distribution, we will be using Ubuntu

## Motivation

Many people tend to buy new gaming consoles in their launch, meanig a large number of obsolete consoles are left unused the objective of this tutorial is to repurpose these old pieces of hardware by installing GNU/Linux enabliing them to be used for a vast number of applications.

----------------------------------------------

## Linux on the PS3
contar da historia de que anstes dava pra instalar e tal



## Setting Up the PS3 and Booting from a Live Image
falar basicamente do tutorial do cara

###

###



## Using bootloader for Cross-Compilation

Buildroot is a set of Makefiles and patches that simplifies and automates the process of building a complete and bootable Linux environment for an embedded system, while using cross-compilation to allow building for multiple target platforms on a single Linux-based development system. Buildroot can automatically build the required cross-compilation toolchain, create a root file system, compile a Linux kernel image, and generate a boot loader for the targeted embedded system, or it can perform any independent combination of these steps. For example, an already installed cross-compilation toolchain can be used independently, while Buildroot only creates the root file system.

This means we can create compile a Linux enviroment that will run on the PS3 from our Desktop, this is great because now we don't need to rely on whatever packages, applications and configurations the pre-compiled distribution comes with.


We will be using the [petitboot--buildroot](https://github.com/glevand/petitboot--buildroot) project wich is basically buildroot with updates to generate a bootable *petitboot* image. This is because the bootloader, wich is a progtam that loads the operating system into the working memory of a computer on start-up, is called petitboot and is not availabe on the original buildroot

    $ git clone https://github.com/glevand/petitboot--buildroot.git
    $ cd petitboot--buildroot



----------------------------------------------

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
