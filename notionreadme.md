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

Aula2:
"INFORMAÇÕES RELATIVAS A NOVOS CÓDIGOS GIT"
git commit -am =====> é uma forma conveniente de combinar duas etapas em uma só: adicionar arquivos ao stage e fazer o commit.

git commit -a: O argumento -a (ou --all) diz ao Git para automaticamente adicionar todos os arquivos modificados e rastreados ao stage antes de fazer o commit. Isso significa que ele pega todos os arquivos que estavam no seu último commit e foram modificados desde então. No entanto, ele não adiciona arquivos não rastreados (ou seja, novos arquivos que você ainda não adicionou ao Git).

git commit -m "mensagem": O argumento -m (ou --message) permite que você especifique uma mensagem de commit diretamente na linha de comando. A mensagem deve estar entre aspas duplas. Essa mensagem é uma breve descrição das mudanças que você está comprometendo.

Portanto, quando você usa git commit -am "mensagem", o Git primeiro adiciona automaticamente todos os arquivos modificados e rastreados ao stage (usando o -a). Em seguida, ele faz o commit dessas mudanças com a mensagem especificada (usando o -m). É uma maneira rápida de fazer ambos os passos em uma única linha de comando.

git add .  # Adiciona todos os arquivos modificados e rastreados ao stage
git commit -m "mensagem"  # Faz o commit com a mensagem especificada
