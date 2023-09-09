<html>
  <h1 style="color:Blue">Close this web-site</h1>
    <button onclick="closeCurrentTab()">Закрити вкладку</button>

    <script>
        function closeCurrentTab() {
            if (confirm('Ви впевнені, realy?')) {
                window.close(); // Close web-site
            }
        }
    </script>
</html>
