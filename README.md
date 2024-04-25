# CS239 Final

### Description
This project is an explanation of RSA encryption and also a rudementary way to encode and decode a message in twine.

### Code descriptions

This code selects p and q from two random lists of three digit primes. This is to allow people to have different encryption keys when they use the program.

![image](https://github.com/joeygarberick/CS239-Final/assets/112030126/3c430d59-91cf-47d4-a8d9-54a8e2feabf6)

This selects a small e coprime with phi

![image](https://github.com/joeygarberick/CS239-Final/assets/112030126/d7947600-b509-42d0-9503-2d2dacbe18e3)

This code generates the decryption key. 

![image](https://github.com/joeygarberick/CS239-Final/assets/112030126/84abcf08-34ea-4b02-9892-3a0fd473a5f8)

This code will encrypt the message. Whats cool about this is the implementation of power mod evaluates in log(e) time.

![image](https://github.com/joeygarberick/CS239-Final/assets/112030126/d13807f1-8034-409f-9f04-22c49858cfd6)

This is the decryption code implementing that same fast power mod algorithm, which is much more useful here as the decryption key is rather large.

![image](https://github.com/joeygarberick/CS239-Final/assets/112030126/c80bc36e-06fb-42e4-a4d4-ebf4839239a6)
