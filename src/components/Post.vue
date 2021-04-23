<template>
    <div>
        <h1>One Post Placeholder</h1>
        <h1>Post Title</h1>
        <p>Post Text</p>
        <PostData />        
    </div>
</template>

<script>
import PostData from './PostData'

export default {
    name: 'Post',
    components: {
        PostData
    }
}
</script>

<style>

</style>