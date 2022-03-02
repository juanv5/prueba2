# prueba2
SuperHero!
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="shortcut icon" type="image/png" href="assets/img/favicon.ico" />
    <meta name="author" content="Juan Vega" />
    <meta name="description" content="#" />

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
    <link rel="stylesheet" href="css/style.css" />

    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
    <script src="https://canvasjs.com/assets/script/canvasjs.min.js"></script>
    <script src="assets/js/script.js"></script>

    <title>SuperHero</title>
</head>

<body>

    <header>
        <nav class="navbar navbar-dark bg-dark">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="assets/img/sh2.jpg" alt="" width="40" height="30" class="d-inline-block align-text-top me-2"> SuperHero
                </a>
            </div>
        </nav>
    </header>

    <main>
        <section class="container">
            <div class="text-center my-4">
                <img src="assets/img/sh1.jpg" class="img-fluid" alt="SuperHero">
            </div>
            <div class="row">
                <h1>Encuentra tu SuperHero</h1>
            </div>
            <div class="row mt-3">
                <form id="super-form">
                    <div class="mb-3">
                        <label for="super-id" class="form-label">Ingresa el número del SuperHero a buscar</label>
                        <input type="number" class="form-control" id="super-id" required>
                    </div>
                    <button type="submit" class="btn btn-primary">Buscar</button>
                </form>
            </div>
            <div id="super-detail" class="row my-4"></div>
        </section>
    </main>
</body>

</html>
