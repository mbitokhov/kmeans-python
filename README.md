# kmeans-python
Kmeans on images in Python

Ever since I saw [this](https://www.youtube.com/watch?v=yR7k19YBqiw) Computerphile video, I've been interested in seeing what images I can create with k-means clustering

I've tried to make the code as optimized as I could, because as I found out, one line of code can make the difference between a program never finishing and finishing in seconds

So far, I've made it as optimized to run in under 3 seconds on my laptop for k=3.

# Usage

```bash
main.py [-h] [-o file] [-k K] [--all] file
```
-o is the output file to use, -k is the value k to use. --all is to run all k values between 1 and 16, and powers of 2 between 16-256
