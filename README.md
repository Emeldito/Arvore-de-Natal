# Arvore-de-Natal
 Árvore de Natal feito com HTML, CSS e jQuery-fireworks, este projecto foi usado numa loja virtual (tech4u.co.mz) passagem do natal 2021-2022.

 # jQuery-fireworks
É um plugin jQuery simples e fácil de usar, totalmente configurável, usado para criar animações realistas de fogos de artifício com efeitos sonoros de explosão para celebrações. O Neste projecto, o plugin jQuery coloca fogos de artifício deslumbrantes em uma div, conforme ilustra a imagem:

![image](https://user-images.githubusercontent.com/50636981/186983884-2a52ec5a-6b57-4dfb-b81c-596234694677.png)

# Usage
$('#divElement').fireworks();

Existem parâmetros opcionais também como:
$('#divElement').fireworks({
    sound: true,
    opacity: 0.4,
    width: '400',
    height: '300'
}); 

Como aplicar efeitos de animação de fogos de artifício jQuery usando fireworks js?

# Passo 1
Baixe o plugin jQuery [aqui](https://www.jqueryscript.net/animation/Realistic-Fireworks-Animations-Using-jQuery-And-Canvas-fireworks-js.html) e depois coloque o script jquery.fireworks.js depois da biblioteca jQuery. Confira abaixo:

![image](https://user-images.githubusercontent.com/50636981/186985417-e5f20bc9-6b6c-4e3b-9987-73afe41ef10c.png)


# Passo 2
Depois de vincular os arquivos necessários, crie um elemento onde você deseja que as animações de fogos de artifício sejam colocadas. Neste projecto eu usei uma div com a classe estrela.

O h1 junto com img eu usei uma dica extra. Tornando-o opcional.

![image](https://user-images.githubusercontent.com/50636981/187048132-59936f94-84ac-41c3-9bb2-d56b17a03b98.png)



# Passo 3
Crie um Arry que vai retornar uma arvore conforme mostrado abaixo:
![image](https://user-images.githubusercontent.com/50636981/187048440-cec6dded-647e-4021-a935-d339fb1a2a9c.png)

# Passo 4
Por fim, inicialize o plugin chamando a função fireworks conforme mostrado abaixo: