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
<h4>🔗¿Cómo se relaciona esto con la geometría no euclidiana y diferencial?</h4>
<ul>
  <li>En geometría euclidiana, las trayectorias (líneas rectas) serían el camino más corto.</li>
  <li>En geometría no euclidiana, la curvatura del espacio modifica estas trayectorias; en relatividad general, las geodésicas reemplazan las rectas.</li>
  <li>En nuestro modelo, una nave sigue una trayectoria curva (geodésica) inducida por la "curvatura" generada por la gravedad del Sol.</li>
</ul>
<h4>🔗Relación con la conjetura de Poincaré</h4>
<p>Aunque la conjetura no trata directamente sobre trayectorias, su demostración con el Ricci flow nos deja una poderosa lección:</p>
<ul>
  <li>Los espacios curvos pueden evolucionar para revelar su verdadera forma topológica.</li>
  <li>En astrodinámica, entender la forma del espacio-tiempo (por ejemplo, la topología del entorno solar) permite calcular trayectorias óptimas.</li>
  <li>Nuestro modelo explora cómo el espacio curvo genera trayectorias que reflejan su estructura interna, como las 3-variedades estudiadas en topología.</li>
  <li>Así, mientras Poincaré intentó clasificar formas posibles del espacio tridimensional, aquí trazamos caminos a través de ese espacio curvado, influenciado por masas como el Sol.</li>
</ul>
<h4>🧪 Fase 1 – Implementación del modelo:</h4>
<p>🔸 Supuestos:</p> 
<ul>
  <li>Solo el Sol influye gravitacionalmente.</li>
  <li>Movimiento en 2D (plano eclíptico).</li>
  <li>La nave sigue una trayectoria afectada por esta “curvatura gravitacional”.</li>
  <li>Se simula por medio de ecuaciones de movimiento derivadas de una potencial newtoniano deformado.</li>
</ul>
<h4>🔍 Analisis de los resultados</h4>
<p>1. La trayectoria azul Representa el camino que seguiría una nave lanzada desde la Tierra bajo la única influencia gravitacional del Sol. Está modelada como un problema de dos cuerpos en 2D, con el Sol fijo en el origen.</p>
<p>2. La curvatura del espacio (implícita)
Aunque no ves la curvatura directamente, el hecho de que la nave no sigue una línea recta sino una órbita curva es una manifestación implícita de la geometría no euclidiana: el espacio está “deformado” por la masa del Sol.</p>
<blockquote>En términos de relatividad, la trayectoria calculada es una geodésica en una métrica deformada por masa, aunque aquí se simula con física newtoniana. </blockquote>













