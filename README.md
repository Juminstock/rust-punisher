<h1 align="center">Rust-start</h1>
<p>
  Aprenderemos inicialmente a instalar <a href="https://www.rust-lang.org/es">Rust</a>, el clasico Hello, world!, y algunas consideraciones sobre <a href="https://www.rust-lang.org/es">rustc</a> y <a href="https://www.rust-lang.org/es">cargo</a>.
</p>
<h2 align="center">Instalación</h2>
<p>
  Es sencilla, en mi caso, como usuario de Linux basta con ejecutar este comando en la terminal: <br>
  <code> curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh </code> Este co
  
  Un posible error puede ser la ausencia de un linker, para solucionarlo instalamos el paquete <code>build-essential</code> en     Linux.
</p> 
  Al hacerlo, veremos nuestro código impreso en la pantalla. Así, habremos creado nuestro primer programa usando Rust, ¡bienvenido, rustacean!
</p>
<p>
  Dato: Notemos que el macro que imprime el <em>hello world</em> se ejecuta dentro de la función <em>main(){}</em>, por regla general los programas en Rust comienzan con la función <em>main()</em> la cúal se traduce como la <em>función principal</em>, el compilador de Rust ejecutar
