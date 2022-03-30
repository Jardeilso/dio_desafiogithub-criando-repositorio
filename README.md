 dio_desafiogithub-criando-repositorio
Desafio de projeto sobre github
nivel_acesso=input('Digite o nivel de acesso:').upper()
genero=input('Qual o seu genero?').upper()
 Genero Masculino
if nivel_acesso=='ADM' and genero=='MASCULINO':
    print('Olá Administrador')
elif nivel_acesso=='USR' and genero=='MASCULINO':
    print('Olá usuario')
elif nivel_acesso=='GUEST' and genero=='MASCULINO':
    print('Olá visitante')
 Genero Feminino
if nivel_acesso=='ADM' and genero=='FEMININO':
    print('Olá Administradora')
elif nivel_acesso=='USR' and genero=='FEMININO':
    print('Olá Usúaria')
    if nivel_acesso=='GUEST' and genero=='FEMININO':
        print('Olá Visitante')
else:
    print('Olá desconhecido (a).')
