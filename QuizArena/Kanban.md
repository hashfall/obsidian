---

kanban-plugin: board

---

## Versão 2.0

- [ ] Implementar um **Analizador de respostas por IA**.
	
	O firestore será restruturado para ter todas as alternativas removidas da base e ele passará a armazenar somente as Questões. 
	
	Quando o player enviar um resposta, esta será avaliada por uma IA que retornará true ou false para o servidor, caso true, serão gravados os pontos do player e a string da resposta que ele deu (para que possamos comparar a raridade de respostas entre players para o cálculo diário de pontuação).
	#firebase #backend #script-diário


## Desejável

- [ ] Adicionar um filtro de **profanidade** para nicknames.
	
	#firebase #backend


## Importante

- [ ] **Tempo limite** de **60s** para responder cada questão.
	#frontend
- [ ] Gravar no firebase a quantidade de tempo que sobrou após responder uma questão. Se o usuário tiver 45s restantes no timer, estes 45s serão armazenados no bd.
- [ ] Sistema de **bonús de pontos** baseado no tempo restante de resposta. 
	Pontos * T_Restante.
	#firebase #script-diário


## Urgente

- [ ] Implementar uma **interface de Admin** segura, com login e senha via OAuth.
	#frontend #backend #auth
- [ ] Adicionar na interface de Admin um sistema para **curadoria e correção de questões** (ajuste manual nas questões e alternativas já armazenadas no firestore)
	#frontend #backend #firebase
- [ ] Adicionar na interface de Admin um sistema para **carregar novas questões** a partir de um arquivo csv ou xls, seguindo todos os padrões atuais.
	#frontend #backend #firebase


## Doing



## Testing



## Implemented





%% kanban:settings
```
{"kanban-plugin":"board","list-collapse":[false,false,false,false,false,false,false],"show-checkboxes":true,"new-line-trigger":"shift-enter"}
```
%%