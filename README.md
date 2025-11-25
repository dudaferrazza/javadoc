# Documentação Javadoc

Este é um projeto Java simples que demonstra como usar a ferramenta Javadoc para documentar código. Ele contém duas classes: `Produto` e `Carrinho`. A documentação Javadoc é essencialmente a documentação oficial da API do seu código.

---

## Estrutura do Projeto

O código-fonte está organizado no pacote `com.aula`:

* `com.aula.Produto`: Uma classe que representa um item para compra, com funcionalidades para calcular descontos e impostos.
* `com.aula.Carrinho`: Uma classe simples que representa o carrinho de compras e possui um método para calcular o total de um item específico.

---

## Classes Incluídas

As classes incluem diversos exemplos de tags Javadoc comuns e úteis:

### Comentários de Classe e Autor
* `@author` e `@version` na classe `Produto`.

### Comentários de Método
* `@param` e `@return` para descrever parâmetros e o valor de retorno, respectivamente.

### Referências Cruzadas
* Uso de `@see` no método `calcularTotal` da classe `Carrinho` para apontar para o método `aplicarDesconto(double)` da classe `Produto`.

### Informações Específicas de Implementação
* Tags como `@apiNote` e `@implSpec` no método `calcularImposto` para fornecer notas sobre o uso e especificações de implementação.

### Métodos Descontinuados
* Uso da tag `@deprecated` no método `descontoAntigo()` para indicar que ele não deve ser mais utilizado, sugerindo o método substituto na descrição.

### Exceções
* Uso de `@throws` no método `aplicarDesconto(double)` para documentar uma exceção que pode ser lançada (`IllegalArgumentException`).
