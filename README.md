MySQL database για το σύστημα διαχείρισης βιβλίων και συγγραφέων.

___Τεχνολογίες___

MySQL
phpMyAdmin

___Περιγραφή___

Η βάση δεδομένων χρησιμοποιείται από το Library Backend και περιλαμβάνει όλους τους απαραίτητους πίνακες και τις σχέσεις για τη διαχείριση βιβλίων και συγγραφέων.

Υλοποιείται σχέση Many-to-Many μεταξύ βιβλίων και συγγραφέων μέσω πίνακα συσχέτισης (Join Table).

___Περιεχόμενα___

library_db.sql : SQL dump της βάσης δεδομένων.
Δομή Βάσης
Books
ISBN
Title
Category
Publication Year
Authors
Name
Nationality
Date of Birth
Relationship
Ένα βιβλίο μπορεί να έχει πολλούς συγγραφείς.
Ένας συγγραφέας μπορεί να έχει πολλά βιβλία.
Εγκατάσταση

___Δημιουργία Βάσης___

CREATE DATABASE library_db;
Import μέσω phpMyAdmin
Δημιούργησε τη βάση library_db.
Επίλεξε τη βάση από το phpMyAdmin.
Πάτησε Import.
Επίλεξε το αρχείο library_db.sql.
Πάτησε Go για την εισαγωγή των δεδομένων.

___Χρήση___

Η βάση δεδομένων συνδέεται με το Spring Boot Backend μέσω MySQL και χρησιμοποιείται για την αποθήκευση και διαχείριση των δεδομένων της εφαρμογής.

___Σχετικά Repositories___

Backend: Spring Boot REST API
Frontend: React Application
