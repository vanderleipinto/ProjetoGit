Olá, esse projeto ensina você a usar o git

git init na pasta principal

Esse repositório começa sem commit.

git add
Manda os arquivos para a área de standing, preparados para serem commitados

git status
Observa quais mudanças estão prontas para serem commitadas.

git commit -m "Mensagem do commit"
Faz o commit para o repositório.

(A branch principal está sendo mudada de master para main)
o comando para fazer essa mudança é:
git branch -M "main"

---

Porque precisamos criar um repositório no GitHub se já criamos um na nossa máquina?
-> Justamente porque tudo que tem no repositório na nossa máquina vá para o Git também.

Depois de criar o repositório no github e pegar o endereço, faremos o git remote para termos acesso a ele

git remote add origin https://github.com/vanderleipinto/ProjetoGit.git

Nenhuma mensagem vai aparecer.

Agora vamos enviar o nosso repositório para o repositório remoto.

git push -U origin main
