<body>

<h1>Documentação dos Endpoints</h1>

<p>Aqui estão os endpoints disponíveis nesta API:</p>

<h2>GET /pagamentos</h2>
<p>Retorna uma lista paginada de todos os pagamentos.</p>
<p>Parâmetros de consulta:</p>
<ul>
  <li><strong>page</strong> (opcional): Número da página (padrão 0).</li>
  <li><strong>size</strong> (opcional): Tamanho da página (padrão 10).</li>
</ul>

<h2>GET /pagamentos/{id}</h2>
<p>Retorna os detalhes de um pagamento específico.</p>
<p>Parâmetros de URL:</p>
<ul>
  <li><strong>id</strong>: ID do pagamento a ser detalhado.</li>
</ul>

<h2>POST /pagamentos</h2>
<p>Cria um novo pagamento.</p>
<p>Corpo da requisição (JSON):</p>
<pre>
{
  "atributo1": "valor1",
  "atributo2": "valor2",
  ...
}
</pre>

<h2>PUT /pagamentos/{id}</h2>
<p>Atualiza os detalhes de um pagamento existente.</p>
<p>Parâmetros de URL:</p>
<ul>
  <li><strong>id</strong>: ID do pagamento a ser atualizado.</li>
</ul>
<p>Corpo da requisição (JSON):</p>
<pre>
{
  "atributo1": "novo_valor1",
  "atributo2": "novo_valor2",
  ...
}
</pre>

<h2>DELETE /pagamentos/{id}</h2>
<p>Remove um pagamento existente.</p>
<p>Parâmetros de URL:</p>
<ul>
  <li><strong>id</strong>: ID do pagamento a ser removido.</li>
</ul>

</body>
