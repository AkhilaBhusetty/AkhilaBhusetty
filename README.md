- 👋 Hi, I’m @AkhilaBhusetty
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---<div id="sectionHome">
        <div class="bg-container d-flex flex-column justify-content-end">
            <div class="tourism-card">
                <h1 class="main-heading">Tourism</h1>
                <p class="paragraph">Plan your trip.</p>
                <button class="button" onclick="display('sectionFavouritePlaces')">
                    Get Started
                </button>
            </div>
        </div>
    </div>

    <div id="sectionFavouritePlaces">
        <div class="favourite-places-bg-container">
            <h1 class="favourite-places-heading">Favourite Places</h1>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Taj Mahal</h1>
                    <p class="favourite-place-card-description">
                        If there was just one symbol to represent all of India, it would be
                        the Taj Mahal
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionGoldenTempleDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Golden Temple</h1>
                    <p class="favourite-place-card-description">
                        Amritsar is world-famous for the beautiful and highly revered Golden
                        Temple
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row">
                <div>
                    <h1 class="favourite-place-card-heading">Mysore Palace</h1>
                    <p class="favourite-place-card-description">
                        The Mysore Palace is a historical palace and the royal residence at
                        Mysore .
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row">
                <div>
                    <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
                    <p class="favourite-place-card-description">
                        Varanasi Temple is most famous Hindu temples dedicated to Lord Shiva
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png" class="favourite-place-card-image" />
            </div>
            <button class="btn btn-dark" onclick="display('sectionHome')">back</button>
        </div>
    </div>

    <div id="sectionTajMahalDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"> </span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"> </span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Taj Mahal</h1>
                    <p class="detailed-view-card-description">
                        The Taj Mahal is considered to be the greatest architectural
                        achievement in the whole range of Indo-Islamic architecture. Its
                        recognised architectonic beauty has a rhythmic combination of solids
                        and voids, concave and convex and light shadow; such as arches and
                        domes further increases the aesthetic aspect. Not a piece of
                        architecture, as other buildings are, but the proud passions of an
                        emperor’s love wrought in living stones.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>

    <div id="sectionGoldenTempleDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"> </span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"> </span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Golden Temple</h1>
                    <p class="detailed-view-card-description">
                        The Golden Temple, also known as Harmandir Sahib, meaning "abode of
                        God", is a gurdwara located in the city of Amritsar, Punjab, India.The
                        gurdwara is built around a man-made pool (sarovar) that was completed
                        by the fourth Sikh Guru, Guru Ram Das in 1577.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>
    <div class="detailed-view-bg-container">
        <h1 class="detailed-view-heading">Detailed View</h1>
        <div class="detailed-view-card-container">
            <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                    <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                    <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple1-img.png" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple2-img.png" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple3-img.png" class="d-block w-100" alt="..." />
                    </div>
                </div>
                <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>
            <div class="detailed-view-card-text-container">
                <h1 class="detailed-view-card-heading">Golden Temple</h1>
                <p class="detailed-view-card-description">
                    The Golden Temple, also known as Harmandir Sahib is a gurdwara
                    located in the city of Amritsar, Punjab, India. There are many
                    places to visit Near Golden Temple like Jallianwala Bagh, Wagah Border, Harike Wetland, Bathinda Fort.
                </p>
            </div>
        </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>


AkhilaBhusetty/AkhilaBhusetty is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
