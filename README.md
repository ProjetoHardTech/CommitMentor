# Guia GIT e Commits 📜

O domínio do versionamento de código é uma habilidade crucial para programadores e estudantes de programação. Compreender e utilizar o Git não apenas facilita o armazenamento, gerenciamento, utilização e compartilhamento de códigos, mas também se torna uma competência indispensável no desenvolvimento de software.

Este guia foi elaborado com o propósito de apoiar seus estudos, simplificar o compartilhamento dos seus projetos e viabilizar a colaboração com sua equipe, permitindo o trabalho simultâneo em um mesmo código de maneira prática e eficiente.

Ao seguir as práticas recomendadas e conceitos apresentados neste guia, você estará mais preparado para enfrentar os desafios do desenvolvimento colaborativo, otimizando seus processos e contribuindo para um fluxo de trabalho mais eficaz e organizado.


## Conceitos básicos

- `Commit`- Uma captura de mudança ou adicão, como um ponto de verificação.
- `Repositório`- Onde os seus arquivos e histórico de commit estarão guardados.
- `Branch`- Uma ramificação do projeto principal que serve como uma linha do tempo(timeline) de commits.
- `Merge`- Combinar modificações de duas branchs diferentes.
- `Pull Request`- Propor e revisar mudança antes de mergir a ramificação (branch) com branch principal.
s

## Comandos principais
<table>
  <thead>
    <tr>
      <th>Comando</th>
      <th>Descrição</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td><code>git init</code></td>
      <td>Inicializa o git na pasta local</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git clone</code></td>
      <td>Copia um repositorio remoto para uma pasta local</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git status</code></td>
      <td>Informa sobre o estado atual do repositório e o que você precisa seguir</td>
      <td></td>
    </tr>
    <tr>
      <td> <code>git add</code></td>
      <td>Adiciona os arquivos modificados para área de preparação para commitar</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git commit</code></td>
      <td>Grava os arquivos modificados da área de preparação no repositório</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git pull</code></td>
      <td>Permite Pegar commits do repositório remoto</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git push</code></td>
      <td>Permite enviar commits para o repositório remoto</td>
      <td></td>
    </tr><tr>
      <td><code>git branch</code></td>
      <td>Lista, cria, renomea ou deleta branches no repositório</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git checkout</code></td>
      <td>Permite mudar branches e commits</td>
      <td></td>
    </tr><tr>
      <td><code>git merge</code></td>
      <td>Permite juntar duas ramificações em uma</td>
      <td></td>
    </tr>
    <tr>
      <td><code>git diff</code></td>
      <td>Mostra a diferença entre dois commits, branches e etc</td>
      <td></td>
    </tr><tr>
      <td><code>git log</code></td>
      <td>Mostra o históico de commits na branch, junto autor e datas</td>
      <td></td>
    </tr>

  </tbody>
</table>


## Git no Visual Studio Code
Utilizar o Git no Visual Studio Code traz diversas facilidades adicionais que contribuem para uma experiência de desenvolvimento mais eficiente. O ambiente integrado oferece um terminal embutido, permitindo a execução de comandos Git diretamente do editor. Além disso, a integração do VsCode com o Git possibilita a utilização de extensões específicas para o controle de versão, oferecendo recursos adicionais e personalizados.

Uma das vantagens notáveis é a simplificação do processo de commit. O VsCode fornece uma interface gráfica intuitiva que facilita a seleção e visualização das alterações feitas nos arquivos. Isso torna o commit mais acessível, especialmente para desenvolvedores que preferem uma abordagem visual ou que estão começando a trabalhar com controle de versão.

Além disso, a integração profunda com o Git no VsCode permite que você visualize o histórico de commits, gerencie branches e resolva conflitos de maneira mais eficiente, tudo dentro do ambiente de desenvolvimento.

#'GitLens' é a extensão necessária para ser possível visualizar o horário, a data, a mensagem do commit e quem o fez.

![GitLens no VsCode]()



## Contribuição ✨

Ajude este projeto a ficar ainda melhor. Saiba mais como contribuir clicando **[aqui](https://github.com/ProjetoHardTech/CommitMentor/blob/main/CONTRIBUTING.md)** e a **[licença](https://github.com/ProjetoHardTech/CommitMentor/blob/main/LICENSE.md)**.