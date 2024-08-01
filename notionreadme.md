O Git é uma ferramenta poderosa para controle de versão e colaboração em projetos de desenvolvimento de software. Vou apresentar alguns dos principais comandos e explicar o que cada um faz:

git init: Esse comando é utilizado para criar um novo repositório Git. Ele cria um repositório vazio no diretório atual, permitindo que você armazene seu código-fonte, faça alterações e salve essas mudanças.
git clone: Quando você precisa obter uma cópia exata de um repositório já existente, o git clone é o seu amigo. Ele cria uma cópia local do repositório remoto, incluindo todo o histórico de commits e arquivos.
git add: O git add adiciona arquivos ao “staging area”, preparando-os para o próximo commit. Você pode usar diferentes sintaxes:
git add seu_arquivo (adiciona um arquivo específico ao repositório)
git add * (adiciona todos os arquivos modificados e/ou novos)
git commit: Este é o momento em que você salva suas mudanças no repositório local. Cada commit cria um novo ponto na história do projeto. Lembre-se de incluir uma mensagem descritiva para que outros desenvolvedores entendam o que foi feito.
git pull: Atualiza o repositório local com as últimas alterações do repositório remoto. É útil quando você quer sincronizar seu código com o que está acontecendo no projeto.
git push: Envia as alterações locais para o repositório remoto. Isso é essencial para compartilhar seu trabalho com outros colaboradores. Lembrando que na primeira vez é necessário digitar>  git push -u origin main */ou seja, informar a origem e o destino/*
git branch: Lista, cria ou deleta ramificações (branches) no repositório. Branches permitem que você trabalhe em diferentes recursos ou correções simultaneamente.*/basta digitar git branch -M main <o novo nome>/*
git log: Mostra o histórico de commits do repositório. É útil para entender quem fez o quê e quando.
git log --pretty=oneline : mostra o histórico de comits do repositório em uma linha.
