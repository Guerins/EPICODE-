# EPICODE-

    <!-- Tabella a 3 colonne -->
    <table>
      <thead>
        <tr>
          <th>Anno</th>
          <th>% di utilizzo</th>
          <th>Supporto browsers</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2000</td>
          <td>20%</td>
          <td>20% di browser supportati</td>
        </tr>
        <tr>
          <td>2002</td>
          <td>35%</td>
          <td>30% di browser supportati</td>
        </tr>
        <tr>
          <td>2004</td>
          <td>45%</td>
          <td>40% di browser supportati</td>
        </tr>
        <tr>
          <td>2008</td>
          <td>80%</td>
          <td>70% di browser supportati</td>
        </tr>
        <tr>
          <td>2012</td>
          <td>100%</td>
          <td>Browser completamente supportati</td>
        </tr>
      </tbody>
    </table>

    <!-- Video YouTube -->
    <section class="video">
      <h3>Guarda il nostro video</h3>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/video-id" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>

  </section>
</article>

<!-- Modulo Newsletter -->
<section class="newsletter">
  <h2>Vuoi rimanere aggiornato su altre novità del blog? Iscriviti alla nostra newsletter:</h2>
  <form action="#" method="POST">
    <input type="email" name="email" placeholder="Inserisci la tua email" required>
    <button type="submit">Iscriviti!</button>
  </form>
</section>

<!-- Articoli Correlati -->
<section class="related-articles">
  <h2>Articoli correlati</h2>
  <ul>
    <li><a href="#">Validare il codice HTML</a> - Categoria: Develop - Data: 18-9-2020</li>
    <li><a href="#">Correggere la sintassi</a> - Categoria: Develop - Data: 16-9-2020</li>
    <li><a href="#">Meno Kb nella pagina</a> - Categoria: Ottimizzazione - Data: 30-9-2020</li>
  </ul>
</section>

/* Impostazioni generali */
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #007bff;
    color: white;
    padding: 10px 15px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 24px;
}

header p {
    margin: 0;
    font-size: 18px;
}

/* Sezione Chi Sono */
.chi-sono {
    background-color: #ffffff;
    padding: 15px;
    margin: 15px;
    border-radius: 5px;
}

.chi-sono h2 {
    font-size: 20px;
    margin-bottom: 10px;
}

.chi-sono p {
    font-size: 14px;
}

/* Sezione Competenze */
.competenze {
    background-color: #ffffff;
    padding: 15px;
    margin: 15px;
    border-radius: 5px;
}

.competenze h2 {
    font-size: 20px;
    margin-bottom: 10px;
}

.competenze ul {
    padding-left: 20px;
    font-size: 14px;
}

.competenze li {
    margin-bottom: 5px;
}

/* Sezione Esperienza */
.esperienza {
    margin-bottom: 20px;
}

.esperienza h2 {
    font-size: 20px;
    margin-bottom: 8px;
}

.esperienza article {
    background-color: #f1f1f1;
    padding: 10px;
    border-radius: 5px;
    margin-bottom: 10px;
}

.esperienza h3 {
    font-size: 16px;
    margin: 0;
}

.esperienza p {
    font-size: 14px;
}

/* Sezione Contatti */
.contatti {
    background-color: #ffffff;
    padding: 15px;
    margin: 15px;
    border-radius: 5px;
}

.contatti h2 {
    font-size: 20px;
    margin-bottom: 10px;
}

.contatti p {
    font-size: 14px;
}

/* Sezione Hobby e Interessi */
.hobby-interessi {
    background-color: #ffffff;
    padding: 15px;
    margin: 15px;
    border-radius: 5px;
}

.hobby-interessi h2 {
    font-size: 20px;
    margin-bottom: 10px;
}

.hobby-interessi ul {
    padding-left: 20px;
    font-size: 14px;
}

.hobby-interessi li {
    margin-bottom: 5px;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

/* Responsive Design */
@media (max-width: 500px) {
    header h1 {
        font-size: 20px;
    }

    header p {
        font-size: 16px;
    }

    .chi-sono h2, .competenze h2, .esperienza h2, .contatti h2, .hobby-interessi h2 {
        font-size: 18px;
    }

    .chi-sono p, .competenze li, .esperienza p, .contatti p, .hobby-interessi li {
        font-size: 12px;
    }

    .esperienza h3 {
        font-size: 14px;
    }

    footer {
        font-size: 12px;
    }
}
