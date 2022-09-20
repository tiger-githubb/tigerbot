<template>
    <h1>mon chat bot</h1>
</template>

<script>
export default {
    name: "mon-chatbot",

    methods: {
    },

    mounted() {
        (function (d, m) {
            var kommunicateSettings =
                { "appId": "2a15d92e11431a8d9bec93a655233c828", "popupWidget": true, "automaticChatOpenOnNavigation": true };
            var s = document.createElement("script"); s.type = "text/javascript"; s.async = true;
            s.src = "https://widget.kommunicate.io/v2/kommunicate.app";
            var h = document.getElementsByTagName("head")[0]; h.appendChild(s);
            window.kommunicate = m; m._globals = kommunicateSettings;
        })(document, window.kommunicate || {});
        /* NOTE : Use web server to view HTML files as real-time update will not work if you directly open the HTML file in the browser. */
    }

}
</script>

<style>
#mck-sidebox-launcher {
    background-color: red !important;
}
</style>