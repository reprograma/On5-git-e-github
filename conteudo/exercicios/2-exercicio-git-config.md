[<- Início](../../README.md)

# Exercício configuração de autoria no git

### Configurando o Git com seu user.name e user.email

Esse exercício foi copiado da [Turma Online 3](https://github.com/reprograma/On3-git-e-github/tree/master/2-exercicio-git-config)

Com essa apresentação: <a href="https://docs.google.com/presentation/d/1hX8i7HX2BrT1mN_Yphy6ZWjt4NT4qEwomhpSpDoyBr0/edit?usp=sharing" target="_blank">(on3-git-bash)</a>

Você deve ter instalado o Git na sua máquina.
Na Área de Trabalho (Desktop), clique com o botão direito e selecione ***Git Bash here***

<img src="imgs/git/bash-here.png" alt="Logo do git" />

- Comando para dizer qual seu nome:
    - `git config --global user.name "Seu nome"`
- Comando para dizer qual seu email:
    - `git config --global user.email "seu@email.com"`
- Comando de verificação se a configuração foi realizada com sucesso:
    - `git config --list`
- Comando para remover suas informações:
    - `git config --global --unset user.name "Seu nome"`
    - `git config --global --unset user.email "seu@email.com"`

Agora é sua vez:

Comandos para configurar seu usuário no Git:
- `git config --global user.name "Lydia Rodrigues"`
- `git config --global user.email "mlydia295@gmail.com"`

Para verificar se foi configurado:
- `git config --list`

Para remover usuário:
- `git config --global --unset user.name "Lydia Rodrigues"`
- `git config --global --unset user.email "mlydia295@gmail.com"`


[<- Voltar para fluxo de trabalho](../sobre-fluxo-de-trabalho.md)
