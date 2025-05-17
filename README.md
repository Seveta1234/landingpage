# landingpage
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Versicherungsberatung – Kostenlose & unverbindliche Beratung</title>
<style>
  /* Grundlegendes Reset */
  * {
    box-sizing: border-box;
  }
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; padding: 0;
    background: #f5f7fa;
    color: #333;
  }
  .container {
    max-width: 480px;
    margin: 50px auto 40px auto;
    background: #fff;
    padding: 40px 30px 30px 30px;
    border-radius: 12px;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.12);
    transition: box-shadow 0.3s ease;
  }
  .container:hover {
    box-shadow: 0 12px 36px rgba(0, 0, 0, 0.18);
  }
  h1 {
    font-size: 2rem;
    color: #00539c;
    margin-bottom: 16px;
    font-weight: 700;
    line-height: 1.2;
  }
  p.subtitle {
    font-size: 1.125rem;
    margin-bottom: 28px;
    color: #555;
    line-height: 1.5;
  }
  label {
    display: block;
    margin-bottom: 8px;
    font-weight: 600;
    color: #222;
  }
  input[type="text"],
  input[type="tel"],
  input[type="email"],
  select,
  textarea {
    width: 100%;
    padding: 12px 14px;
    margin-bottom: 22px;
    border: 1.8px solid #ccc;
    border-radius: 8px;
    font-size: 1rem;
    font-family: inherit;
    transition: border-color 0.3s ease;
  }
  input[type="text"]:focus,
  input[type="tel"]:focus,
  input[type="email"]:focus,
  select:focus,
  textarea:focus {
    border-color: #00539c;
    outline: none;
    box-shadow: 0 0 6px #91c3ff;
  }
  textarea {
    min-height: 90px;
    resize: vertical;
  }
  button {
    width: 100%;
    padding: 16px;
    background-color: #0071bc;
    border: none;
    border-radius: 10px;
    color: white;
    font-size: 1.2rem;
    font-weight: 700;
    cursor: pointer;
    transition: background-color 0.3s ease;
    box-shadow: 0 4px 12px rgba(0, 113, 188, 0.4);
  }
  button:hover {
    background-color: #005a8f;
  }
  .trust-section {
    margin-top: 28px;
    font-size: 0.95rem;
    color: #444;
    line-height: 1.4;
  }
  .trust-section p {
    margin: 8px 0;
    display: flex;
    align-items: center;
  }
  .trust-section p::before {
    content: "✔";
    color: #0071bc;
    font-weight: bold;
    margin-right: 8px;
  }
  footer {
    max-width: 480px;
    margin: 0 auto 40px auto;
    font-size: 0.9rem;
    color: #777;
    text-align: center;
  }
  footer a {
    color: #0071bc;
    text-decoration: none;
    font-weight: 600;
  }
  footer a:hover {
    text-decoration: underline;
  }
  @media (max-width: 520px) {
    .container {
      margin: 30px 15px 30px 15px;
      padding: 30px 20px 25px 20px;
    }
  }
</style>
</head>
<body>

<div class="container" role="main" aria-label="Versicherungsberatung Landingpage">
  <h1>Kostenlose &amp; unverbindliche Beratung für deine Versicherung!</h1>
  <p class="subtitle">
    Sorge jetzt vor – wir finden den besten Schutz für dich.<br />
    Du möchtest sicher sein, dass deine Absicherung passt?<br />
    Oder clever bei deiner Kfz-Versicherung sparen?<br />
    Dann sichere dir jetzt dein kostenloses Beratungsgespräch!
  </p>

  <form action="DEIN_FORMULAR_HANDLER_URL" method="POST" aria-label="Versicherungsberatung Anfrageformular" novalidate>
    <label for="vorname">Vorname *</label>
    <input type="text" id="vorname" name="vorname" required autocomplete="given-name" placeholder="Max" />

    <label for="nachname">Nachname *</label>
    <input type="text" id="nachname" name="nachname" required autocomplete="family-name" placeholder="Mustermann" />

    <label for="telefon">Telefonnummer *</label>
    <input type="tel" id="telefon" name="telefon" required autocomplete="tel" placeholder="+49 123 4567890" />

    <label for="email">E-Mail *</label>
    <input type="email" id="email" name="email" required autocomplete="email" placeholder="max.mustermann@email.de" />

    <label for="anliegen">Anliegen *</label>
    <select id="anliegen" name="anliegen" required>
      <option value="" disabled selected>Bitte auswählen</option>
      <option value="Berufsunfaehigkeit">Berufsunfähigkeit</option>
      <option value="Altersvorsorge">Altersvorsorge</option>
      <option value="Kfz-Wechsel">Kfz-Wechsel</option>
      <option value="Haftpflicht">Haftpflicht</option>
      <option value="Sonstiges">Sonstiges</option>
    </select>

    <label for="beschreibung">Bisherige Versicherung &amp; Grund für Wechsel (optional)</label>
    <textarea id="beschreibung" name="beschreibung" placeholder="Beschreibe bitte kurz, welche Versicherung du aktuell hast und warum du unzufrieden bist oder wechseln möchtest."></textarea>

    <button type="submit" aria-label="Beratung jetzt sichern">Jetzt Beratung sichern!</button>
  </form>

  <div class="trust-section" aria-live="polite">
    <p>Kostenfrei &amp; unverbindlich</p>
    <p>Persönliche Beratung vom Experten</p>
    <p>Datenschutz garantiert</p>
  </div>
</div>

<footer>
  <p><a href="/impressum.html" target="_blank" rel="noopener noreferrer">Impressum</a> | <a href="/datenschutz.html" target="_blank" rel="noopener noreferrer">Datenschutz</a></p>
  <p>Kontakt: <a href="tel:+491234567890">+49 123 4567890</a> | <a href="mailto:info@deinefirma.de">info@deinefirma.de</a></p>
</footer>

</body>
</html>
