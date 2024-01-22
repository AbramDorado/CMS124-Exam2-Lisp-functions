# CMSC124-Exam-Lisp-Functions
This is our 2nd Exam in CMSC 124. Our professor gave us some problems to solve in LISP and that we need to make some LISP functions. This was done in the first semester of my second year.

LISP Setup:
1. DL GNU CLISP and install

Program Setup:
1. Open the file *.txt (where the code is stored)
2. Launch GNU CLISP
3. Copy paste the function to the CLISP terminal
    Ex: (defun dupli (list)
  (if (null list)
      '()
      (cons (first list)
            (cons (first list)
                  (dupli (rest list))))))

4. Copy paste the function caller
    Ex: (dupli '(a b c))
=> (a a b b c c )
6. Done!
