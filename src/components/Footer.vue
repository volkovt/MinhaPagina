<template>
  <div
    class="app-footer d-flex flex-column flex-md-row align-items-center py-md-2 border-top shadow"
  >
    <div class="container d-flex justify-content-center">
      <div class="d-flex justify-content-evenly">
        <div
          id="github"
          class="contatos mx-3"
          alt="github"
          @click="(event) => onClickContatos('github')"
        ></div>
        <div
          id="linkedin"
          class="contatos mx-3"
          alt="linkedin"
          @click="(event) => onClickContatos('linkedin')"
        ></div>
        <div
          id="instagram"
          class="contatos mx-3"
          alt="instagram"
          @click="(event) => onClickContatos('instagram')"
        ></div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  methods: {
    onClickContatos(linkName: string): void {
        switch(linkName) {
            case 'github':
                window.open("https://github.com/volkovt", "_blank");
                break;
            case 'linkedin':
                window.open("https://www.linkedin.com/in/diego-melo-6ba44068", "_blank");
                break;
            case 'instagram':
                window.open("https://www.instagram.com/diieegomelo", "_blank");
                break;
        }
    },
  },
};
</script>

<style lang="scss">
.app-footer {
  box-shadow: 0px -4px 5px 0px rgba(0, 0, 0, 0.75);
  background-color: rgb(48, 31, 59);
  /* position: absolute;
  bottom: 0; */
}

.contatos {
  box-shadow: 3px 3px 5px 1px rgba(0, 0, 0, 0.75);
  width: 50px;
  height: 50px;

  &:hover {
    box-shadow: 3px 3px 7px 6px rgba(0, 0, 0, 0.75);
    cursor: pointer;
  }

  &#github {
    background-color: rgb(48, 31, 59);
    background-image: url("../assets/images/github.png");
    background-repeat: no-repeat;
    background-size: 100%;
    border-radius: 100%;
  }
  &#linkedin {
    background-color: rgb(48, 31, 59);
    background-image: url("../assets/images/linkedin.png");
    background-repeat: no-repeat;
    background-size: 100%;
    border-radius: 20%;
  }

  &#instagram {
    background-color: rgb(48, 31, 59);
    background-image: url("../assets/images/instagram.png");
    background-repeat: no-repeat;
    background-size: 100%;
    border-radius: 20%;
  }
}
</style>
