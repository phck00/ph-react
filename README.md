# ph-react
import React from 'react';
import ReactDOM from 'react-dom';

const Botao = (props) => {
  return (
    <button>{props.texto}</button>
  );
};

const App = () => {
  return (
    <div>
      <h1>Exemplo de Utilização de Props</h1>
      <Botao texto="Clique Aqui" />
    </div>
  );
};

ReactDOM.render(<App />, document.getElementById('root'));
