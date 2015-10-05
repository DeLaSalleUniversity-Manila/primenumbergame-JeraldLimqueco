# primenumbergame
primenumbergame-JeraldLimqueco created by Classroom for GitHub

This assignment illustrates the usage of a simple Buttons and basic Event handling. It also introduces the application of toasts for user feedback.

## Problem:

Design and implement an Android game application that displays a random number (2 to 999) and lets the user guess whether that number is Prime or Composite. A correct answer is rewarded with +1 points while the incorrect answer is penalized with -5 points. Display the current score in a TextView. Provide feedback to the user after his/her answer using a Toast. 

## Basig Game Scoring Logic:

```Java
        if (!(isPrime(number) ^ answer)) {
            score++;
            Toast.makeText(this, "Congratulations!", Toast.LENGTH_SHORT).show();
        } else {
            score -= 5;
            Toast.makeText(this, "Wrong!", Toast.LENGTH_SHORT).show();
        }
```



