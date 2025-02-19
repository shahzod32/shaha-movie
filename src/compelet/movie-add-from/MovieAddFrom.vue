<template>
        <div class='movie-add-form'>
            <h3>Yangi kino qo'shish</h3>
            <form>
                <input type="text" class='form-control new-movie-label' >
                <input type="text" class='form-control new-movie-label' >
                <button class="btn btn-outline-dark" type="submit">Qo'shish</button>
            </form>
            
        </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .movie-add-form{
        margin-top:2rem;
        padding: 1.5rem;
        background-color: #fcfaf5;
        box-shadow: 15px 15px 15px rgb(0, 0, 0.15); 
    }
</style>