# App.jsx.
evidencia GA7-220501096-AA4-EV03
import React from 'react';
import GestionPropiedades from './components/GestionPropiedades';

function App() {
  return (
    <div className="App">
      <header style={{ backgroundColor: '#2c3e50', padding: '20px', color: 'white', textAlign: 'center' }}>
        <h1>INMOSOFT - Sistema de Gestión Inmobiliaria</h1>
      </header>
      <main>
        <GestionPropiedades />
      </main>
    </div>
  );
}

export default App;
