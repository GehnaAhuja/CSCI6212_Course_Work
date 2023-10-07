# CSCI6212_Course_Work

## Project 2

### Hoffman Code

<p>Hoffman coding algorithm is commonly used for lossless data compression. It has two features:  
<li> These variable-length codes are designed as prefix codes, ensuring that the code assigned to one character is never a prefix of the code assigned to any other character.</li>
<li> The codes are assigned based on the frequency. So, if a character has more frequency, the smallest length code will be assigned to it. So that the weighted length of codes for all the symbols (weighted by the usage frequency) is minimized.</li></p>

### Run the Code

```
python hoffman_coding.py
```

Two ways of generating the characters and frequency of the code:
<li> Currently it takes 1 to 10^6 as its characters according to the loop, which runs in 5,10,50,100....1000000 fashion and frequency is random for each.</li>
<li> Uncomment the for loop and append at 104th and 107th lines and comment out 101,102,105 and 108 lines. With these changes the code will generate single unique characters, the loop will run in multiples of 3 and frequency will be random for each.</li>
