<template>
    <div>
        <h1>Projeto em NuxtJS</h1>
        <p>Esse projeto mostra um routing feito com NuxtJS</p>
    </div>
</template>

<script>
export default{
    head() {
        return {
            title: "Sobre a aplicação",
            meta: [
                {
                    hid: "descrição",
                    name: "descrição",
                    content: "explicação sobre o objetivo do app"
                }
            ]
        };
    }
};
</script>