<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- titre de la page -->
    <title>Apprentissage html</title>
    <!-- icone de l'onglet -->
    <link rel="shortcut" href="logo-html.png">
</head>

<body>
    <header>
        <div>
            <h1><span>&#9998;</span>titre H1</h1>
            <p>texte. <em>texte italique.</em> <strong>texte en gras.</strong><span>l'élement en span ne revient pas à
                    la ligne</span>.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil deleniti necessitatibus praesentium
                repudiandae ducimus.
                Dignissimos voluptatibus eligendi aliquid sunt, molestias asperiores tempore quos quisquam, mollitia vel
                minus neque provident totam?</p>
    </header>
    </div>
    <section>
        <div>
            <h2>titre H2 - Photo</h2>
            <img src="logo-html.png" alt="photo logo html 5">
        </div>
        <div>
            <h3>titre H3 - Listes</h3>
            <ul>
                <li>UL = unordered list</li>
                <li>UL = unordered list</li>
                <li>UL = unordered list</li>
            </ul>
            <ol>
                <li>OL = ordered list</li>
                <li>OL = ordered list</li>
                <li>OL = ordered list</li>
            </ol>
        </div>
        <div>
            <h4>titre H4 - Tableaux</h4>
            <table border="1" width="50%">
                <!-- légende -->
                <caption>Population d'europe</caption>
                <!-- En tête -->
                <thead>
                    <tr>
                        <th>Pays</th>
                        <th>Population</th>
                    </tr>
                </thead>
                <!-- corps du tableau -->
                <tbody>
                    <tr>
                        <td>France</td>
                        <td>66M</td>
                    </tr>
                    <tr>
                        <td>Allemagne</td>
                        <td>82M</td>
                    </tr>
                    <tr>
                        <td>Espagne</td>
                        <td>47M</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <div>
            <h5>titre H5 - Liens</h5>
            <a href="https://htmlcheatsheet.com/" targets=_blank> HTML cheats sheet</a>
            <br>
            <a href="https://www.toptal.com/designers/htmlarrows/symbols/" targets="_blank">Icônes en HTML</a>
        </div>
        <div>
            <h6>titre H6 - Vidéo</h6>
            <video src="running-27539.mp4" height="150" autoplay loop muted></video>
        </div>
    </section>
    <br>
    <section>
        <h2>Formulaire</h2>
        <form action="/action.php" method="post">
        <label for="name">Nom</label>
        <input id="name" type="text" placeholder="Entrez votre nom"><br>
        <label for="age">Age</label>
        <input id="age" type="number" min="0" max="99" step="1" value="18" placeholder="Entez votre âge">

        <!-- Input select -->
        <label for="gender">Genre</label>
        <select id="gender">
            <option value="Homme">Homme</option>
            <option selected value="Femme">Femme</option>
        </select><br>

        <!-- Input radio -->
        <div>
            <input type="radio" name="type" id="human">
            <label for="human">Humain</label>

            <input type="radio" name="type" checked id="dog">
            <label for="human">Chien</label>

            <input type="radio" name="type" id="cat">
            <label for="human">Chat</label>
        </div>

            <textarea cols="30" rows="10" placeholder="Spécifiez autre ici"></textarea><br>

            <!-- Input checkbox -->
            <label><input type="checkbox" name="type"/>Accepter les CGU</label>
            <label><input type="checkbox" name="type"/>Refuser les CGU</label>
            <input type="submit" value="Valider">
        </form>
    </section>
    <br>
    <!-- Mail & envoi de fichier -->
    <footer>
        <a href="mailto:fjrjv@gmail.com">Ecrire à cette adresse pour aucune raison</a>
        <br>
        <a href="essai.txt" download="nom-du-fichier">Télécharger l'essai</a>
    </footer>
</body>

</html>
