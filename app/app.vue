<script setup>
useHead({
  titleTemplate: (pageTitle) =>
    [pageTitle, "Gelungenes"].filter(Boolean).join(" | "),
  viewport: "width=device-width, initial-scale=1, maximum-scale=1",
  charset: "utf-8",
});
</script>

<template>
  <section class="section py-6">
    <div class="columns">
      <div class="column is-10 is-offset-1">
        <h1 class="title">Gelungenes</h1>
        <p class="subtitle">Wettkämpfe, die man nicht so schnell vergisst.</p>

        <div class="content">
          <p>
            Gelungenes steht für außergewöhnliche Sport- und
            Wettkampfveranstaltungen. Für Herausforderungen, bei denen es auf
            Leistung, Teamgeist und den Willen ankommt, bis zum Schluss
            durchzuziehen.
          </p>

          <p>
            Was 2023 mit dem Schanzenlauf Oberstdorf begann, ist inzwischen eine
            Reihe ganz unterschiedlicher Wettkämpfe – vom Treppenlauf in
            spektakulärer Kulisse bis zum Berglauf durch die Allgäuer
            Landschaft.
          </p>

          <p>Anspruchsvoll. Ungewöhnlich. Und ziemlich gelungen.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="hero is-success">
    <div class="hero-body px-0">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <section class="section">
            <h1 class="title has-text-white">Unsere Veranstaltungen</h1>
          </section>
        </div>
      </div>
    </div>
  </section>

  <div id="fire-trail-nesselwang" class="columns mt-6 row">
    <div
      class="column image is-7"
      style="
        background-image: url(images/fire-trail-nesselwang.jpg);
        background-position-y: 60%;
      "
    >
      &nbsp;
    </div>
    <div class="column is-4">
      <section class="section">
        <h2 class="title">
          <a href="//www.fire-trail-nesselwang.de"
            >Fire Trail <span>Nesselwang</span></a
          >
        </h2>
        <p class="years is-size-6 has-text-grey">seit 2025</p>

        <p>
          Beim Fire Trail geht Feuerwehrsport raus aus dem Gebäude und rauf auf
          den Berg. Die Strecke führt vom Explorer Hotel über Treppen, Waldwege
          und Steigungen bis zum Sportheim Böck auf rund 1.500 Metern Höhe.
          Gelaufen wird mit kompletter Ausrüstung gegen die Uhr – mitten durch
          die Landschaft rund um Nesselwang.
        </p>

        <p class="series-link">
          <small><a href="#fire-trail-immenstadt">Auch in Immenstadt →</a></small>
        </p>
      </section>
    </div>
  </div>

  <div class="columns mt-6 row reversed">
    <div
      class="column image is-7"
      style="
        background-image: url(images/muensterturmlauf-ulm.jpg);
        background-position-y: 0%;
        background-position-x: 100%;
      "
    >
      &nbsp;
    </div>
    <div class="column is-4 is-offset-1">
      <section class="section">
        <h2 class="title">
          <a href="//muensterturmlauf-ulm.gelungen.es"
            >Münsterturmlauf <span>Ulm</span></a
          >
        </h2>
        <p class="years is-size-6 has-text-grey">seit 2026</p>

        <p>
          560 Stufen führen vom Münsterplatz hinauf zum zweiten Kranz des Ulmer
          Münsters – rund 102 Höhenmeter. Für die Feuerwehrwertung wird die
          Strecke mit angeschlossenem Atemschutzgerät bewältigt. Ein Lauf mitten
          durch eines der bekanntesten Wahrzeichen Ulms, bei dem vor allem eines
          zählt: möglichst schnell nach oben.
        </p>
      </section>
    </div>
  </div>

  <div class="columns mt-6 row">
    <div
      class="column image is-7"
      style="
        background-image: url(images/munich-sunrise.jpg);
        background-position-y: 10%;
      "
    >
      &nbsp;
    </div>
    <div class="column is-4">
      <section class="section">
        <h2 class="title">
          <a href="//www.munich-sunrise.de">Munich <span>Sunrise</span></a>
        </h2>
        <p class="years is-size-6 has-text-grey">seit 2026</p>

        <article class="message">
          <div class="message-body">
            <blockquote>
              <p>
                Danke es war Mega schön heute! <mark>Genau meine Uhrzeit.</mark>
              </p>
            </blockquote>
            <p>— Jasmin(FF Seukendorf)</p>
          </div>
        </article>

        <p>
          32 Stockwerke in den Highlight Towers – und das früh am Morgen. Bei
          Munich Sunrise geht es durch die vollverglasten Treppenhäuser eines
          der markantesten Gebäude Münchens.
        </p>
      </section>
    </div>
  </div>

  <div id="eskalation-frankfurt" class="columns mt-6 row reversed">
    <div
      class="column image is-7"
      style="background-image: url(images/eskalation-frankfurt.jpg)"
    >
      &nbsp;
    </div>
    <div class="column is-4 is-offset-1">
      <section class="section">
        <h2 class="title">
          <a href="//eskalation-frankfurt.de"
            >Eskalation <span>Frankfurt</span></a
          >
        </h2>
        <p class="years is-size-6 has-text-grey">ab 2027</p>

        <article class="message">
          <div class="message-body">
            <blockquote>
              <p>Ja bist du deppert 🙈</p>
            </blockquote>
            <p>— Marcus (FF Taufkirchen/Vils)</p>
          </div>
        </article>

        <p>
          Bei Eskalation wird das Prinzip Treppenlauf einmal komplett neu
          gedacht. Denn hier bewegt sich die Treppe selbst: Gelaufen wird auf
          der Rolltreppe im MyZeil – nach oben, während sie nach unten fährt.
          <strong>Rise Against the Machine.</strong>
        </p>

        <p class="series-link">
          <small><a href="#eskalation-essen">Auch in Essen →</a></small>
        </p>
      </section>
    </div>
  </div>


  <section class="hero is-info">
    <div class="hero-body px-0">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <section class="section">
            <h1 class="title has-text-white">Unsere Ideen</h1>
          </section>
        </div>
      </div>
    </div>
  </section>

  <div id="fire-trail-immenstadt" class="columns mt-6 row reversed">
    <div
      class="column image is-7"
      style="background-image: url(images/fire-trail-immenstadt.jpg)"
    >
      &nbsp;
    </div>
    <div class="column is-4 is-offset-1">
      <section class="section">
        <h2 class="title">
          <a href="//www.fire-trail-immenstadt.de"
            >Fire Trail <span>Immenstadt</span></a
          >
        </h2>

        <p>
          Nach Nesselwang bekommt der Fire Trail eine zweite Station im Allgäu.
          Immenstadt wird damit Teil der Serie, die Feuerwehrsport mit Berglauf
          verbindet und die Herausforderung dorthin bringt, wo es nicht nur nach
          oben, sondern auch durch die Landschaft geht.
        </p>

        <p class="series-link">
          <small><a href="#fire-trail-nesselwang">Auch in Nesselwang →</a></small>
        </p>
      </section>
    </div>
  </div>

  <div class="columns mt-6 row">
    <div
      class="column image is-7"
      style="
        background-image: url(images/one-left-mannheim.jpg);
        background-position-x: 20%;
      "
    >
      &nbsp;
    </div>
    <div class="column is-4">
      <section class="section">
        <h2 class="title">One Left <span>Mannheim</span></h2>

        <p>
          Das Prinzip eines Backyard Ultras, nur eben im Treppenhaus des
          Victoria-Turms: Zu jeder Runde geht es gemeinsam an den Start, wer es
          nicht rechtzeitig wieder nach oben schafft, ist raus. Runde für Runde,
          so lange, bis nur noch eine Person übrig ist.
        </p>
      </section>
    </div>
  </div>

  <div id="eskalation-essen" class="columns mt-6 row reversed">
    <div
      class="column image is-7"
      style="background-image: url(images/eskalation-essen.jpg)"
    >
      &nbsp;
    </div>
    <div class="column is-4 is-offset-1">
      <section class="section">
        <h2 class="title">
          <a href="//eskalation-essen.de">Eskalation <span>Essen</span></a>
        </h2>

        <article class="message">
          <div class="message-body">
            <blockquote>
              <p>Das ist mal ne <mark>wilde Sache</mark> 🦾</p>
            </blockquote>
            <p>— Manuel (BwF Laupheim)</p>
          </div>
        </article>

        <p>
          Die längste freistehende Rolltreppe Deutschlands: 58 Meter und 24
          Höhenmeter am Ruhr Museum auf Zollverein. Erst läuft man sie im
          Stillstand, im Finale fährt sie dann nach unten – und es geht trotzdem
          rauf.
        </p>

        <p class="series-link">
          <small><a href="#eskalation-frankfurt">Auch in Frankfurt →</a></small>
        </p>
      </section>
    </div>
  </div>

  <div class="columns mt-6 row">
    <div
      class="column image is-7"
      style="background-image: url(images/fire-ride.jpg)"
    >
      &nbsp;
    </div>
    <div class="column is-4">
      <section class="section">
        <h2 class="title">Fire & Ride</h2>
        <!--<span class="tag">2027</span>-->

        <p>
          Warum endet der Wettkampf bislang eigentlich immer oben? Bei Fire &
          Ride befinden sich Start und Ziel <strong>unten</strong>, nach dem
          Lauf bergauf musst du also auch noch so schnell wie möglich wieder
          runter.
        </p>
      </section>
    </div>
  </div>

  <section class="hero has-background-grey">
    <div class="hero-body px-0">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <section class="section">
            <h1 class="title has-text-white">Bisherige Veranstaltungen</h1>
          </section>
        </div>
      </div>
    </div>
  </section>

  <div class="columns mt-6 row past">
    <div
      class="column image is-7"
      style="
        background-image: url(images/schanzenlauf-oberstdorf.jpg);
        background-position-y: 20%;
        background-position-x: 65%;
      "
    >
      &nbsp;
    </div>
    <div class="column is-4">
      <section class="section">
        <h2 class="title">
          <a href="//www.schanzenlauf-oberstdorf.de"
            >Schanzenlauf <span>Oberstdorf</span></a
          >
        </h2>
        <p class="years is-size-6 has-text-grey">2023</p>

        <article class="message">
          <div class="message-body">
            <blockquote cite="https://www.schanzenlauf-oberstdorf.de">
              <p>
                Ich würde mal vorsichtig behaupten, das war
                <mark>einer der härtesten Treppenläufe</mark>, den die
                (Feuerwehrsport-) Welt zu bieten hat 🙈
              </p>
            </blockquote>
            <p>— Alex (BF Bremen)</p>
          </div>
        </article>

        <p>
          Über 1.000 Stufen, 162 Höhenmeter und 412 Meter Strecke: die
          Heini-Klopfer-Skiflugschanze hinauf. Oben wartet nicht nur das Ziel,
          sondern auch eine Aussicht, die man sich erst einmal verdienen muss.
          Gelungenes hat den Schanzenlauf 2023 organisiert, inzwischen richtet
          ihn die Feuerwehr Oberstdorf selbst aus.
        </p>
      </section>
    </div>
  </div>

  <div class="columns mt-6 row reversed past">
    <div
      class="column image is-7"
      style="background-image: url(images/schachmatt-ulm.jpg)"
    >
      &nbsp;
    </div>
    <div class="column is-4 is-offset-1">
      <section class="section">
        <h2 class="title">
          <a href="//www.schachmatt-ulm.de">Schachmatt <span>Ulm</span></a>
        </h2>
        <p class="years is-size-6 has-text-grey">2024 – 2026</p>

        <article class="message">
          <div class="message-body">
            <blockquote cite="https://www.schachmatt-ulm.de">
              <p>Es tut schon weh, aber <mark>ist irgendwie geil</mark>.</p>
            </blockquote>
            <p>— Lukas (BF Ulm)</p>
          </div>
        </article>

        <p>
          18 Stockwerke, acht mögliche Durchgänge und immer nur zwei Teams
          gleichzeitig im direkten Duell: Schachmatt Ulm war ein
          K.-o.-Treppenlauf. Wer schneller oben war, kam weiter – wer verlor,
          war raus. Gelaufen wurde im Zweierteam und in kompletter
          Einsatzkleidung mit Atemschutzgerät auf dem Rücken.
        </p>
      </section>
    </div>
  </div>

  <section class="section py-6">
    <div class="columns mt-6">
      <div class="column is-10 is-offset-1">
        <div class="content">
          <p>Und das war erst der Anfang.</p>

          <p><mark class="special">Mal sehen, was als Nächstes kommt.</mark></p>
        </div>
      </div>
    </div>
  </section>

  <footer class="footer px-0">
    <div class="columns">
      <div class="column is-10 is-offset-1">
        <p>
          Gelungenes c/o Stefan Matheis · Alpenstraße 19, 87435 Kempten ·

          <a href="tel:+4916097048114">0160 970 48 114</a> ·
          <a href="mailto:stefan@gelungen.es">stefan@gelungen.es</a> ·

          <abbr
            title="Umsatzsteuer-Identifikationsnummer gemäß §27a Umsatzsteuergesetz"
            >UstID</abbr
          >: DE 273 589 132
        </p>
      </div>
    </div>
  </footer>
</template>

<style>
@import url("bulma");

@media screen and (min-width: 1024px) {
  .section {
    padding: 0;
  }
}

.row .column.image {
  background-size: cover;
  background-position: 50% 50%;
  height: 50vh;
}

.row.reversed {
  flex-direction: row-reverse;
}

mark {
  background-color: transparent;
  background-image: url(/yellow_highlight_bold_05.svg);
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: cover;
  white-space: nowrap;
}

mark.special {
  background-image: url(/green_highlight_bold_05.svg);
}

.title a {
  color: inherit;
  display: block;
}

html {
  scroll-behavior: smooth;
}

.series-link {
  margin-top: 1rem;
}

.title + .years {
  margin-top: -1rem;
  margin-bottom: 1.5rem;
}

.row.past .column.image {
  filter: grayscale(70%);
  transition: filter 0.4s;
}

.row.past:hover .column.image {
  filter: grayscale(0);
}
</style>
