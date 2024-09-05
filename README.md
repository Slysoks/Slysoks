<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Slysoks - GitHub</title>
</head>
<body>
    <header>
        <p class="name">@Slysoks</p>
    </header>
    <main>
        <section>
            <p class="short-presentation">
                Hi, I'm Slysoks and I'm <span id="age"></span>. My real name is Nathan. 
                Since I was still a child, I've always been passionate about computers and technology.
                I started programming at the age of 10, when my father showed me Scratch, by the MIT.
                That was the beginning of my journey in the programming world. I next created basic
                programs in Python. That's were I discovered my passion for programming without
                any graphical interface.
            </p>
        </section>
    </main>
    <script>
        const birthday = new Date('March 15 2009');
        const today = new Date();
        const difference = today - birthday;
        const age = new Date(difference);
        document.getElementById('age').innerText = age.getFullYear() - 1970;
    </script>
</body>
</html>