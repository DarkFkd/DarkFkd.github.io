# Project 0
Bandit0: Για το επίπεδο αυτό αρκεί να συνδεθούμε στο hostname bandit.labs.overthewire.org -p 2220, με όνομα χρήστη και κωδικό bandit0, μέσω της εντολής 'ssh (hostname)'.<br>
Bandit1: Αρχικά, εκτελούμε την εντολή 'ls' προκειμένου να εντοπίσουμε το αρχείο στο directory. Στη συνέχεια τυπώνουμε το περιεχόμενό του, μέσω της εντολής 'cat (filename)' ώστε να αποσπάσουμε τον κωδικό./n
Bandit2: Για να αντιμετωπίσουμε το συγκεκριμένο επίπεδο θα ακολουθήσουμε την ίδια διαδικασία με το bandit1. Όμως αυτή τη φορά θα πρέπει να αλλάξουμε την εντολή 'cat (filename)' σε 'cat ./(filename)'. Αυτό συμβαίνει καθώς το όνομα του αρχείου είναι '-', που είναι επίσης ο τρόπος που αρχίζουμε ένα command, και έτσι ο υπολογιστής αυτό περιμένει. Βάζοντας './' του λέμε να ψάξει στο παρόν directory για το αρχείο αυτό και αποφεύγουμε την όλη σύγχυση./n
Bandit3: Παρατηρούμε πως υπάρχουν κενά στο όνομα του αρχείου. Επομένως για να υποδείξουμε πως όλες οι λέξεις αποτελούν ένα αρχείο πρέπει να τις τοποθετήσουμε ανάμεσα σε εισαγωγικά και να τρέξουμε την εντολή cat "filename".
