# co2-emission-tracker1
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>CO2 Emissionsdaten</title>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo" />
        <h1>CO2 Emission Tracker</h1>
        <nav>
            <ul>
                <li><a href="#home">Startseite</a></li>
                <li><a href="#about">Über uns</a></li>
                <li><a href="#data">Daten</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="data">
            <h2>CO2 Emissionsdaten</h2>
            <input type="text" id="filter" placeholder="Filtere nach Land oder Unternehmen" />
            <table id="emissionTable">
                <thead>
                    <tr>
                        <th>Land</th>
                        <th>Unternehmen</th>
                        <th>CO2 Emissionen (Tonnen)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Deutschland</td>
                        <td>Unternehmen A</td>
                        <td>1000</td>
                    </tr>
                    <tr>
                        <td>USA</td>
                        <td>Unternehmen B</td>
                        <td>2000</td>
                    </tr>
                    <!-- weitere fiktive Daten hier -->
                </tbody>
            </table>
        </section>
    </main>
    <footer>
        <p>© 2023 CO2 Emission Tracker. Alle Rechte vorbehalten.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
