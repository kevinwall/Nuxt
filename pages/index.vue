<template>
  <div>
    <h2>
      Bem vindo ao meu app
    </h2>
  </div>
</template>

<script>
export default{
    head() {
        return {
            title: "Home page",
            meta: [
                {
                    hid: "descrição",
                    name: "descrição",
                    content: "home page do app"
                }
            ]
        };
    }
};
</script>
