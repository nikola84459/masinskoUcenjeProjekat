Ovaj projekat ima za cilj da predvidi kreditnu ocenu korisnika kaorisnika, koja predstavlja kreditnu spospobnost korisnika. Ocene kredita su označene slovima od A do G i primenom tehnika klasifikacije se predviđa kreditna ocena korisnika.

Dataset sadrži određene podatke o korisnicima, odnosno njihovim ličnim i finansiskim podacima:

  Ulazni podaci koji se koriste za obučavanje modela su:
  
    person_age - godine korisnika
    person_income - primanja korisnika na godišnjem nivou
    person_home_ownership - vlasništvo nad stambenim objektom
    person_emp_length - dužina zaposlenja korisnika
    loan_amnt - iznos kredita
    loan_int_rate - kamatna stopa
    loan_status - da li je korisnik imao nekih kašnjenja o otplati kredita
    loan_percent_income - procenat prihoda korisnika koji je potreban za otplatu kredita
    cb_person_default_on_file - da li je korisnik imao kašnjenja u otplati prethodnih kredita
    cb_person_cred_hist_length - dužina kreditne istorije korisnika

Model mašinskog učenja koji je korišten za predvidjanje kreditne ocene:
  Gradient Boosting Classifier

Tačnost algoritma(accuracy) je 98.11%

                precision    recall  f1-score   support

           A       0.99      0.99      0.99      1541
           B       0.98      0.99      0.99      1439
           C       0.98      0.98      0.98       974
           D       0.97      0.95      0.96       514
           E       0.92      0.88      0.90       126
           F       0.88      0.67      0.76        21
           G       0.67      1.00      0.80         2

    accuracy                           0.98      4617
   macro avg       0.91      0.92      0.91      4617
weighted avg       0.98      0.98      0.98      4617

