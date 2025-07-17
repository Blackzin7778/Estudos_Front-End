---
tags: inbox
created: 2025-07-15 07:35
---

# Nota Rápida

Referência: https://www.youtube.com/watch?v=nlO5hySqJFA&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=7

# Representação de Dados


> [!NOTE] Frase destaque
> O computador é um burro muito rápido
>

## Como  o computador vê os dados ?

O computador não é inteligente nós programadores que concedemos a inteligência ao computador , assim como todo equipamento eletrônico o computador funciona através de sinais como 0 e 1, mas na verdade não são vários 0 e 1 que são representados como onda quadrada sinais elétricos com e sem sinal sendo 0 = Sem sinal e 1 = Com sinal.

### O que é bit e byte ?

O conjunto de 0s e 1s que são digitos binários(bit = Binary digit ) como o 0 e 1 não dá para representar muita coisa, e por isso a tecnologia e computação reúne um conjunto de 8 bits
que recebe o nome de byte.
  
> [!NOTE] Representação de um Byte
> 01000001 = A

A sequência de bits acima é o que representa a letra A, mas o que exatamente vai para a memória do computador é exatamente essa sequência, e para saber sobre a tabela inteira basta apenas procurar na tabela de representação ==UTF-8== o código multibyte usa de 1 a 4 bytes para representar letras, caracteres acentuados e emojis, e como dito anteriormente o computador irá entender como vários 0 e 1 mas na verdade ele enxerga esta onda quadrada abaixo:
![[Pasted image 20250715103127.png]]

###  Os múltiplos do byte

Na computação possuímos os múltiplos dos bytes sempre representados dessa forma abaixo:


| Representação dos Dados | Resultado |
| ----------------------- | --------- |
| 1024 Bytes              | 1KB       |
| 1024 KB                 | 1 MB      |
| 1024 MB                 | 1 GB      |
| 1024 GB                 | 1 TB      |
| 1024 TB                 | 1 PB      |
| 1024 PB                 | 1 EB      |
| 1024 EB                 | 1 ZB      |
| 1024 ZB                 | 1 YB      |
A diferenças entre representações como exemplo MB

> [!NOTE] Diferenças entre representações
> MB = Megabytes é usado mais para armazenamento
> Mb = Megabits é usado para transmissão

## Como nos conectamos a Internet ?

Nós quando estamos acessando a internet chamamos nosso dispositivo de cliente, e porque cliente? chamamos de cliente pois estamos fazendo o uso de um serviço no caso queremos navegar na internet, acessar um vídeo ou até mesmo baixar uma imagem então somos um cliente e todos estas opções que queremos acessar está na internet, como dito anteriormente a internet é uma rede mundial distribuída por todo o território do planeta, geralmente na nossa casa para termos acesso precisamos instalar um aparelho quando fazemos uma assinatura de plano de internet, vão e instalam um aparelho que geralmente está ligado a rede telefônica ou no nosso sistema de cabeamento da televisão, se estamos utilizando um celular, o nosso celular tem que se conectar sem fio nesse aparelho ou se estamos na rua o dispositivo se encontra dentro do nosso celular e se conecta a uma antena mas o princípio é o mesmo e este dispositivo que é instalado na nossa casa esse conjunto é necessário para que tenhamos acesso a internet, mas ai temos um problema o computador como exemplo sendo o cliente nós temos o computador que entende o sinal como ondas quadradas, e precisamos mandar um sinal ou pela linha telefônica, esses sistemas como exemplo o telefone aceitam essa onda senoidal 
Ex:
![[Pasted image 20250715111342.png]]

## O que é um Modem?

Então possuímos um tipo de onda que o computador entende e o telefone não entende, e um tipo de onda que o telefone entende e um computador não entende, e é por isso que necessitamos deste aparelho em casa, esse aparelho tem a função de transformar essa onda quadrada em senoidal e que chamamos de ==mo==dulação e também tem que fazer ao contrário quando os dados chegarem na nossa casa transformar de onda senoidal e ondas quadradas que chamamos de ==dem==odulação.

![[Pasted image 20250715111834.png]]

Dando uma verificada somente nas letras destacadas em amarelo é o nome do aparelho, ou seja o modem é nada mais do que um aparelho que faz a modulação (modulation) e demodulação(demodulation) é exatamente para isso que serve este aparelho que possuímos em casa é um modem , esse aparelho além de possuir um modem ele possui um roteador bem simples, um switch esse aparelho é o que chamamos de gateway.

## Como chegamos no servidor?

Por exemplo quando digitamos www.instagram.com quero acessar o instagram onde está o instagram? temos costume de dizer que estão na nuvem de forma simples, de maneira mais técnica o instagram é um conjunto de arquivos, esses arquivos se encontram nos servidores e assim como toda máquina na internet os servidores recebem uma numeração própria como exemplo:

> [!NOTE] Servidor Instagram
> 157.240.22.174

Imagine que toda vez que fossemos acessar o instagram precisasse digitar o endereço IP 157.240.22.174, seria complicado de gerenciar, decorar sem contar seria necessário anunciar toda vez que trocasse o endereço IP, como exemplo para não decorarmos o número geralmente salvamos o contato com o nome da pessoa, quando precisamos ligar para alguém não procuramos pelo número e sim pelo nome, assim com o telefone a internet também possuí uma agenda eletrônica.

### O que são os servidores DNS?

A sigla DNS significa: 

> [!NOTE] Significado Sigla DNS
> Domain System Name = Sistema de nome de domínio

então sistema de nome de domínio é um local na internet ou lugares especiais na internet que podemos questionar, como exemplo quando digitamos Instagram.com não vai diretamente pro servidor, ele vai diretamente para o servidor DNS onde é requisitado o endereço , onde o DNS procura pelo IP do site e retorna para o cliente assim concedendo o acesso ao servidor.

## Passo a Passo do funcionamento da internet

O instagram por exemplo possuí imagens, essa imagem é transmitida para o dispositivo cliente, a imagem é quebrada em vários pacotes de dados que são enviados em caminhos, tempos e rotas diferentes

### Entendendo as rotas da Internet

A internet funciona muito baseado em rotas porque é uma rede finita com caminhos finitos, por exemplo quando tem uma rota congestionada, muita gente solicitando ou parou de funcionar o sistema de roteamento da internet tem equipamentos específicos que desviam a rota tipo waze quando te joga para outro caminho quando uma rua está engarrafada e ele te joga para outro caminho, então podemos fazer com que o roteamento siga caminhos diferentes, e o caminho quando quebramos a imagem cada pacote de dados faz caminhos diferentes, como por exemplo quando um site demora para carregar e quando pesquisamos novamente e vai mais rápido não significa que os dados estavam no meio do caminho e chegaram depois, mas sim que sua solicitação foi executada por outra rota.

---

## Contexto

Compreender e entender como funciona a internet de forma geral e intuitiva

---

✅ Processado → Criado
## Próximos passos

- [ ] Revisar e processar
