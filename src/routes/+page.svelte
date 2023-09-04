<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<style lang="scss">


    h1{
        color : red;
        font-size: functions.toRem(60);

        @include breakpoint.up('lg'){
            color: blue;
        }


        @include breakpoint.down('lg'){
            color: blue;
        }


        @include breakpoint.down('md'){
            color: green;
        }
        
    }
</style>