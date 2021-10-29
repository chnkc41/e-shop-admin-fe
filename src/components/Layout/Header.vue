<template>
      <!--========== HEADER ==========-->
        <header class="header">
            <div class="header__container">
                <img src="@/assets/img/perfil.jpg" alt="" class="header__img">

                <a href="#" class="header__logo">Chn Design</a>
    
                <div class="header__search">
                    <input type="search" placeholder="Search" class="header__input">
                    <i class='bx bx-search header__icon'></i>
                </div>
    
                <div class="header__toggle" @click="showMobileMenu = !showMobileMenu">
                    <i class='bx' id="header-toggle" :class="showMobileMenu ? 'bx-menu' : 'bx-x'"></i>
                </div>
            </div>
        </header>
</template>

<script>
export default {
    data() {
        return {
            showMobileMenu: false
        }
    }
}
</script>