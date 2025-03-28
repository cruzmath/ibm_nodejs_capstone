1. Mostrar todas as bases de dados:
    * show databases
2. Usar uma base de dados específica:
    * use [database_name]
3. Contar quantos documentos tem na coleção dentro da base de dados atuais:
    * db.<collection_name>.countDocuments({})
4. Encontrar um documento específico com base no id:
    * db.<collection_name>.findOne({ id: "429" })
