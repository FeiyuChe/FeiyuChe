[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00CC68&center=true&vCenter=true&width=435&lines=Hello+world!)](https://git.io/typing-svg)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Read Specific Cookie</title>
</head>
<body>
    <h1>Specific Cookie</h1>
    <p id="cookie-output">Loading cookie...</p>

    <script>
        // Function to read a specific cookie by key
        function getCookie(key) {
            // Split the cookie string into an array of key=value pairs
            const cookieArray = document.cookie.split('; ');
            // Loop through the array to find the specific key
            for (let i = 0; i < cookieArray.length; i++) {
                const cookiePair = cookieArray[i].split('=');
                if (cookiePair[0] === key) {
                    return cookiePair[1]; // Return the value of the specific key
                }
            }
            return null; // Return null if the key is not found
        }

        // Function to display the specific cookie
        function displaySpecificCookie(key) {
            const value = getCookie(key);
            if (value) {
                document.getElementById('cookie-output').innerText = `Cookie '${key}': ${value}`;
            } else {
                document.getElementById('cookie-output').innerText = `Cookie '${key}' not found.`;
            }
        }

        // Call the function when the page loads
        window.onload = function() {
            displaySpecificCookie('user'); // Replace 'user' with the key you want to display
        };
    </script>
</body>
</html>

<!--
**FeiyuChe/FeiyuChe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
