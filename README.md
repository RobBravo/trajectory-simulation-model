# Modelo de simulacion de trayectorias en geometrías espaciales complejas

<h2>✅ Objetivo del modelo:</h2>
<p>Simular la trayectoria de una nave desde la Tierra hacia Marte considerando la influencia gravitacional del Sol como una deformación del espacio-tiempo (basado en la relatividad general, pero simplificado para efectos computacionales).</p>
<h3>🔧 Herramientas </h3>
<ul>
  <li>Numpy para el cálculo numérico.</li>
  <li>Matplotlib para graficar las trayectorias.</li>
  <li>Scipy.integrate.solve_ivp para resolver sistemas diferenciales.</li>
  <li>Un campo gravitacional modelado como curvatura de espacio.</li>  
</ul>
<h3>🧠 Concepto base:</h3>
<p>Usaremos una versión simplificada del espacio curvado (como una deformación alrededor del Sol) para modelar cómo la nave “cae” en esa curvatura, similar a la idea de geodésicas en geometría diferencial.</p>
<h3>🧭 Fase 1:</h3>
<p>Simular la trayectoria de una nave espacial bajo la influencia gravitacional del Sol en un plano bidimensional, interpretando la gravedad como curvatura del espacio (analogía con geometría no euclidiana).</p>
<h4>¿Cómo se relaciona esto con la geometría no euclidiana y diferencial?</h4>
<ul>
  <li>En geometría euclidiana, las trayectorias (líneas rectas) serían el camino más corto.</li>
  <li>En geometría no euclidiana, la curvatura del espacio modifica estas trayectorias; en relatividad general, las geodésicas reemplazan las rectas.</li>
  <li>En nuestro modelo, una nave sigue una trayectoria curva (geodésica) inducida por la "curvatura" generada por la gravedad del Sol.</li>
</ul>


