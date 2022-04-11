# Lösung Aufgabe 1


```
// Smart Typecast to Button
if (v is Button) {
   // Check if text is empty
   if (v.text.toString() != "") {
       // Button already clicked
       return
   }

   // Set X or O
   v.text = if (player1Turn) "X" else "O"

   // Increase round counter
   roundCount++

   if (checkForWin()) {
       // Display winner
       if (player1Turn) {
           player1Wins()
       } else {
           player2Wins()
       }
   } else if (roundCount == 9) {
       // draw -> reset board
       draw()
   } else {
       // change player
       player1Turn = !player1Turn
   }
}
```


# Lösung Aufgabe 2

```
// Iterate over all buttons
for (i in 0..2) {
   for (j in 0..2) {
       // Set text to empty String
       buttons[i][j]!!.text = "" // non-null assertion operator necessary, 
       // because we create the button array with null pointer. They get the reference later in the onCreate method. See line 12-15
   }
}
roundCount = 0
player1Turn = true
```
