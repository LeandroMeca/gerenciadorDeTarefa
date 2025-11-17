<h1>📝 Gerenciador de Tarefas React</h1>

<p>Um projeto simples de um "To-Do List" (Gerenciador de Tarefas) criado com React e Vite. Permite ao usuário adicionar, excluir, completar e ver detalhes de tarefas. O projeto utiliza o localStorage do navegador para persistir os dados, garantindo que as tarefas não sejam perdidas ao recarregar a página.</p>

<h2>✨ Funcionalidades</h2>

<ul>
  <li><strong>Adicionar Tarefas:</strong> Formulário para adicionar novas tarefas com título e descrição.</li>
  <li><strong>Listar Tarefas:</strong> Exibe a lista de tarefas pendentes e concluídas.</li>
  <li><strong>Completar Tarefas:</strong> Permite marcar/desmarcar uma tarefa como concluída (clicando no título).</li>
  <li><strong>Excluir Tarefas:</strong> Remove tarefas da lista.</li>
  <li><strong>Ver Detalhes:</strong> Navega para uma página de detalhes separada para cada tarefa.</li>
  <li><strong>Persistência de Dados:</strong> Salva e carrega as tarefas do localStorage do navegador.</li>
</ul>

<h2>💻 Tecnologias Utilizadas</h2>

<p>Este projeto foi construído utilizando as seguintes tecnologias:</p>

<ul>
  <li><strong>React:</strong> Biblioteca principal para a construção da interface do usuário.</li>
  <li><strong>Vite:</strong> Ferramenta de build e servidor de desenvolvimento local.</li>
  <li><strong>React Router DOM:</strong> Para gerenciamento de rotas e navegação entre páginas (ex: página de detalhes).</li>
  <li><strong>Tailwind CSS:</strong> Framework CSS utility-first para estilização rápida e responsiva.</li>
  <li><strong>Lucide React:</strong> Biblioteca de ícones SVG.</li>
  <li><strong>UUID:</strong> Para a geração de IDs únicos para cada nova tarefa.</li>
</ul>

<h2>🚀 Como Rodar o Projeto</h2>

<p>Para rodar este projeto localmente, siga os passos abaixo:</p>

<h3>Clone o repositório</h3>
<pre><code>git clone https://github.com/LeandroMeca/gerenciadorDeTarefa.git</code></pre>

<h3>Navegue até o diretório do projeto</h3>
<pre><code>cd [NOME_DO_SEU_PROJETO]</code></pre>

<h3>Instale as dependências</h3>
<pre><code>npm install</code></pre>

<h3>Rode o projeto em modo de desenvolvimento</h3>
<pre><code>npm run dev</code></pre>

<h3>Abra seu navegador</h3>
<p>A aplicação estará disponível em http://localhost:5173 (ou na porta indicada pelo Vite).</p>

<h2>📂 Estrutura de Componentes</h2>

<p>O projeto está organizado da seguinte forma:</p>

<ul>
  <li><strong>App.jsx:</strong> Componente principal que gerencia o estado das tarefas (adicionar, excluir, completar).</li>
  <li><strong>main.jsx:</strong> Ponto de entrada da aplicação, onde o React Router é configurado.</li>
  <li><strong>/components:</strong>
    <ul>
      <li><strong>AddTask.jsx:</strong> Formulário para adicionar novas tarefas.</li>
      <li><strong>Task.jsx:</strong> Componente que renderiza a lista de tarefas.</li>
      <li><strong>Button.jsx:</strong> Componente de botão reutilizável.</li>
      <li><strong>Input.jsx:</strong> Componente de input reutilizável.</li>
      <li><strong>Title.jsx:</strong> Componente de título reutilizável.</li>
    </ul>
  </li>
  <li><strong>/pages:</strong>
    <ul>
      <li><strong>TaskPage.jsx:</strong> Página que exibe os detalhes de uma tarefa específica.</li>
    </ul>
  </li>
</ul>
