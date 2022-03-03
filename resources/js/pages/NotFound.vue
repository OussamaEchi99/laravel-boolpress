<template>
    <section>
        <div class="container">
            <h2>
                Errore 404
                La pagina che stai cercando non esiste
            </h2>

            <router-link class="nav-link" :to="{ name: 'blog' }">Torna alla Sezione Blog per leggere le ultime nuove notizie</router-link>
        </div>
    </section>
</template>

<script>
export default {
    name: 'NotFound'
}
</script>