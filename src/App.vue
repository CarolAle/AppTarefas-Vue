<template>
  <div id="app">
    <section class="hero is-primary is-bold is-fullheight">
      <div class="hero-head">
        <nav class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <a class="navbar-item">
                VueJs Tutorial
              </a>
            </div>
          </div>
        </nav>
      </div>
      <div class="hero-body">
        <div class="container has-text-centered">
          <todo-card></todo-card>
        </div>
      </div>
      <div class="hero-foot">
        <div class="container">
          <div class="content has-text-centered">
            <p>
              <strong>VueJs Tutorial</strong>
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import TodoCard from './components/TodoCard'

  export default {
    name: 'app',
    components: {
      TodoCard
    },

    data () {
      return {
        msg: 'hello world!'
      }
    }
  }
</script>