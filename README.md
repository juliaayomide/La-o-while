<h1>📌 O que é o laço while?</h1>

<p>
O laço <strong>while</strong> é uma estrutura de repetição utilizada na programação
para executar um bloco de código enquanto uma condição for verdadeira.
</p>

<p>
Ou seja, antes de cada repetição, a condição é verificada. Se ela for verdadeira,
o código continua sendo executado; se for falsa, o laço é encerrado.
</p>

<h1>🧠 Como funciona?</h1>

<p>O <strong>while</strong> segue uma lógica simples:</p>

<p>
• Verifica a condição <br>
• Se a condição for verdadeira, executa o bloco de código <br>
• Repete o processo até que a condição se torne falsa
</p>

<p>
Por isso, é muito importante que a condição mude em algum momento,
evitando loops infinitos.
</p>

<h1>💻 Exemplo simples</h1>

<pre>
int contador = 1;

while (contador &lt;= 5) {
    System.out.println(contador);
    contador++;
}
</pre>

<p>🔎 Nesse exemplo:</p>

<p>
• O código imprime números de 1 a 5 <br>
• A variável <strong>contador</strong> é incrementada a cada repetição <br>
• Quando contador passa de 5, a condição deixa de ser verdadeira e o laço termina
</p>

<h1>✅ Quando usar o while?</h1>

<p>O <strong>while</strong> é ideal quando:</p>

<p>
• Não sabemos exatamente quantas vezes o código deve se repetir <br>
• A repetição depende de uma condição dinâmica <br>
• Queremos testar a condição antes de executar o código
</p>
