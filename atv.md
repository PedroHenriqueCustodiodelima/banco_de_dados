# Comentario
|Campos | | | | |
|:-------|:------- | :------- | :------- | :------- |
|  **Nome**  | **Descrição** |  **Tipo de dado**  | **Tamanho** |  **Restrições de integridade**  |
| id | Cógido de identificação da tabela | int |  | PK |
| texto | Um conjunto de caráteres | Varchar | 100 | Not Null |
| data_hora | hora que o comentario foi adicionado | Varchar | 5 | Not null |
| nome_id_usuario | De quem pertence o comentario | Varchar | ? | FK |
| id_post | Id do post que foi selecionado | ? | ? | Fk |

|Restrição de Integridade (Tabela)| |
|:-------|:------- |
|  **Nome**  | **Descrição** |
|||
|||
|||
