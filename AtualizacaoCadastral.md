---


---

<p>Serviço responsável por gerar dinamicamente as views e campos do formulário que serão exibidos pelo aplicativo.<br>
Serviço acionado somente para clientes logados, no momento em que o menu “Atualização cadastral” é acionado no aplicativo.</p>
<p><strong>Verbo</strong>: GET<br>
Recurso: api/Beneficiario/<strong>AtualizacaoCadastral</strong></p>
<p>Entrada:</p>

<table>
<thead>
<tr>
<th>Atributo</th>
<th>Tipo de Dados</th>
<th>Descrição</th>
<th>Formato</th>
</tr>
</thead>
<tbody>
<tr>
<td>Result</td>
<td>Inteiro</td>
<td>Atributo responsável por identificar se houve erro ou sucesso no processamento</td>
<td>0 para erro na execução; 1 para sucesso</td>
</tr>
</tbody>
</table>
