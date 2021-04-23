<template>
    <div>
        <h1>Post Details Page</h1>
        <Header />
        <PostData />
        <div>
            <h1>Post Title</h1>
            <p>Post Text...</p>
        </div>
        <CommentList />
    </div>
</template>

<script>
import Header from './Header'
import PostData from './PostData'
import CommentList from './CommentList'

export default {
    name: 'PostDetails',
    components: {
        Header,
        PostData,
        CommentList
    }
}
</script>

<style>

</style>