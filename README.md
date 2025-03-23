# Eagler-Revive
Go to W3schools and past the following into the html try yourself:
```<html lang="en">
	<h1>Eagler Revive</h1>
    <span style="color: red;">Make sure Github Raw is unblocked!</span>
    <p>
    Credits:
    <li>Instel - Lead bypasser</li>
    <li>ChatGPT - Code help</li>
    <li>lax1dude - Made the Eaglercraft Client</li>
    <br>
    <button id="openContentBtn">Launch</button>
    <script>
        document.getElementById('openContentBtn').addEventListener('click', function() {
            var url = 'https://raw.githubusercontent.com/Instel12/archives/refs/heads/main/pages/gameroom01/assets/ID6.html';
            fetch(url)
                .then(response => response.text())
                .then(content => {
                    var newWindow = window.open('about:blank', '_blank');
                    newWindow.document.write(content);
                    newWindow.document.close();
                })

        });
    </script>
</html>
```
