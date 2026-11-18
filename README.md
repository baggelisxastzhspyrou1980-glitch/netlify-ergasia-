# 🎨 Netlify-ece-example: Portfolio με HTML, CSS και Netlify

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=flat&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)

Μια στατική σελίδα **portfolio** για τη διάλεξη **HTML και CSS** του μαθήματος
[**Δικτυακός Προγραμματισμός** (HMMY105)](https://eclass.uowm.gr/courses/HMMY105/) του Τμήματος ΗΜΜΥ του
Πανεπιστημίου Δυτικής Μακεδονίας. Η σελίδα δημοσιεύεται στο **Netlify** και η φόρμα επικοινωνίας λειτουργεί με τις **Netlify Forms**.

🌐 **Live:** [ecedemo.netlify.app](https://ecedemo.netlify.app/)

---

## 📂 Αρχεία

| Αρχείο | Ρόλος |
|---|---|
| `index.html` | Η δομή της σελίδας: header με φωτογραφία, ενότητες *About Me*, *Resume*, *Projects*, φόρμα επικοινωνίας και footer |
| `styles.css` | Η εμφάνιση: χρώματα, γραμματοσειρές, στυλ για τη φόρμα και το κουμπί, responsive διάταξη με media query |
| `formValidation.js` | Έλεγχος των πεδίων της φόρμας πριν από την αποστολή |

## 🧩 Τι περιέχει η σελίδα

- **HTML:** σημασιολογικά tags (`header`, `section`, `footer`), επικεφαλίδες, λίστες (`ul`/`li`), εικόνα, σύνδεσμοι και φόρμα με `input`, `textarea` και `button`.
- **CSS:** επιλογείς στοιχείων, id (`section#about`) και attribute (`input[type="email"]`), `:hover`, `border-radius`, `flex` και ένα `@media` για μικρές οθόνες.
- **JavaScript:** στο `submit` της φόρμας ελέγχει ότι όνομα, email και μήνυμα δεν είναι κενά και ότι το email έχει σωστή μορφή (`/^[^\s@]+@[^\s@]+\.[^\s@]+$/`). Αν κάτι λείπει, εμφανίζει μήνυμα και σταματά την αποστολή με `event.preventDefault()`. Αν όλα είναι σωστά, κρύβει τη φόρμα και εμφανίζει μήνυμα ευχαριστίας.
- **Netlify Forms:** τα attributes `data-netlify="true"` και το κρυφό πεδίο `form-name` αρκούν ώστε το Netlify να συλλέγει τις υποβολές της φόρμας, χωρίς δικό μας server.

## ▶️ Εκτέλεση

**Τοπικά:** ανοίξτε το `index.html` σε έναν browser. Δεν χρειάζεται εγκατάσταση. Η αποστολή της φόρμας λειτουργεί μόνο όταν η σελίδα φιλοξενείται στο Netlify.

**Δημοσίευση στο Netlify:**

1. Κάντε fork ή αντιγράψτε το αποθετήριο στο δικό σας GitHub.
2. Στο [Netlify](https://www.netlify.com/): *Add new site → Import an existing project* και επιλέξτε το αποθετήριο.
3. Δεν χρειάζεται build command. Το publish directory είναι η ρίζα του αποθετηρίου.
4. Μετά το deploy, οι υποβολές της φόρμας εμφανίζονται στην ενότητα *Forms* του site στο Netlify.

## ✏️ Δοκιμάστε

- Αντικαταστήστε τα στοιχεία της *Jane Doe* με τα δικά σας και δημοσιεύστε το δικό σας portfolio.
- Προσθέστε μια νέα ενότητα (π.χ. *Certificates*) με δικό της στυλ στο `styles.css`.
- Εμφανίστε τα μηνύματα σφάλματος κάτω από κάθε πεδίο αντί για `alert()`.

---

## 🙏 Credits

Το παράδειγμα αναπτύχθηκε σε συνεργασία με τον συνάδελφο **[Χρήστο Αναστασίου](https://github.com/Christos-16)**, τον οποίο ευχαριστώ θερμά για τη συνεργασία.

Σχετικό υλικό του μαθήματος: [WebProgECE_2026](https://github.com/chitiris/WebProgECE_2026).
