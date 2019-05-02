<template>
    <div class="section">
        <div class="container">
            <div class="columns" style='min-height:800px;'>
                <div class="column is-6">
                    <div class="image is-2by2">
                        <img src="https://images.unsplash.com/photo-1533629663071-038eb2b96fcf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80">
                    </div>
                </div>
                <div class="column is-5 is-offset-1">
                    <div class="title is-2">Test Product</div>
                    <p class="title is-3 has-text-muted">$ 15</p>
                    <hr>
                    <br>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s</p>
                    <br>
                    <br>
                    <p class='level'>
                        <router-link to="/order" class="button is-large is-primary level-item has-text-centered">Buy Now</router-link>
                    </p>
                    <br>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {}
</script>