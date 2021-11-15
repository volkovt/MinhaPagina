<template>
  <div class="stack-body">
    <div>
      <div id="java" class="stacks">
        <img src="../assets/images/java.png" alt="Java" title="Springboot, Hibernate/JPA"/>
      </div>
      <div id="javascript" class="stacks">
        <img src="../assets/images/javascript.png" alt="Javascript" />
      </div>
      <div id="typescript" class="stacks">
        <img src="../assets/images/typescript.png" alt="Javascript" />
      </div>
      <div id="vue-js" class="stacks">
        <img src="../assets/images/vue.png" alt="VueJS" />
      </div>
      <div id="react" class="stacks">
        <img src="../assets/images/react.png" alt="ReactJS" />
      </div>
    </div>
  </div>
</template>

export default { }

<style lang="scss">
.stack-body {
    height: 100%;
  /* padding: 5vh; */
}

.stack-body > div {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
}

.stacks {
  border-radius: 50%;
  margin: 2vh;

  &#java {
    width: 70px;
    height: 70px;
    background-color: rgb(235, 235, 235);
    box-shadow: 1px 1px 8px 3px rgb(138, 138, 138, 0.75);
    &:hover {
      box-shadow: 1px 1px 8px 6px rgb(138, 138, 138, 0.75);
    }
    & > img {
      width: 100%;
      height: 100%;
    }
  }

  &#javascript {
    width: 70px;
    height: 70px;
    background-color: #fadf1c;
    box-shadow: 1px 1px 8px 3px rgb(138, 138, 138, 0.75);
    &:hover {
      box-shadow: 1px 1px 8px 6px rgb(138, 138, 138, 0.75);
    }
    & > img {
      width: 100%;
      height: 100%;
    }
  }

  &#typescript {
    width: 70px;
    height: 70px;
    background-color: #017acb;
    box-shadow: 1px 1px 8px 3px rgb(138, 138, 138, 0.75);
    &:hover {
      box-shadow: 1px 1px 8px 6px rgb(138, 138, 138, 0.75);
    }
    & > img {
      width: 100%;
      height: 100%;
    }
  }

  &#vue-js {
    width: 70px;
    height: 70px;
    background-color: rgb(235, 235, 235);
    box-shadow: 1px 1px 8px 3px rgb(138, 138, 138, 0.75);
    &:hover {
      box-shadow: 1px 1px 8px 6px rgb(138, 138, 138, 0.75);
    }
    & > img {
      width: 100%;
      height: 100%;
    }
  }

  &#react {
    width: 70px;
    height: 70px;
    background-color: rgb(235, 235, 235);
    box-shadow: 1px 1px 8px 3px rgb(138, 138, 138, 0.75);
    &:hover {
      box-shadow: 1px 1px 8px 6px rgb(138, 138, 138, 0.75);
    }
    & > img {
      width: 100%;
      height: 100%;
    }
  }
}
</style>
