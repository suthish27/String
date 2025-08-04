# String
📘 Java Strings – Overview
🔤 What is a String in Java?
In Java, a String is a sequence of characters used to represent textual data. Strings are immutable, meaning once a String object is created, its value cannot be changed. Java provides the String class in the java.lang package to work with strings.

✨ Key Features
Immutable – Once created, the value of a string cannot be changed.

Stored in String Pool – String literals are stored in a special memory area to save memory and improve performance.

Rich API – Java provides a variety of built-in methods like length(), substring(), charAt(), equals(), replace(), and many more.

🛠️ Common Operations
Operation	Method Example
Length	str.length()
Concatenation	str1 + str2 or str1.concat(str2)
Substring	str.substring(0, 5)
Character access	str.charAt(2)
Comparison	str.equals(str2) or str.equalsIgnoreCase(str2)
Search	str.contains("word"), str.indexOf("a")
Replace	str.replace('a', 'b')
Split	str.split(" ")
Trim whitespace	str.trim()
