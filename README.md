## Bloco 29: Introdução ao MongoDB

### 29-1: MongoDB- Introdução :heavy_check_mark:

- Databases, collections e documents
- MongoDB com Docker
- Método insert
- Método find
- Tipos e comparadores
- Limitando e pulando retornos

### 29-2: Filter Operators :heavy_check_mark:

- Operadores de comparação ($lt, $lte, $gt, $gte, $in...)
- Operadores lógicos ($not, $and, $or...)
- Operador $exists
- Métodos sort e pretty
- Removendo documentos com deleteOne e deleteMany

### 29-3: Operadores de consulta :heavy_check_mark:

- Operador $all (para buscar valores independentemente da existência de outros valores ou a ordem que estejam)
- Operador $elemMatch (seleciona os documentos que contêm um campo do tipo array com pelo menos um elemento que satisfaça todos os critérios de seleção especificados)
- Operador $size (seleciona documentos em que um array contenha um número de elementos especificado)
- Operador $expr (permite que você utilize expressões de agregação e construa queries que comparem campos no mesmo documento)
- Operador $regex (expressão regular no MongoDB)
- Operador $mod (operação matemática módulo: 2/2 = 0)

### 29-4: Updates simples :heavy_check_mark:

- Método updateOne
- Método updateMany
- Operador $set (altera o valor de um campo específico)
- Operador $mul
- Operador $inc
- Operadores $min e $max
- Operador $currentDate
- Operador $rename e $unset

### 29-5: Updates Complexos :heavy_check_mark:

- Operador $push (inserir dados num array)
- Operador $pull (remover dados do array)
- Operador $pop (remover dados pelo indice ou local)
- Add to set e array filters
