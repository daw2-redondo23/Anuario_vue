<template>
    <div class="menu">
        <header>
                <div class="row bg-dark text-white border-bottom">
                    <div class="pb-3">
                        <div class="col-12 d-flex justify-content-between">
                        <img src="/img/logoLlefia.png" class="logo">
                        <div class="d-flex justify-content-end">
                            <p class="pt-3 pe-2 text-white">Rubén Redondo</p>
                            <a href=""><i class="fa-solid fa-user pt-3 ps-2 me-2 icono-perfil"></i></a> 
                                
                        </div>
                        </div>
                    </div>
                </div>
        </header>
    </div>
</template>

<script>
export default{
    name: 'Menu',
    props:{
        msg: String
    }
}
</script>

<style>

</style>
