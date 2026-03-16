## Conferentie Registratie

Maak een volledig functioneel en responsief registratieformulier voor een tech-conferentie. Dit formulier moet alle geleerde concepten over formulieren en styling combineren.

### Onderdelen van het formulier

- **Persoonlijke Gegevens:**
  - Volledige naam (text, verplicht)
  - E-mailadres (email, verplicht)
  - Wachtwoord (password, verplicht, minstens 8 tekens)
- **Registratie Details:**
  - Datum van deelname (date, verplicht)
  - Ticket type (radiobuttons: Early Bird, Regular, VIP)
  - Workshops (checkboxes: Web Design, Backend, DevOps)
- **Extra Info:**
  - Profielfoto (file upload)
  - Extra opmerkingen (textarea)
  - Akkoord gaan met de voorwaarden (checkbox, verplicht)
- **Verzenden:**
  - Een duidelijke submit button.

### Technische Eisen

- **Layout & Responsiviteit:**
  - Gebruik **Flexbox** om inputgroepen (bijv. Naam en E-mail) naast elkaar te zetten op grote schermen, maar onder elkaar op mobiel.
  - Zorg ervoor dat het formulier maximaal 800px breed is en gecentreerd staat op de pagina.
  - Gebruik de algemene layout (witte container, gradient achtergrond, padding).
- **CSS Pseudo-classes:**
  - Geef visuele feedback met `:valid` en `:invalid` (bijv. een groene of rode border).
  - Gebruik `:focus` om het actieve veld te accentueren met een paarse outline.
  - Gebruik `:required` om de labels van verplichte velden subtiel te markeren (bijv. een rood sterretje `*` via een `::after` pseudo-element).
  - De submit button moet een hover effect hebben.
- **Toegankelijkheid:**
  - Elk invoerveld **moet** een bijbehorend `<label>` hebben dat correct gelinkt is via het `for` en `id` attribuut.
  - Gebruik `<fieldset>` en `<legend>` om logische groepen te maken (bijv. voor Ticket type en Workshops).
