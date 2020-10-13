# <p align=center>Back-end e regras de negócio do projeto</p>

### Comandos

**Execução do servidor**

```bash
yarn start
```

**Criação de migrations**
Após devidamente configurado o typeorm utiliza-se o comando
```bash
yarn typeorm migration:create -n create_nome_da_table
```
Onde -n é o parâmetro para o nome.
