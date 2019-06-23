# 000webhost banner injection mechanism
* As of 24 June 2019
1. Retrieve compiled HTML code.
2. Replace the first occurrence of "```</body>```" to "```<banner here></body>```".
3. Send the modified HTML code as response.

# Solution 001
* Add "```<!--</body>-->```" before "```</body>```" to your code.
* Note: "```require```" is suggested to use with this solution.
* Solution expired on: ?
