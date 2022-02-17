# Debugging and Error Handling
Challenge from the course "Debugging and Error Handling" from the Banco Inter's Bootcamp

------

### Atividade: validação de erros por tipo

- O objetivo é que a função receba um array e retorne ele caso o seu tamanho corresponda ao número enviado como parâmetro na função. Caso contrário, um erro será lançado.

Crie uma função que recebe um array e um número</br>
Realize as seguintes validações:

- Se os parâmetros não forem enviados, lance um erro do tipo ReferenceError
- Se o array não for do tipo 'object', lance um erro do tipo TypeError
- Se o número não for do tipo 'number', lance um erro do tipo TypeError
- Se o tamanho do array for diferente do número enviado como parâmetro, lance um erro do tipo RangeError

Utilize a declaração try...catch</br>
Filtre as chamadas de catch por cada tipo de erro utilizando o operador instanceof
