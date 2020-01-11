<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown"
                aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-around" id="navbarNavDropdown">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <a class="nav-link text-uppercase p-3" href="#">About the company </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-uppercase p-3" href="#">Investments</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-uppercase p-3" href="#">Career</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-uppercase p-3" href="#">Reference</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-uppercase p-3" href="#">Reviews</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-uppercase p-3" href="#">Contacts</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-uppercase p-3" href="#">Log In</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle p-3" href="#" id="navbarDropdownMenuLink" role="button"
                            data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            English
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>


<style scoped>

/* fonts */
@font-face {
    font-family: "helvetica-neue-cyr-black";
    src: url("../assets/fonts/HelveticaNeueCyr-Black.otf") format("woff"),
        url("../assets/fonts/HelveticaNeueCyr-Black.otf") format("opentype"),
        url("../assets/fonts/HelveticaNeueCyr-Black.otf") format("truetype");
}

@font-face {
    font-family: "helvetica-neue-cyr-bold";
    src: url("../assets/fonts/HelveticaNeueCyr-Bold.otf") format("woff"),
        url("../assets/fonts/HelveticaNeueCyr-Bold.otf") format("opentype"),
        url("../assets/fonts/HelveticaNeueCyr-Bold.otf") format("truetype");
}

nav a {
    font-size: 0.8rem;
    font-family: 'helvetica-neue-cyr-bold';
    color: #333333;
    padding: 1.2rem;
}
</style>