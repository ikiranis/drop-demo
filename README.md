# DROP (Διαχείριση Εγγράφων / Ηλεκτρονικό Πρωτόκολλο Αλληλογραφίας)

Η εφαρμογή αυτή είναι μια υλοποίηση από την αρχή, [αυτής](https://apps4net.eu/drop/) της web εφαρμογής. Απευθύνεται σε μικρές και μεσαίες επιχειρήσεις, για την διαχείριση των εγγράφων τους και την τήρηση ηλεκτρονικού πρωτόκολου αλληλογράφιας.

Χρησιμοποιούνται νέες τεχνολογίες, ώστε να είναι εύκολο στον οποιοδήποτε, να την εκτελέσει στο pc του, χωρίς να χρειάζεται να εγκαταστήσει server ή βάση δεδομένων. Συγκεκριμένα, έχει γραφτεί σε Java με χρήση του Spring Boot. Αυτό βοηθάει στο να δημιουργείται τοπικά ένας web server και μία βάση δεδομένων. O χρήστης μετά μπαίνει μέσα από τον browser του στην εφαρμογή. 

Τo frontend είναι γραμμένο σε Vue και TypeScript.

Η εφαρμογή είναι υπό ανάπτυξη αυτή την στιγμή. Μπορείτε να κατεβάσετε ένα demo μιας πρώτης alpha έκδοσης. Μέχρι τώρα έχει φτιαχτεί η βασική αρχιτεκτονική και οι βασικές λειτουργίες. Δηλαδή μπορεί κάποιος να δημιουργήσει έγγραφα, να ανεβάσει τα αρχεία του και να εκτελέσει βασικές λειτουργίες αναζήτησης, επεξεργασίας, διαγραφής. Ενώ προς το παρόν είναι μόνο στα Αγγλικά.

Τα χαρακτηριστικά που σχεδιάζονται να υπάρχουν στην τελική έκδοση είναι:

- Απευθείας δημιουργία και βασική επεξεργασία αρχείων word
- Ψηφιακή υπογραφή
- Υποστήριξη χρηστών και ομάδων χρηστών, με τα αντίστοιχα δικαιώματα στα σχετικά έγγραφα
- Διαχείριση εγγράφων ανα project
- Αυτόματη δημιουργία ετικετών, για αρχεία κειμένου
- Πολυγλωσσική υποστήριξη
- Export/import database

Αν ενδιαφέρεστε να μπει και κάποιο άλλο χαρακτηριστικό, μπορείτε να ανοίξετε ένα issue σε αυτό το repository.

### Κατέβασμα και εκτέλεση της εφαρμογής

- Κατεβάστε το demo πατώντας δεξιά, στο σχετικό αρχείο.

- Εκτελέστε την γράφοντας στο terminal ``java -jar drop-0.0.1.jar`` ή κάνοντας διπλό κλικ στο αρχείο jar (σε αυτή τη περίπτωση, επειδή δεν έχει ακόμη κάποιο περιβάλλον GUI δεν θα φανεί ότι εκτελείται). Στο terminal θα εμφανιστεί το url της εφαρμογής. Συγκεκριμένα είναι το **http://localhost:9999/**.

Για την εκτέλεση απαιτείται η εγκατάσταση της [Java](https://www.java.com/en/download/) (έκδοση 17 ή νεώτερη)


