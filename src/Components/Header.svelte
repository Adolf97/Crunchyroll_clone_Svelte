<script>
    import { CaretDownFill } from 'svelte-bootstrap-icons'
    import Logo from '../lib/assets/Crunchyroll-logo.png'
    import '../Styles/Header.css'
</script>

<div class="header__container">
    <div class="logo__container">
        <img src={Logo} alt="Crunchyroll Logo">
    </div>
    <div class="menu__container">
        <ul class="menu__list">
            <li class="menu__item">Browse <CaretDownFill class="icon" /></li>
            <li class="menu__item">Manga</li>
            <li class="menu__item">Games</li>
            <li class="menu__item">News <CaretDownFill class="icon" /></li>
        </ul>
    </div>
    <div class="icons__container">
        <div class="findAnime__container each_icon__container">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-search icon_search" viewBox="0 0 16 16">
                <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
            </svg>
        </div>
        <div class="bookmark__container each_icon__container">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-bookmark icon_bookmark" viewBox="0 0 16 16">
                <path d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v13.5a.5.5 0 0 1-.777.416L8 13.101l-5.223 2.815A.5.5 0 0 1 2 15.5V2zm2-1a1 1 0 0 0-1 1v12.566l4.723-2.482a.5.5 0 0 1 .554 0L13 14.566V2a1 1 0 0 0-1-1H4z"/>
            </svg>
        </div>
        <div class="user__container each_icon__container">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-person-circle icon_user" viewBox="0 0 16 16">
                <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"/>
                <path fill-rule="evenodd" d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm8-7a7 7 0 0 0-5.468 11.37C3.242 11.226 4.805 10 8 10s4.757 1.225 5.468 2.37A7 7 0 0 0 8 1z"/>
            </svg>
            <CaretDownFill class="icon" />
        </div>
    </div>
</div>