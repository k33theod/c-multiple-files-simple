# c-multiple-files-simple
Παράδειγμα δημιουργίας πρόγράμματος με πολλά αρχεία κώδικα
Δημιουργώ ένα πηγαίο αρχείο maxim.c που βάζω μέσα την υλοποίηση του κώδικα μου και ένα αρχείο maxim.h με το ίδιο όνομα που βάζω μέσα τα πρωτότυπα.
Στο αρχείο maxim.c κάνω #include"maxim.h" με τον τρόπο αυτό ελέγχεται αν το πρότυπο συμφωνεί με την υλοποίηση
Στο αρχείο maxim.h  βάζω επίσης ενα codeguard αυτό με τα define δηλαδή. Την πρώτη φορά που θα διαβαστεί το maxim.h θα οριστεί το _maxim_h_. Eάν και άλλο αρχείο χρησιμοποιεί το maxim.h δεν θα ξαναγίνει iclude θα πάει κατευθείαν στο endif και τέλος. Έτσι αποφεύγω την πολλαπλή εισαγωγή του ίδιου αρχείου.
Στο main.c κάνω #include "maxim.h"
