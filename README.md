# 🦗 Modul A – HTML Links & Lists

Dette prosjektet er en øvelse i bruk av **HTML-lenker**, **navigasjon** og **ulike listetyper**. Med tre enkle nettsider (Home, About, Contact) demonstrerer prosjektet hvordan man bygger navigasjonsmenyer, lenker til eksterne og interne sider, og bruker lister til å organisere informasjon.

---

## 🧠 Hva du lærer

✅ Hvordan lage interne og eksterne lenker med `<a href="">`  
✅ Bruk av `target="_blank"` for å åpne lenker i nye faner  
✅ Strukturert `nav`-meny med `ul` og `li`  
✅ Bruk av ulike listetyper:
- **Unordered list** (`<ul>`)
- **Ordered list** (`<ol>`)
- **Description list** (`<dl><dt><dd>`)  
✅ Grunnleggende CSS for lenkestil og hover-effekter  
✅ Bruk av klasser og kombinatorselektorer for mer presis styling

---

## 📄 Filoversikt

| Fil         | Beskrivelse                           |
|-------------|----------------------------------------|
| `index.html`| Hjemmeside med ekstern lenke og bilde |
| `about.html`| Om oss-side med `ol` og `dl`          |
| `contact.html`| Kontaktside med knapp og linkliste  |
| `style.css` | Felles styling for alle sidene        |

---

## 🔗 Navigasjonsmeny (eksempel)

```html
<nav>
  <ul>
    <a href="./index.html"><li>Home</li></a>
    <a href="./about.html"><li>About us</li></a>
    <a href="./contact.html"><li>Contact</li></a>
  </ul>
</nav>
