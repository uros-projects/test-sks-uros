<template>
    <div>
        <h1>Post Details Page</h1>
        <CommentList />
    </div>
</template>

<script>
import CommentList from './CommentList'

export default {
    name: 'Post',
    components: {
        CommentList
    }
}
</script>

<style>

</style>