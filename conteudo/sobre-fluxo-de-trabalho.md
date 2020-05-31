[<- Início](../README.md)

# Fluxo de trabalho

## Índice
- [Configurações de autoria no git](#configurações-de-autoria-no-git)
- [Rastreando seu projeto localmente e subindo para o github](#rastreando-seu-projeto-localmente-e-subindo-para-o-github)
- [Clonando projetos](#clonando-projetos)
- [Contribuindo com um projeto](#contribuindo-com-um-projeto)
- [Puxando mudanças do remoto](#puxando-mudanças-do-remoto)

### Extra
- [Configurações Mac](configuracoes-mac.md)

-----------
Aqui aprenderemos os passos para tornar nossos projetos versionáveis pelo git e como hospedá-los com outras pessoas pelo github.


## Configurações de autoria no git
Agora que aprendemos sobre linha de comando no terminal, podemos utilizar a linha de comando do git, e o ideal é começarmos pelas configurações de autoria:
- Comando para dizer qual seu nome:
    - `git config --global user.name "Seu nome"`
- Comando para dizer qual seu email:
    - `git config --global user.email "seu@email.com"`
- Comando de verificação se a configuração foi realizada com sucesso:
    - `git config --list`
- Comando para remover suas informações:
    - `git config --global --unset user.name "Seu nome"`
    - `git config --global --unset user.email "seu@email.com"`

Agora é sua vez, [exercício para configuração de autoria](exercicios/2-exercicio-git-config.md)

### Rastreando seu projeto localmente e subindo para o github

[Para esse módulo seguiremos o material da on3-git sobre iniciando o git](exercicios/3-exercicio-local-remoto.md)

### Clonando projetos

[Para esse módulo seguiremos o material da on3-git sobre clone](exercicios/4-exercicio-clone.md)

### Contribuindo com um projeto

[Para esse módulo seguiremos o material da on3-git sobre contribuição](exercicios/5-exercicio-contribuição/README.md)

### Puxando mudanças do remoto

[Para esse módulo seguiremos o material da on3-git sobre clone](exercicios/6-exercicio-pull.md)



[<- Sobre github](sobre-github.md) | [Exercício para entrega ->](exercicios/7-exercicio-projeto-casa/README.md)
