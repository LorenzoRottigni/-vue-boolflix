<template>
    <main>
        <div class="container">
            <div class="row">
                <div class="col-8 offset-2 mt-5">
                    <h1>Search films</h1>
                    <div class="input-group mb-3">
                        <span class="input-group-text" id="basic-addon3">https://example.com/users/</span>
                        <input type="text" class="form-control" id="basic-url" aria-describedby="basic-addon3"
                        v-model="searchString">
                    </div>
                    <div class="d-grid">
                        <button class="btn btn-primary">
                            Search
                        </button>
                    </div>
                </div>
            </div>
        </div>
        

    </main>
</template>
<script>
import axios from 'axios';
export default {
    name : 'Main',
    data(){
        return {
            searchString : undefined
        }
    },
    methods : {
        performCallAPI(){

        }
    }

}
</script>
