# Amizade
|Campos | | | | |
|:-------|:------- | :------- | :------- | :------- |
|  **Nome**  | **Descrição** |  **Tipo de dado**  | **Tamanho** |  **Restrições de integridade**  |
| id | Cógido de identificação da tabela | int |  | PK |
| nome_id_usuario_1 | identificador do nome | int |  | FK |
| nome_id_usuario_2 | identificador do nome | int |  | FK |

# Denuncia
|Campos | | | | |
|:-------|:------- | :------- | :------- | :------- |
|  **Nome**  | **Descrição** |  **Tipo de dado**  | **Tamanho** |  **Restrições de integridade**  |
| id_denuncia | identificador virtual numerico | int | | PK |
| tipo | Explicita se a postagem é do tipo texto ou midiatica | Booleano | |  Padrão |
| data_hora |  data e hora que o usuario criou o post | DataType | | PK |
| descricao | uma descrição qualquer escrita pelo usuario | Varchar | 100 | Nulo |
| nome_usuario_id | identificador do nome | int |  | FK |
| id_post | Chave estranjeira da tabela Post | int | |  FK/PK |

# Mensagem
|Campos | | | | |
|:-------|:------- | :------- | :------- | :------- |
|  **Nome**  | **Descrição** |  **Tipo de dado**  | **Tamanho** |  **Restrições de integridade**  |
| id_msg | identificador virtual numerico | int | | PK |
| data_hora |  data e hora que o usuario criou o post | DataType | | PK |
| nome_usuario_id | identificador do nome | int |  | FK |
| id_grupo | Chave estranjeira da tabela grupo | int | |  FK/PK |

# Moderador
|Campos | | | | |
|:-------|:------- | :------- | :------- | :------- |
|  **Nome**  | **Descrição** |  **Tipo de dado**  | **Tamanho** |  **Restrições de integridade**  |
| id | Cógido de identificação da tabela | int |  | PK |
| senha | uma senha qualquer criada pelo o moderador | Varchar | 8 | Nulo |
