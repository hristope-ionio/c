### Εβδομάδα #1 - Εισαγωγή στη C, το περιβάλλον codecheck.io και τα περιβάλλοντα ανάπτυξης Atom & Goorm IDE
___
Σκοπός του πρώτου εργαστηρίου είναι να εξοικειωθείτε με τη C, το περιβάλλον codecheck.io και τα περιβάλλοντα ανάπτυξης Atom & Goorm IDE ή όποιον άλλο τρόπο επιλέξετε για να εκτελείτε τον κώδικά σας.

___
Στα πρώτα εργαστήρια θα εξοικειωθείτε με τη γλώσσα C μέσα από το περιβάλλον του codecheck.io. Μέσα από το codechek.io γίνεται αυτόματη διόρθωση του κώδικά σας και δε χρειάζεται εγγραφή σε καμία πλατφόρμα.  
*Codecheck is an anonymous, author-friendly autograder. It is optimized for simple programming assignments that provide practice and build confidence.*

___
Για τα επόμενα εργαστήρια και για την υλοποίηση ασκήσεων εξάσκησης που δεν διορθώνονται αυτόματα βεβαιωθείτε ότι στο σύστημα εργασίας που εργάζεστε είναι εγκατεστημένα και ρυθμισμένα τα ακόλουθα:

* **Ανάλογα το λειτουργικό σας**  
Απαιτείται η εγκατάσταση ενός C compiler.
  * **Windows**:  Compiler: [MinGW](https://www.mingw-w64.org)
  * **Linux**: [gcc](https://www.geeksforgeeks.org/how-to-install-gcc-compiler-on-linux/)
  * **Mac**: [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)


* **Atom IDE + packages** (λήψη από: https://atom.io/)
  * βεβαιωθείτε ότι είναι εγκατεστημένο το Atom IDE
  * ελέγξτε (από το μενού `Packages > Settings View > Install Packages/Themes`) ότι έχουν εγκατασταθεί τα:
    - terminus
    - script
    - tool-bar
    - tool-bar-atom
    - gpp-compiler
    - linter
    - linter-gcc2
    - linter-ui-default

Εναλλακτικά μπορείτε να χρησιμοποιήσετε οποιοδήποτε IDE, όπως το [VS Code](https://code.visualstudio.com), το DEV-C++.  
Μία άλλη επιλογή η οποία είναι cloud based και συνεπώς σας επιτρέπει να δουλεύετε στο ίδιο περιβάλλον είτε από τον προσωπικό σας υπολογιστή στο σπίτι σας είτε από τους υπολογιστές του εργαστήριο, είναι το:
* **Goorm cloud based IDE** (εγγραφή/σύνδεση: https://ide.goorm.io/)
  * βεβαιωθείτε ότι έχετε ακολουθήσει τις οδηγίες των διαφανειών για την εγγραφή και τη δημιουργία C/C++ based container


___
#### Ασκήσεις ####
* Τοποθετήστε σωστά τις σειρές εντολών για να εμφανιστεί το Hello World!.  
[Parson Puzzle - Hello World](https://codecheck.io/files/22100219085gl7uerlfbwgcd63ukxmz8ct9)

* Συμπληρώστε τη γραμμή που λείπει με μία εντολή `printf` για να εμφανίσετε το "Hello World".  
[Print Hello World](https://codecheck.io/files/22100219466et1rsi8zjxambwn1p0j0k6tf)

* Γράψτε τον κώδικα του Hello World που είδατε παραπάνω σε ένα δικό σας αρχείο με κατάληξη `.c` . Κάνετε `compile` και εκτελέστε το __από το τερματικό__. Χρησιμοποιήστε την εντολή   
`gcc helloworld.c -o helloworld`

---
* Προσέξτε τα **σχόλια** στο πρόγραμμα (prog00.c) και συμπληρώστε τα κενά `...` για να εμφανιστεί το σωστό μήνυμα. Θέστε τη σωστή τιμή στη **μεταβλητή distance** και βρείτε πού αλλού θα χρησιμοποιηθεί.  
[prog00](https://codecheck.io/files/22100220256a2qqj3kzh0bwh5vn25hdsih4)

* Γράψτε τον κώδικα του prog00.c σε ένα δικό σας αρχείο, κάντε το `compile` και εκτελέστε το __από το τερματικό__. Χρησιμοποιήστε την εντολή   
`gcc prog00.c -o prog00`

---
* Συμπληρώστε το ακόλουθο πρόγραμμα έτσι ώστε να εμφανίζεται η τετραγωνική ρίζα του 'a'.
[var01](https://codecheck.io/files/22100220532r4xffy9zco9d0jy6ehwh6rj7)

* Γράψτε τον κώδικα του var01.c σε ένα δικό σας αρχείο, κάντε το `compile` και εκτελέστε το __από το τερματικό__. Χρησιμοποιήστε την εντολή   
`gcc var01.c -o var01 -lm`
