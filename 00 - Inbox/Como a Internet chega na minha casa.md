---
tags:
  - diário
created: 2025-06-12 14:50
status: Revisando
date: <% tp.date.now("YYYY-MM-DD") %>
---
# Nota Rápida

Referência: https://www.youtube.com/watch?v=F74GKCLXUWM&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=6

A internet surgiu no período da Guerra fria, surgiu para cumprir objetivos na guerra, em uma disputa travada entre o Estados Unidos e União soviética, com o surgimento do **Sputnik** o primeiro satélite artificial lançado pela união soviética que apenas tinha como função de contornar a terra e emitir bips para que a união soviética pudesse captar estes bips, então **Dwight D. Eisenhower** com medo da evolução tecnológica da união soviética decidiu criar uma organização para estudar tecnologias para guerra. A **Darpa** existente até hoje, que surgiu como forma de "Backup" de dados assim surgindo a primeira rede a **Arpanet** em 1969 que tinha como base apenas 4 computadores na época :

> [!NOTE] Computadores
> SDS Sigma 
> IBM 370/375
> DEC PDP-10
> SDS 90

Computadores diferentes , se comunicavam cada um de uma forma individual , então havia o grande problema que era impossível desses computadores conversarem entre si.

# Como os computadores se Comunicavam na época?

Com o surgimento do primeiro protocolo o **NCP** que basicamente unificava as linguagens diferentes dos computadores em apenas uma , mas como era algo muito simples e primordial tinha problemas como ser necessário interromper a transmissão para que apenas 2 computadores comunicassem entre si, porém a rede com o passar do tempo cresceu e se tornou impossível manter o uso do protocolo então surgiu um versionamento diferente de protocolo o **TCP** criado por **Bob Kahn** porém havia um pequeno problema como estava muito grande o protocolo não conseguia distinguir as máquinas e pontos de comunicação, então **Vint Cerf** Criou o protocolo **IP** que tinha como objetivo criar a identificação de máquinas então os protocolos foram agrupados assim surgindo a criação do **TCP/IP** , com esse grande avanço em 1977 a rede cresceu mais ainda e assim ocorreu a primeira comunicação via satélite entre continentes.

## Crescimento da rede e versionamentos surgindo

Com a crescimento constante da rede, decidiram separar a rede em três partes sendo a **MilNet** para uso militares, **NSFNET** para uso científico, **Comerciais**, todas as redes com a exceção da **MILNET** haviam necessidade de se comunicarem entre si então surgiu a ideia de criar uma rede de interconexão entre eles que surgiu o nome de **Interconnect Networking** que foi cunhado por **Robert Kane** que de forma abreviada ficava **InternetWorking** que posteriormente foi mais simplificada e então surgiu o tão conhecido nome/termo isolado **Internet*** .

## Internet por baixo da água

Acesse o site: https://www.submarinecablemap.com/
para poder entender como funciona a comunicação mundial

Praticamente todos os continentes hoje em dia estão interconectados entre si em uma rede gigante que chamamos de **Internet**, que são transmitido entre sinais de satélites, balões de comunicação, transmissões via antenas para uso de rede celular.

## Como funciona a comunicação entre pontos


![[brave_screenshot_www.youtube.com.png]]

Imagine que o computador da sua casa seja o ponto A e o Servidor seja o Ponto B, vamos supor que o ponto A solicite uma imagem então o servidor ponto B possui o arquivo da foto. O que o ponto A irá fazer será solicitar a foto para o ponto B, se for enviada a imagem inteira, uma imagem grande pode causar uma lentidão na internet mundial assim entra em ação o Protocolo **TCP/IP** que irá quebrar esse arquivos em vários pacotes de dados, que será enviado totalmente fora de ordem, em tempos diferentes e por rotas diferente e caso seja perdido o servidor reenvia, mas o fato que no fim da transmissão todos os pacotes estarão no ponto A, quando acessamos a internet ou estamos acessando um site e a imagem é pesada e estamos com a conexão lenta é possível vermos a imagem se montando.

## Como era a internet  antigamente ?

A internet antigamente não possuia nada gráfico muito menos visual, era somente uma tela preta com letras em verdes, o protocolo básico de navegação de contéudo que se havia na época era chamado **gopher** não havia mouse, muito menos cursor, se usava as teclas do teclado para navegar e acessar os sites, já havia possibilidade de baixar imagens na época mais era necessário abrir em uma interface gráfica local, pois não haviam imagens indexadas na tela como hoje em dia.

# Surgimento da WWW

Em 1993 o inglês **Tim Berners-Lee** estava participando de um projeto tipo o gopher que eram textos que possuiam áreas sensíveis que podiam ser acessadas atráves de links ou hyper links, que evoluiu e posteriormente se chamaria como conhecemos hoje o protocolo **HTTP** além do HTTP Tim Berners-Lee Criou o **HTML** que é uma linguagem de marcação para hyper textos, que é a internet que conhecemos hoje que também possuí outro nome **World Wide Web** e para a **WWW** funcionar era necessário um navegador então surgiu o primeiro navegador compátivel com HTTP o **Mosaic** criado por **Marc Andreessen** então com este cconjunto a WWW se tornou realidade.

## A Diferença entre World Wide Web e Internet

A internet é um termo mais amplo é a rede mundial, e dentro da internet possuímos diversos servidores especializados em determinado tipo de serviço ou protocolo, como o **FTP** que é especializado em transferência de arquivos, já a World Wide Web é uma subrede da internet, é uma parte da internet que é especializada em HTTP então toda vez que falamos sobre WWW é uma rede que está dentro da grande rede internet.

---

## Contexto

Aprender como funciona a internet e conceitos básicos para compreender como funciona a internet e assim ter uma base para criação de páginas web

---
Creditos
Felipe Dev: https://github.com/Blackzin7778

✅ Processado → Criado [[Zettel - Sputnik e a Infraestrutura da Internet]]
✅ Processado → Criado [[Zettel - Dwight D. Eisenhower, seu legado e perfil executivo]]
✅ Processado → Criado [[Zettel - Darpa e sua contribuição histórica]]
✅ Processado → Criado [[Zettel - NCP - Networking control protocol]]
✅ Processado → Criado [[Zettel - Protocolo TCP-IP e seu funcionamento]]


## Próximos passos

- [x] Revisar e processar
