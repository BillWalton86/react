import React from 'react';
import ReactDOM from 'react-dom';


class Button extends React.Component {
  scream() {
	alert('AAAAHHHHHHH!!');
  }

  render() {
	return <button onClick={this.scream}>AAAHHH!</button>;
  }
}

ReactDOM.render(
	<Button />,
	document.getElementById('app')
);

