# Self attedance auto marker
**Pt-Br:**  
Ao adicionar o bloco HTML contendo todo código de [`attendance-mod-block.html`](https://github.com/LucasVerdade/moodle-custom-blocks/blob/main/attendance-mod/attendance-mod-block.html) você verá algo como a imagem abaixo.   
![Bloco de marcação automática de presenças](https://github.com/LucasVerdade/moodle-custom-blocks/blob/main/docs/attendance-mod/attendance-mod-block-img.png?raw=true)  
  
## Objetivo
Esse bloco procura todas as listas de presença em todas matérias do seu último semestre. 
Caso encontre alguma presença disponível para auto anotar ele acessa a página desta presença e marca a primeira opção.  
O bloco mostra uma lista das presenças encontradas e o status dela no momento. Nessa lista, haverá o código da máteria, que também é um link para a lista de presença da mesma, e o status.  
Caso não há nada para marcar então exibirá  _"There is no attendance"_.  
Caso encontre e marque a presença então exibirá _" Marked '\<option\>' "_.  
Veja um exemplo abaixo, em que não há presenças para marcar.  
![Exemplo da lista do bloco](https://github.com/LucasVerdade/moodle-custom-blocks/blob/main/docs/attendance-mod/attendance-mod-list-example.png?raw=true)  

# Uso
O botão **"Check"** dentro permite você rodar a verificação sem precisar recarregar a página.  
O botão ao lado, que pode estar como **"Manual"** ou **"Auto"**, exibe em qual modo o bloco está. Por padrão o bloco vem como _"Manual"_, isto é, ele não irá executar ao entrar na página inicial do moodle.  
Já o modo "Auto" permite que o bloco execute assim que a página inicial do moodle é carregada.  
Para alterar entre os modos basta clicar no botão até que esteja exibindo a opçao desejada.  
Independente do modo que está configurado, é possível usar o botão _"Check"_ quando quiser.  

Essa configuração fica salva em seu navegador.

---
### Features em desenvolvimento:
- Campo para escolher qual opção de presença quer que o bloco marque sempre naquela máteria;
- Ignorar matérias específicas;

