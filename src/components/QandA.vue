<template>
  <section class="QandA">
    <div class="container">
      <h1>Pytania i odpowiedzi</h1>
      <div class="header">
        <h3>Jak będziemy oceniać uczestników?</h3>
        <div class="plus" @click="list1 = !list1">
          <span v-if="list1">-</span>
          <span v-else>+</span>
        </div>
      </div>
      <div class="list" :class="{ open: list1 }">
        <ul>
          <li>
            <p>(Eksperci ocenią głównie umiejętności miękkie streamerów)</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Kreatywność w wykonywaniu misji (w finale)</p>
          </li>
          <li>
            <div class="square"></div>
            <p>
              Częstotliwość streamowania (czy streamy są regularne, prowadzone,
              czy widzowie wiedzą jaki jest harmonogram)
            </p>
          </li>
          <li>
            <div class="square"></div>
            <p>Atmosferę panującą na streamie</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Jakość contentu i kreatywność</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Kontakt z widzami (interakcje, aktywność widzów itp.)</p>
          </li>
        </ul>
      </div>
      <div class="header">
        <h3>Jak będziemy oceniać uczestników?</h3>
        <div class="plus" @click="list2 = !list2">
          <span v-if="list2">-</span>
          <span v-else>+</span>
        </div>
      </div>
      <div class="list" :class="{ open: list2 }">
        <ul>
          <li>
            <p>(Eksperci ocenią głównie umiejętności miękkie streamerów)</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Kreatywność w wykonywaniu misji (w finale)</p>
          </li>
          <li>
            <div class="square"></div>
            <p>
              Częstotliwość streamowania (czy streamy są regularne, prowadzone,
              czy widzowie wiedzą jaki jest harmonogram)
            </p>
          </li>
          <li>
            <div class="square"></div>
            <p>Atmosferę panującą na streamie</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Jakość contentu i kreatywność</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Kontakt z widzami (interakcje, aktywność widzów itp.)</p>
          </li>
        </ul>
      </div>
      <div class="header">
        <h3>Jak będziemy oceniać uczestników?</h3>
        <div class="plus" @click="list3 = !list3">
          <span v-if="list3">-</span>
          <span v-else>+</span>
        </div>
      </div>

      <div class="list" :class="{ open: list3 }">
        <ul>
          <li>
            <p>(Eksperci ocenią głównie umiejętności miękkie streamerów)</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Kreatywność w wykonywaniu misji (w finale)</p>
          </li>
          <li>
            <div class="square"></div>
            <p>
              Częstotliwość streamowania (czy streamy są regularne, prowadzone,
              czy widzowie wiedzą jaki jest harmonogram)
            </p>
          </li>
          <li>
            <div class="square"></div>
            <p>Atmosferę panującą na streamie</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Jakość contentu i kreatywność</p>
          </li>
          <li>
            <div class="square"></div>
            <p>Kontakt z widzami (interakcje, aktywność widzów itp.)</p>
          </li>
        </ul>
      </div>
      <div class="QandA-footer">
        <button type="button" class="btn btn-primary">Weź udział</button>
        <h2>Masz pytania? Wbij na discorda</h2>
        <button type="button" class="btn btn-secondary">Discord</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      list1: false,
      list2: false,
      list3: false,
    };
  },
};
</script>