<h1><strong>Hoteis.com</strong></h1>
<h2>Planejamento da avaliação</h2>
<ol>
    <h3><li>Objetivos</li></h3>
    <p>Encontrar falhas de usabilidade.</p>
    <h3><li>Método utilizado</li></h3>
    <p>
      Método de inspeção usando a avaliação heurística.
    </p>
    <h3><li>Escopo da avaliação</li></h3>
    <ol>
      <li>Página inicial do site</li>
      <li>Página de escolha das hospedagens</li>
    </ol>
    <h3><li>Diretrizes escolhidas(heurísticas)</li></h3>
    <ol>
      <li>Visibilidade do estado do sistema</li>
      <li>Projeto estético e minimalista</li>
      <li>Flexibilidade de eficiência de desempenho</li>
      <li>Correspondência entre o sistema e o mundo real</li>
      <li>Controle e liberdade de usuário</li>
      <li>Ajuda e documentação</li>
      <li>Concistência e padronização</li>
      <li>Reconhecimento em vez de memorização</li>
      <li>Prevenção de erros</li>
    </ol>
</ol>
<h2>Problemas encontrados:</h2>
<ol>
    <li><h3>Excesso de informações</h3></li>
    <ul>
      <li>Problema: A página é muito poluída e possui muitas informações desnecessárias</li>
      <li>Local: Página onde é possivel escolher as hospedegens</li>
      <li>Gravidade: Problema grande</li>
      <li>Huerística violada: Projeto estético e minimalista</li>
    </ul>
    <li><h3>Indução do usuário ao erro</h3></li>
    <ul>
      <li>Problema: O usuário pode selecionar uma data anterior ao dia atual</li>
      <li>Local: Assim que entra no site e coloca dos dados da hospedegem</li>
      <li>Gravidade: Problema pequeno</li>
      <li>Huerística violada: Prevenção de erros</li>
    </ul>
    <li><h3>Marcação de data errada</h3></li>
    <ul>
      <li>
        Problema: Não há informações que o site não marca estadias acima de 28
        dias e além disso é possivel marcar acima de 28 dias e só depois o 
        usuário é alertado.
      </li>
      <li>
        Local: Pop-up onde escolhe as datas da estadia na parte do site destinada
        escolha dos dados da estadia.
      </li>
      <li>Gravidade: Problema pequeno</li>
      <li>Huerística violada: Prevenção de erros</li>
    </ul>
    <li><h3>Perda de tempo do usuário</h3></li>
    <ul>
      <li>Problema: O site mostra hotéis onde não é possivel marcar a estadia</li>
      <li>Local: Página onde se escolhe os hotéis para a hospedagem</li>
      <li>Gravidade: Problema grande</li>
      <li>Huerística violada: Flexibilidade e eficiência de uso</li>
    </ul>
</ol>

<h2>Versionamento</h2>
<table>
  <tr>
    <th>Data</th>
    <th>Versão</th>
    <th>Descrição</th>
    <th>Autor</th>
  </tr>
  <tr>
    <td>20/09</td>
    <td>1.0</td>
    <td>Primeira versão da estrutura do planejamento/avaliação em Markdown</td>
    <td>Maicon Mares</td>
  </tr>
  <tr>
    <td>03/10</td>
    <td>2.0</td>
    <td>Detalhamento da avaliação do site</td>
    <td>João Pedro Silva de Carvalho</td>
  </tr>
</table>