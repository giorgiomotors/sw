# Μάθημα: Τεχνολογίες Λογισμικού  

## Εργασία: Οπτικοποίηση δεδομένων χορηγιών (UK) 

## Σύνοψη  
Η συγκεκριμένη εργασία αφορά την οπτικοποίηση των στατιστικώ στοιχείων δωρεών που έχουν γίνει σε πολιτικά κομματα της Μεγάλης Βρετανίας.Σκοπός της εργασίας είναι η γνωριμία με τη βιβλιοθήκη D3 της javascript (οπτικοποίηση δεδομένων), χρησιμοποιώντας παράλληλα τις σελίδες github pages.Επίσης, σκοπός είναι η αξιοποίηση των δυνατοτήτων της γλώσσας javascript για λειτουργίες μεγένθυνσης κειμένου και text-to-speech.Τέλος, στοχεύει στην επαφή με τις γλώσσσες html,css.  

### Δήλωση και δέσμευση θέματος εργασίας  
* Ονοματεπώνυμο: **Καραντζή Παναγιώτα**  
* Αριθμός Μητρώου: **Π2015130**  
* Θέμα Εργασίας: **Οπτικοποίηση δεδομένων χορηγιών (UK)**  
* Προσωπικό αποθετήριο του κώδικα, *στο οποίο έγιναν αλλαγές*: [Link αποθετηρίου του κώδικα](https://github.com/p15kara3/D3js-uk-political-donations/tree/gh-pages)  
* Link για το εκτελέσιμο: [Link εκτελέσιμου](https://p15kara3.github.io/D3js-uk-political-donations/)  

### Αρχικές αλλαγές και ενδιάμεση αναφορά προόδου (25%), 14 Μαρτίου (Παραδοτέο 1)  

Αρχικά έγιναν οι κατάλληλες αλλαγές ώστε να αλλάξει το url της εφαρμογής και να μην χρειάζεται να καταλήγει σε "full-viz.html".  
Στην συνέχεια, έγιναν οι αλλαγές στον κώδικα ώστε οι μπάλες με τα δεδομένα, καθώς και στα αντίστοιχα 3 πεδία της ομαδοποίησης Split by party. (Αλλαγές σε αρχεία chart και index αντίστοιχα)  

![image](https://user-images.githubusercontent.com/22661913/37311500-1dade2ba-2650-11e8-80f0-eae1cb94c2f6.png)  

Έπειτα, για να ακούγεται ήχος κάθε φορά που ο χρήστης κάνει κλικ σε μία από τις επιλογές/κουμπιά ομαδοποίησης των δεδομένων έγιναν αλλαγές στο αρχείο index.html (σειρές 33-36, 60-70) και η προσθήκη του click_sound.mp3 (Σημ: ο ήχος ακούγεται για κάποιον λόγο που δεν καταλαβαίνω μόνο όταν γίνει reload και πατηθεί το κουμπί)  

Ο κώδικας τροποποιήθηκε ώστε όταν γίνεται κλικ σε μια μπάλα να εμφανίζονται αποτελέσματα για τον αντίστοιχο δωρητή στο Google. Προστέθηκε η συνάρτηση search στο αρχείο chart.js (σειρές 357-360,113)  

![image](https://user-images.githubusercontent.com/22661913/37312052-2f99732a-2652-11e8-95d5-9938b1510a61.png)  

Έγινε τροποποίηση του κώδικα ώστε να λειτουργεί το ποντίκι ως μεγεθυντικός φακός όταν μεταφέρεται πάνω από τις λέξεις του κειμένου. Αλλαγές στο αρχείο index.html, σειρές 41-49.  

![image](https://user-images.githubusercontent.com/22661913/37312218-d42ed664-2652-11e8-866c-3933020f0d5a.png)  


Τροποποιήθηκε ο κώδικας της εφαρμογής έτσι ώστε το ποντίκι όταν βρίσκεται μέσα στον κύκλο κάποιου δωρητή, να ακούγεται η ονομασία του δωρητή και το ποσό της δωρεάς. (Σχετικός σύνδεσμος: https://responsivevoice.org/).  
Αλλαγές έγιναν στα αρχεία chart.js(σειρές 400,411) και index.html(σειρά 259)  

Τέλος δημιουργήθηκε μια ακόμα επιλογή ομαδοποίησης των δεδομένων Split by the amount of the donation, όπου γίνεται ο διαχωρισμός σε δωρεές μέχρι 500.000, δωρεές μέχρι 1.000.000 και δωρεές πάνω από 1.000.000.  
Για να δημιουργηθεί η συγκεκριμένη επιλογή  ομαδοποίησης έγιναν αλλαγές και στα τρία αρχεία του κώδικα (chart.js,index.html,style.css) όπως φαίνεται στο προσωπικό μου λινκ.  

![image](https://user-images.githubusercontent.com/22661913/37313025-11a5dbb6-2656-11e8-8c63-030bed9b0dca.png)  


* ΣΗΜΕΙΩΣΗ: Έγινε δημιουργία φακέλου .csv στον φάκελο [participants](https://github.com/ioniodi/D3js-uk-political-donations/tree/master/participants) καθώς και η τοποθέτηση εικόνων των δωρητών Oscar Pinto-Hervia, John C Peake, Lord Alliance, The Halcyon Gallery, Richard D Harpin στον φάκελο [photos](https://github.com/ioniodi/D3js-uk-political-donations/tree/master/photos) του αποθετηρίου.
