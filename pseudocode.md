1. LET "bookPile" be the pile of books
2. IF "bookPile" is empty or contains only one book, THEN it is already sorted
3. LET "theFirstBook" be the book with the highest alphabetical priority in "bookPile"
4. FOR each book in "bookPile"
5. IF book comes before "theFirstBook" in alphabetical order, THEN SET "theFirstBook" to book
6. MOVE "theFirstBook" from "bookPile" to the sorted pile of books
7. GOTO step 2