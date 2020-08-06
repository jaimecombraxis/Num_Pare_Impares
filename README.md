# Num_Pare_Impares
n = 1
par = 0
impar = 0
imparn = 0
parn = 0
while n != 0:
    n = int(input('\033[1;34mDigite um valor: '))
    if n != 0:
        if n % 2 == 0:
            par += 1
            parn = parn + n
        else:
            impar += 1
            imparn = imparn + n
print('\033[1;30mVocê digitou \033[1;31m{} \033[1;30mnumeros pares e '
      '\033[1;31m{}\033[1;30m numeros ímpares!'.format(par, impar))
print('\033[1;30mSendo a soma dos numeros Pares valor \033[1;31m{} '
      '\033[1;30me a soma dos numeros Impares valor \033[1;31m{}\033[m '.format(parn,imparn))
