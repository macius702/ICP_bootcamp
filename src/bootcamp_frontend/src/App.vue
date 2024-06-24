

<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Płynie w rzece woda prędko <br>
    Paweł tkwi na brzegu z wędką <br> <br>
    Siedzi, czeka, w wodę patrzy <br>
    Czy już ryba chwyta haczyk <br> <br>
    Wciąż w bezruchu tkwi jak grzyb <br>
    Bo w tej rzece nie ma ryb <br> <br>
    <button @click="zwiekszLicznik">Zwiększ licznik     </button>
    {{ licznik }}

  </main>
</template>

<script>
export default {
  data(){
    return {
      licznik: 0
    }
  },
  methods: {
    zwiekszLicznik(){
      this.licznik++
    }
  }
}
</script>