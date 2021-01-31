The program thought that the addition meant concatenating two strings when we wanted to add two numbers together. This is why when I put inputed '1' and '2', I received '12' instead of '3'. The fix was to use the Number() method which converts a string to a number. Therefore, I simply changed num1 and num2 to be Number(num1) and Number(num2).

1. citylots
2. part2.js
3. 11.7 MB
4. 6.32s
5. Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData
