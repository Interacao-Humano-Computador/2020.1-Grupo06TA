<h1><strong>1.Política de commits</strong></h1>
<p>
    Os commits devem ser feitos de forma objetiva, descrevendo o que foi feito. Eles devem ser significativos, escritos no gerúndio, sem acentos e em português.<br>
    Exemplo: Adicionando processo de design.
</p>
<h1><strong>2.Política de branchs</strong></h1>
<p align="center">
    Para a criação e uso de branchs seguimos o modelo do gitflow:
    <img src="https://fga-eps-mds.github.io/2019.2-Amika-Wiki/docs/projeto/gitflow.jpeg"/>
    No repositório são utilizadas duas branchs principais para desenvolvimento: master e develop. A partir da develop branchs auxiliares são criadas com o propósito de desenvolver funcionalidades específicas detalhadas nas issues.
    <br>
    A master conterá a versão estável já validada nos pull requests onde será entregue cada uma das versões do projeto.
    <br>
    A branch develop será utilizada para o desenvolvimento, onde ocorrerá a integração das funcionalidades desenvolvidas pela equipe nas branchs auxiliares.
    <br>
    As branchs auxiliares têm o propósito do desenvolvimento de funcionalidades, sua nomeação deve ser feita de acordo com a issue com a qual está relacionada. Por exemplo: DOC01. Caso essa identificação não exista, deve-se utilizar a palavra "issue" seguida do número da issue no github e o nome da issue, todos separados por underline.
    <br>
    <ul>
        <li>Exemplo: DOC01_cronograma_projeto</li>
        <li>Exemplo: __issue_25_cronograma_projeto__</li>
    </ul>
    <br>
    <p>Se após o fechamento da issue, integração a develop e exclusão da branch relacionada a issue ainda existir algum bug, deve-se criar uma branch nomeada hotfix mais o nome do bug com o objetivo de resolvê-lo.</p>
    <br>
    <ul>
        <li>Exemplo: hotfix_ferramentas</li>
    </ul>
</p>
<h1><strong>3.Uso de issues</strong></h1>
<p>
    As issues têm por objetivo auxiliar no controle sobre o que é desenvolvido. Elas representarão as histórias de usuário, documentação do projeto e bugs. Os tipos de issues são os seguintes:
</p>
<br>
<ul>
    <li><strong>US</strong> -> História de usuário</li>
    <li><strong>DOC</strong> -> Documentação do projeto</li>
</ul>
<br>
<p>
    As tarefas e critérios de aceitação de cada história serão cadastrados seguindo o template definido.
</p>
<br>
<p>
    O nome das issues seguirão o seguinte padrão: [ ].
</p>
<br>
<ul>
    <li>Exemplo: <strong>[DOC01] Documentar políticas de contribuição</strong></li>
</ul>
<h1><strong>4.Política de aprovação de código</strong></h1>
<p>O nome do pull request será o nome da issue sendo feito da branch relacionada à ela para a develop. No máximo dois contribuidores devem ser ligados à avaliação do pull request, sendo que, no mínimo, um deles não deve ter participado no desenvolvimento das funcionalidades em avaliação.</p>

# Versionamento
<table>
  <tr>
    <th>Data</th>
    <th>Versão</th>
    <th>Descrição</th>
    <th>Autor</th>
  </tr>
  <tr>
    <td>21/09</td>
    <td>1.0</td>
    <td>Criação das políticas de contribuição</td>
    <td>Maicon Mares</td>
  </tr>
</table>