<h1 align="center">Desafio 01 - Conceitos do React</h1>

<p align="center">
  <a href="#-Sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Template-da-aplicação">Template da aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-executando">Executando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
  <img src="https://img.shields.io/static/v1?label=Ignite&message=ReactJS&color=8257E5&labelColor=000000" alt="Ignite" />
</p>

## 💻 Sobre o desafio

<p align="justify">
Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS
Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer,
para treinar um pouco mais sobre manipulação do estado no React.
  
  <ul>
    <li>Adicionar uma nova tarefa</li>
    <li>Remover uma tarefa</li>
    <li>Marcar e desmarcar uma tarefa como concluída</li>
  </ul>
</p>

## 🎯 Template da aplicação

<p>Você pode encontrar o template <a href="https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react" target="_blank">aqui</a></p>

## O que devo fazer no desafio ?

<p align="justify">
  Com o template já clonado, as depêndencias instaladas, você deve completar onde não possui código com o código para atingir os objetivos de cada teste.
  Nesse desafio, você deve editar apenas o seguinte arquivo para completar as funcionalidades da aplicação: <strong>src/components/TaskList.tsx</strong>
  
  Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são
  
  <ul>
    <li>
      <strong>handleCreateNewTask</strong> Deve ser possível adicionar uma nova task no estado de tasks, com os campos id que deve ser gerado de forma aleatória,
      title que deve ser um texto e isComplete que deve iniciar como false.
    </li>
    <li>
      <strong>handleToggleTaskCompletion</strong> Deve alterar o status de isComplete para uma task com um ID específico que é recebido por parâmetro
    </li>
    <li>
      <strong>handleRemoveTask</strong> Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.
    </li>
  </ul>
</p>

## Especificação dos testes

- [X] <strong>should be able to add a task</strong>: Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela.
As taks criadas devem conter os atributos seguindo o padrão da interface, que é:
```
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```
- [X] <strong>should not be able to add a task with an empty title:</strong> Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio,
caso o valor digitado seja vazio, você deve impedir a criação da task
- [X] <strong>should be able to remove a task:</strong> Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.
- [X] <strong>should be able to check a task:</strong> Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de isComplete de false para true ou ao contrário, de true para false


## 🚀 Executando

- Clone o repositório e acesse a pasta criada
- Instale as dependências com `yarn` ou `npm install`;
- Inicie a aplicação com `yarn dev`;
- Faça os testes com o comando `yarn test` ou `npm run test`;

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
