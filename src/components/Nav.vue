<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"> ItemShop </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link :to="{ name: 'home-route' }" class="nav-link"> Home </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{ name: 'contact-route' }" class="nav-link"> Contact</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{ name: 'login-route'}" class="nav-link"> Login </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{ name: 'register-route'}" class="nav-link"> Register </router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>