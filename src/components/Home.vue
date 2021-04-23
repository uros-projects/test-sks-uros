<template>
    <div>
        <Header />
        <PostList />
    </div>    
</template>

<script>
import Header from './Header'
import PostList from './PostList'

export default {
    name: 'Home',
    components: {
        Header,
        PostList
    }
}
</script>

<style>

</style>