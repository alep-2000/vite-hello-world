<script>
export default {

}
</script>

<template>
    <div>
        <div class="container">
            <div class="paragraph">
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br>
                    Totam illum alias rerum expedita consequuntur! <br>
                    Excepturi ut eligendi deleniti accusamus, possimus, <br>
                    vitae aliquid error illo dolorem et eum quasi ipsum modi. <br>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>
                    Id, ab, fugit consequatur nostrum molestias <br>
                    perspiciatis repellendus deleniti iste cumque reprehenderit harum repudiandae. <br>
                    Quisquam dolores repudiandae provident vero excepturi facilis delectus!
                </p>
            </div>
        </div>
    </div>
</template>

<style>
.container {
    width: 100%;
    height: 75vh;
    background-color: rgb(103, 42, 42);
}

.paragraph {
    width: 50%;
    height: 100%;
    background-color: black;
    margin: 0 auto;
    position: relative;
}

p {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    color: white;
}
</style>