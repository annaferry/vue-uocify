<template>
    <main class="page-notfound">
        <img class="icon-sad" src="@/assets/icon-sad.svg" alt="No encontrado">
        <h1 class="main-title">Página no encontrada</h1>

        <router-link to="/">
            Volver al inicio
        </router-link>
    </main>
</template>

<script>
export default {
    name:'NotFound',
    metaInfo: {
        title: '404 Error',
        meta: [
            {
            name: 'description',
            content: 'Error 404. Lo sentimos, no hemos podido encontrar la página que buscas'
            }
        ]
    }    
}
</script>


<style lang="scss" >

    .page-notfound{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top:200px;

        .icon-sad{
            width: 100px;
            margin-bottom: 20px;
        }
    }

</style>